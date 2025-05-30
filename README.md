<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JS Hub - Interactive JavaScript Learning</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <header>
    <div class="logo">📘 JS Hub</div>
    <nav>
      <a href="index.html" class="active">Home</a>
      <a href="notes.html">Notes</a>
      <a href="quizzes.html">Quizzes</a>
      <a href="assessment.html">Assessment</a>
      <a href="game.html">Game</a>
      <a href="editor.html">Playground</a>
      <button class="mode-toggle" onclick="toggleMode()"><img src="image/dark-mode.svg" class="mode" alt="Dark mode toggle"></button>
      <button class="music-toggle" onclick="toggleMusic()"><img src="image/music-on.svg" class="mode" alt="Music toggle"></button>
    </nav>
  </header>

  <main>
    <!-- Hero Section -->
    <section class="hero">
      <div class="hero-box">
        <div class="js-logo">
          <svg viewBox="0 0 630 630" width="80" height="80">
            <rect width="630" height="630" fill="#f7df1e"/>
            <path d="m423.2 492.19c12.69 20.72 29.2 35.95 58.4 35.95 24.53 0 40.2-12.26 40.2-29.2 0-20.3-16.1-27.49-43.1-39.3l-14.8-6.35c-42.72-18.2-71.1-41-71.1-89.2 0-44.4 33.83-78.2 86.7-78.2 37.64 0 64.7 13.1 84.2 47.4l-46.1 29.6c-10.15-18.2-21.1-25.37-38.1-25.37-17.34 0-28.33 11-28.33 25.37 0 17.76 11 24.95 36.4 35.95l14.8 6.34c50.3 21.57 78.7 43.56 78.7 93 0 53.3-41.87 82.5-98.1 82.5-54.98 0-90.5-26.2-107.88-60.54zm-209.13 5.13c9.3 16.5 17.76 30.45 38.1 30.45 19.45 0 31.72-7.61 31.72-37.2v-201.3h59.2v202.1c0 61.3-35.94 89.2-88.4 89.2-47.4 0-74.85-24.53-88.81-54.075z"/>
          </svg>
        </div>
        <h1 class="typing-text"></h1>
        <p class="hero-subtitle">The interactive playground for mastering JavaScript fundamentals and beyond</p>
        <button class="greet-btn" onclick="askName()">🔥 Greet Me</button>
        <div class="code-snippet">
          <pre><code>// Start your journey with a simple console.log
console.log("Hello, JavaScript!");</code></pre>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section class="features">
      <h2>Why Learn With JS Hub?</h2>
      <div class="features-grid">
        <div class="feature-card">
          <div class="feature-icon">💻</div>
          <h3>Interactive Coding</h3>
          <p>Write and execute real JavaScript code right in your browser with our built-in playground.</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🎮</div>
          <h3>Interactive Flashcards</h3>
          <p>Master concepts through flashcard to sharpen your knowledge.</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">📚</div>
          <h3>Comprehensive Notes</h3>
          <p>Detailed explanations with examples for every JavaScript concept from beginner to advanced.</p>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🧪</div>
          <h3>Real-world Projects</h3>
          <p>Build practical applications that reinforce your learning and boost your portfolio.</p>
        </div>
      </div>
    </section>

    <!-- Developers Section -->
    <section class="developers">
      <h2>Meet The Developers</h2>
      <div class="developers-grid">
        <div class="developer-card">
          <div class="developer-image">
            <img src="image/developer1.jpg" alt="Muhammad Faqih Hazim">
          </div>
          <div class="developer-info">
            <h3>Muhammad Faqih Hazim</h3>
            <div class="skills">
              <span class="skill-tag">HTML</span>
              <span class="skill-tag">CSS</span>
              <span class="skill-tag">Javascript</span>
            </div>
            <p>Passionate about creating interactive learning experiences that make coding accessible to everyone.</p>
          </div>
        </div>
        
        <div class="developer-card">
          <div class="developer-image">
            <img src="image/developer2.jpg" alt="Muhammad Zill Al Furqan">
          </div>
          <div class="developer-info">
            <h3>Muhammad Zill Al Furqan</h3>
            <div class="skills">
              <span class="skill-tag">HTML</span>
              <span class="skill-tag">CSS</span>
              <span class="skill-tag">Javascript</span>
            </div>
            <p>Design enthusiast focused on creating intuitive interfaces that enhance the learning process.</p>
          </div>
        </div>
        
        <div class="developer-card">
          <div class="developer-image">
            <img src="image/developer3.png" alt="Aqeel Najwan">
          </div>
          <div class="developer-info">
            <h3>Aqeel Najwan</h3>
            <div class="skills">
              <span class="skill-tag">HTML</span>
              <span class="skill-tag">CSS</span>
              <span class="skill-tag">Javascript</span>
            </div>
            <p>Ensures our platform runs smoothly and securely while handling all your coding submissions.</p>
          </div>
        </div>
        
        <div class="developer-card">
          <div class="developer-image">
            <img src="image/developer4.jpg" alt="Tuan Muhammad Rayyan">
          </div>
          <div class="developer-info">
            <h3>Tuan Muhammad Rayyan</h3>
            <div class="skills">
              <span class="skill-tag">HTML</span>
              <span class="skill-tag">CSS</span>
              <span class="skill-tag">Javascript</span>
            </div>
            <p>Creates engaging coding challenges and games that make learning JavaScript fun and rewarding.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="cta">
      <h2>Ready to Start Your JavaScript Journey?</h2>
      <p>Join thousands of learners who've transformed their coding skills with JS Hub</p>
      <button class="cta-btn" onclick="location.href='notes.html'">Start Learning Now →</button>
    </section>
  </main>

  <footer>
    <div class="footer-content">
      <div class="footer-logo">📘 JS Hub</div>
      <div class="footer-links">
        <a href="#">About</a>
        <a href="#">Contact</a>
        <a href="#">Privacy Policy</a>
        <a href="#">Terms</a>
      </div>
      <div class="footer-social">
        <a href="x.com"><img src="image/twitter.svg" alt="Twitter"></a>
        <a href="github.com"><img src="image/github.svg" alt="GitHub"></a>
        <a href="youtube.com"><img src="image/youtube.svg" alt="Youtube"></a>
      </div>
    </div>
    <div class="footer-copyright">
      © 2025 JS Hub. Made with 💙 by Team JavaScript
    </div>
  </footer>

  <!-- Greet Popup -->
  <div id="greet-popup" class="popup-overlay">
    <div class="popup-box">
      <span class="close-btn" onclick="closePopup()">&times;</span>
      <h2>Hello, <span id="user-name">coder</span>!</h2>
      <p>Welcome to JS Hub. Ready to master JavaScript?</p>
      <div class="popup-code">
        <pre><code>// Your first lesson awaits!
function greet() {
  return "Happy coding!";
}</code></pre>
      </div>
      <button class="popup-btn" onclick="closePopup()">Let's Begin!</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
