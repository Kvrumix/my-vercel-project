# my-vercel-project
To my love
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Love to Bella Castro</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #fff5f5;
      color: #333;
      line-height: 1.6;
    }
    
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    
    header {
      background: linear-gradient(135deg, #ff758c 0%, #ff7eb3 100%);
      color: white;
      text-align: center;
      padding: 60px 20px;
      margin-bottom: 40px;
    }
    
    h1 {
      font-family: 'Pacifico', cursive;
      font-size: 3.5rem;
      margin-bottom: 20px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    }
    
    h2 {
      font-family: 'Pacifico', cursive;
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #ff758c;
    }
    
    .subtitle {
      font-size: 1.2rem;
      font-weight: 300;
      max-width: 700px;
      margin: 0 auto;
    }
    
    .heart-icon {
      font-size: 2rem;
      color: #ff758c;
      margin: 0 10px;
      animation: pulse 1.5s infinite;
    }
    
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    
    .letter {
      background: white;
      border-radius: 10px;
      padding: 40px;
      margin: 40px 0;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      position: relative;
    }
    
    .letter::before {
      content: '';
      position: absolute;
      top: -15px;
      left: 50%;
      transform: translateX(-50%);
      width: 30px;
      height: 30px;
      background: white;
      transform: rotate(45deg);
    }
    
    .letter p {
      margin-bottom: 20px;
      font-size: 1.1rem;
    }
    
    .signature {
      font-family: 'Pacifico', cursive;
      font-size: 1.8rem;
      text-align: right;
      margin-top: 30px;
      color: #ff758c;
    }
    
    .reasons-section {
      background: white;
      border-radius: 10px;
      padding: 40px;
      margin: 40px 0;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }
    
    .love-button {
      background: linear-gradient(135deg, #ff758c 0%, #ff7eb3 100%);
      color: white;
      font-family: 'Montserrat', sans-serif;
      font-size: 1.2rem;
      font-weight: 600;
      padding: 15px 30px;
      border: none;
      border-radius: 50px;
      cursor: pointer;
      margin-top: 20px;
      transition: all 0.3s ease;
      box-shadow: 0 4px 15px rgba(255, 117, 140, 0.4);
    }
    
    .love-button:hover {
      transform: translateY(-5px);
      box-shadow: 0 7px 20px rgba(255, 117, 140, 0.6);
    }
    
    .love-button:active {
      transform: translateY(0);
    }
    
    .reason-display {
      margin-top: 30px;
      min-height: 100px;
      font-size: 1.5rem;
      font-weight: 300;
      color: #ff758c;
      padding: 20px;
      border-radius: 10px;
      background-color: #fff5f5;
      transition: all 0.3s ease;
    }
    
    .reason-display.show {
      animation: fadeIn 0.5s ease;
    }
    
    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    
    footer {
      text-align: center;
      padding: 40px 0;
      margin-top: 40px;
      background: linear-gradient(135deg, #ff758c 0%, #ff7eb3 100%);
      color: white;
    }
    
    .footer-heart {
      font-size: 1.5rem;
      animation: pulse 1.5s infinite;
    }
    
    @media (max-width: 768px) {
      h1 {
        font-size: 2.5rem;
      }
      
      h2 {
        font-size: 2rem;
      }
      
      .reason-display {
        font-size: 1.2rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>My Love to Bella Castro</h1>
      <p class="subtitle">Every moment with you is a treasure, every memory a gift. This is my dedication to our love story.</p>
      <div>
        <span class="heart-icon">❤️</span>
        <span class="heart-icon">❤️</span>
        <span class="heart-icon">❤️</span>
      </div>
    </div>
  </header>
  
  <main class="container">
    <section class="letter">
      <h2>My Dearest Bella,</h2>
      <p>Words cannot express the joy you've brought into my life. From the moment we met, I knew there was something special about you - the way you smile, the sound of your laughter, and the kindness in your heart.</p>
      <p>Every day with you is an adventure, and I cherish each moment we spend together. You've shown me what it means to truly love and be loved in return.</p>
      <p>This page is just a small token of my affection, a digital love letter that I hope brings a smile to your face whenever you visit it.</p>
      <p>I promise to continue loving you, supporting you, and being your biggest fan in all your endeavors.</p>
      <div class="signature">With all my love,<br>Your Secret Admirer</div>
    </section>
    
    <section class="reasons-section">
      <h2>Why I Love You</h2>
      <p>Click the button to discover one of the many reasons why you mean the world to me.</p>
      <button class="love-button" id="reasonButton">Show Me Why You Love Me</button>
      <div class="reason-display" id="reasonDisplay"></div>
    </section>
  </main>
  
  <footer>
    <div class="container">
      <p>Created with <span class="footer-heart">❤️</span> for Bella Castro</p>
      <p>Forever and Always</p>
    </div>
  </footer>
  
  <script>
    // Array of reasons why I love you
    const reasons = [
      "Your smile lights up my entire world.",
      "The way you laugh makes my heart melt.",
      "You make me feel safe and loved.",
      "Your kindness is endless and inspiring.",
      "You always know how to cheer me up.",
      "Your passion for life amazes me.",
      "I love the way you give me backshots (jokes) .",
      "You believe in me when I doubt myself.",
      "You are incredibly strong and brave.",
      "Your voice is my favorite sound.",
       "I can be completely myself around you.",
      "You listen with your heart, not just your ears.",
      "The random stims you do.",
      "You're beautiful inside and out.",
      "I admire your honesty.",
      "You make every day better just by being you.",
      "You have the purest soul sometimesss.",
      "You care about others so deeply.",
      "You make even the smallest moments enjoyable.",
      "Your creativity amazes me.",
      "You're my biggest supporter.",
      "I love your ambition to play league RELIGOUSLY.",
      "You inspire me to be a better person.",
      "You gives me butterflies.",
      "You're incredibly thoughtful.",
      "Your laugh is contagious.",
      "You never give up on me.",
      "You're my favorite person to share life with.",
      "You surprise me in the sweetest ways.",
      "You make love feel effortless.",
      "You see the best in people.",
      "You make dreams seem possible.",
      "You're a light in my life.",
      "You choose love every single day.",
      "Your patience amazes me mhm.",
      "You're my safe place.",
      "You always know what to say.",
      "You're simply unforgettable.",
      "You are my sunshine and my moonlight.",
      "I feel lucky every day because of you.",
      "You teach me what love truly means.",
      "You make my sol feel complete ( get it... ).",
      "You laugh at my terrible jokes.",
      "You trust me with your heart.",
      "You forgive with so much grace.",
      "You bring out the best in me.",
      "You're my best friend and soulmate.",
      "You love me for who I am.",
      "You make even silence feel special.",
      "Your optimism is contagious.",
      "You have a heart of gold.",
      "You're my forever favorite.",
      "You keep me grounded.",
      "You make time stand still.",
      "You believe in fairytales with me.",
      "You complete my world.",
      "You see the beauty in everything.",
      "You fill my life with laughter.",
      "You're my partner in everything.",
      "You cherish every little thing.",
      "You're a gift I treasure.",
      "You dance with my heart.",
      "You're my everything.",
      "You are my dream come true.",
      "You give me strength every day.",
      "You understand my silence.",
      "You're a masterpiece.",
      "You stay even when things get hard.",
      "You light up my darkest days.",
      "You are my answered prayer.",
      "You're the reason I smile.",
      "You show me unconditional love.",
      "You accept all of me.",
      "You're simply irreplaceable.",
      "You are more than enough.",
      "You are my miracle.",
      "You make my heart race.",
      "You make my soul sing.",
      "You fill my heart with peace.",
      "You make me laugh till I cry.",
      "You're better than my best dreams.",
      "You love with your whole heart.",
      "You make life sweeter.",
      "You are my greatest blessing.",
      "You make every goodbye harder.",
      "You give meaning to my life.",
      "You are my forever and always.",
      // New ones about her personally:
      "You sing like an actual angel and it melts me every time.",
      "You're a little freaky sometimes... and honestly, I love it.",
      "Your music taste is actually god-tier.",
      "You always have songs that somehow fit exactly what I'm feeling.",
      "You make even late-night talks feel magical.",
      "You make me feel wanted in a way no one else ever has.",
      "You're my personal concert and my safe place at the same time."
    ];
    
    // Function to display a random reason
    function showRandomReason() {
      const reasonDisplay = document.getElementById('reasonDisplay');
      const randomIndex = Math.floor(Math.random() * reasons.length);
      
      // Remove the show class to reset animation
      reasonDisplay.classList.remove('show');
      
      // Trigger reflow to restart animation
      void reasonDisplay.offsetWidth;
      
      // Set new text and add show class
      reasonDisplay.textContent = reasons[randomIndex];
      reasonDisplay.classList.add('show');
    }
    
    // Add event listener to the button
    document.getElementById('reasonButton').addEventListener('click', showRandomReason);
    
    // Show a random reason when the page loads
    window.addEventListener('load', showRandomReason);
  </script>
</body>
</html>
