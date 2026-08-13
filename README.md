
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <meta name="description"
        content="Victor Forex Academy — Learn forex trading, develop real trading skills and become a disciplined trader.">

  <title>Victor Forex Academy</title>

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <!-- ================= HEADER ================= -->

  <header class="navbar">

    <a href="#home" class="logo">
      <span class="logo-circle">V</span>
      <span>VICTOR<span class="logo-red"> FOREX</span></span>
    </a>

    <nav class="desktop-menu">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#academy">Academy</a>
      <a href="#plans">Plans</a>
      <a href="#testimonials">Reviews</a>
      <a href="#contact">Contact</a>
    </nav>

    <button class="menu-button" onclick="toggleMenu()">
      ☰
    </button>

  </header>


  <!-- ================= MOBILE MENU ================= -->

  <div class="mobile-menu" id="mobileMenu">

    <a href="#home" onclick="closeMenu()">Home</a>
    <a href="#about" onclick="closeMenu()">About</a>
    <a href="#academy" onclick="closeMenu()">Academy</a>
    <a href="#plans" onclick="closeMenu()">Plans</a>
    <a href="#testimonials" onclick="closeMenu()">Reviews</a>
    <a href="#contact" onclick="closeMenu()">Contact</a>

  </div>


  <!-- ================= HERO ================= -->

  <section class="hero" id="home">

    <div class="hero-overlay"></div>

    <div class="hero-content">

      <p class="small-heading">VICTOR FOREX ACADEMY</p>

      <h1>
        Learn Forex.
        <strong>Trade With Confidence.</strong>
      </h1>

      <p class="hero-text">
        Master the skills, strategies and discipline needed
        to navigate the forex market with confidence.
      </p>

      <div class="hero-buttons">

        <a href="#plans" class="btn btn-primary">
          Start Learning
          <span>→</span>
        </a>

        <a href="#academy" class="btn btn-outline">
          Explore Academy
          <span>↗</span>
        </a>

      </div>

    </div>

  </section>


  <!-- ================= ABOUT / MENTOR ================= -->

  <section class="about section" id="about">

    <div class="section-title">

      <div class="title-icon">✦</div>

      <div>
        <p class="red-title">MEET YOUR MENTOR</p>

        <h2>
          Learn from someone who
          <strong>understands the market.</strong>
        </h2>
      </div>

    </div>


    <div class="about-grid">

      <div class="mentor-image">

        <!-- Replace mentor.jpg with your own photo -->
        <img src="mentor.jpg" alt="Victor Forex Academy Mentor">

      </div>


      <div class="about-content">

        <p class="mentor-name">
          VICTOR
        </p>

        <h3>
          Your journey to becoming
          a better trader starts here.
        </h3>

        <p>
          Victor Forex Academy was created to give aspiring
          traders practical knowledge, proper market education
          and the mindset required to approach the forex market
          professionally.
        </p>

        <p>
          Whether you are completely new to forex or already
          have trading experience, our goal is to help you
          understand the market, manage risk and develop a
          consistent trading process.
        </p>

        <a href="#academy" class="text-button">
          Learn More About The Academy →
        </a>

      </div>

    </div>

  </section>


  <!-- ================= JOURNEY ================= -->

  <section class="journey section">

    <div class="journey-content">

      <p class="red-title">
        A LITTLE MORE ABOUT OUR JOURNEY
      </p>

      <h2>
        From learning the basics
        to understanding the market.
      </h2>

      <p>
        Forex trading can be confusing when you do not have
        the right guidance. Victor Forex Academy was built to
        simplify the learning process and provide traders with
        a structured path.
      </p>

      <p>
        Instead of chasing unrealistic promises, we focus on
        education, technical analysis, risk management,
        psychology and disciplined execution.
      </p>

      <p>
        Our mission is simple: help traders understand what
        they are doing before they put their money at risk.
      </p>

    </div>

  </section>


  <!-- ================= ACADEMY FEATURES ================= -->

  <section class="academy section" id="academy">

    <div class="center-title">

      <p class="red-title">WHAT WE OFFER</p>

      <h2>
        Everything you need to
        <strong>improve your trading.</strong>
      </h2>

      <p>
        Get access to structured education and practical
        resources designed for traders at different levels.
      </p>

    </div>


    <div class="feature-grid">

      <!-- Feature 1 -->

      <div class="feature-card">

        <div class="feature-icon">📚</div>

        <h3>Forex Education</h3>

        <p>
          Learn forex from the fundamentals to more advanced
          trading concepts through structured lessons.
        </p>

        <a href="#plans">
          Start Learning ↗
        </a>

      </div>


      <!-- Feature 2 -->

      <div class="feature-card">

        <div class="feature-icon">📈</div>

        <h3>Live Trading Sessions</h3>

        <p>
          Follow practical market analysis and learn how
          trading decisions are made in real market conditions.
        </p>

        <a href="#contact">
          Join A Session ↗
        </a>

      </div>


      <!-- Feature 3 -->

      <div class="feature-card">

        <div class="feature-icon">🎯</div>

        <h3>Trading Strategies</h3>

        <p>
          Develop a clear trading plan and understand how to
          identify potential market opportunities.
        </p>

        <a href="#plans">
          Explore Strategies ↗
        </a>

      </div>


      <!-- Feature 4 -->

      <div class="feature-card">

        <div class="feature-icon">🛡️</div>

        <h3>Risk Management</h3>

        <p>
          Understand position sizing, stop losses and the
          importance of protecting your trading capital.
        </p>

        <a href="#plans">
          Learn Risk Management ↗
        </a>

      </div>


      <!-- Feature 5 -->

      <div class="feature-card">

        <div class="feature-icon">🧠</div>

        <h3>Trading Psychology</h3>

        <p>
          Build the discipline and emotional control required
          to follow your trading plan.
        </p>

        <a href="#plans">
          Improve Your Mindset ↗
        </a>

      </div>


      <!-- Feature 6 -->

      <div class="feature-card">

        <div class="feature-icon">🤝</div>

        <h3>Community & Support</h3>

        <p>
          Learn alongside other traders and get guidance as
          you progress through your trading journey.
        </p>

        <a href="#contact">
          Join Community ↗
        </a>

      </div>

    </div>

  </section>


  <!-- ================= PRICING ================= -->

  <section class="plans section" id="plans">

    <div class="center-title">

      <p class="red-title">CHOOSE YOUR PLAN</p>

      <h2>
        Start your trading
        <strong>education today.</strong>
      </h2>

      <p>
        Choose the learning plan that best fits your goals.
      </p>

    </div>


    <div class="pricing-grid">


      <!-- BASIC -->

      <div class="price-card">

        <p class="plan-name">
          BASIC PLAN
        </p>

        <div class="price">
          ₦50,000
        </div>

        <div class="line"></div>

        <h3>
          What you will get...
        </h3>

        <ul>

          <li>✓ Forex fundamentals</li>

          <li>✓ Beginner trading lessons</li>

          <li>✓ Trading psychology</li>

          <li>✓ Risk management</li>

          <li>✓ Private community</li>

        </ul>

        <a href="#contact" class="price-button">
          Choose This Plan →
        </a>

      </div>


      <!-- PREMIUM -->

      <div class="price-card popular">

        <div class="popular-label">
          MOST POPULAR
        </div>

        <p class="plan-name">
          PREMIUM PLAN
        </p>

        <div class="price">
          ₦100,000
        </div>

        <div class="line"></div>

        <h3>
          Everything in Basic, plus...
        </h3>

        <ul>

          <li>✓ Advanced trading education</li>

          <li>✓ Live trading sessions</li>

          <li>✓ Advanced market analysis</li>

          <li>✓ Private mentorship</li>

          <li>✓ Premium community</li>

          <li>✓ Constant support</li>

        </ul>

        <a href="#contact" class="price-button">
          Choose This Plan →
        </a>

      </div>


      <!-- VIP -->

      <div class="price-card">

        <p class="plan-name">
          VIP MENTORSHIP
        </p>

        <div class="price">
          ₦200,000
        </div>

        <div class="line"></div>

        <h3>
          Personalised mentorship...
        </h3>

        <ul>

          <li>✓ One-on-one mentorship</li>

          <li>✓ Personal trading guidance</li>

          <li>✓ Advanced market analysis</li>

          <li>✓ Trading plan development</li>

          <li>✓ Private support</li>

        </ul>

        <a href="#contact" class="price-button">
          Apply Now →
        </a>

      </div>

    </div>

  </section>


  <!-- ================= TESTIMONIALS ================= -->

  <section class="testimonials section" id="testimonials">

    <div class="section-title">

      <div class="title-icon">
        ★★★
      </div>

      <div>

        <p class="red-title">
          STUDENT EXPERIENCES
        </p>

        <h2>
          Hear from our
          <strong>students.</strong>
        </h2>

      </div>

    </div>


    <div class="testimonial-grid">


      <div class="testimonial-card">

        <div class="student">

          <div class="avatar">
            DA
          </div>

          <div>
            <h3>David A.</h3>
            <p>Forex Student</p>
          </div>

        </div>

        <div class="stars">
          ★★★★★
        </div>

        <p>
          “The lessons helped me understand forex much better.
          I finally have a structured approach to studying the
          market instead of entering trades randomly.”
        </p>

      </div>


      <div class="testimonial-card">

        <div class="student">

          <div class="avatar">
            JO
          </div>

          <div>
            <h3>Joseph O.</h3>
            <p>Trader</p>
          </div>

        </div>

        <div class="stars">
          ★★★★★
        </div>

        <p>
          “The emphasis on risk management and psychology has
          completely changed the way I approach trading.”
        </p>

      </div>


      <div class="testimonial-card">

        <div class="student">

          <div class="avatar">
            MK
          </div>

          <div>
            <h3>Michael K.</h3>
            <p>Student</p>
          </div>

        </div>

        <div class="stars">
          ★★★★★
        </div>

        <p>
          “I started with very little knowledge. The academy
          gave me a much clearer understanding of technical
          analysis and trading discipline.”
        </p>

      </div>

    </div>


    <div class="reviews">

      <h2>
        We've got more reviews from our students!
      </h2>

      <p>
        See what other students have to say about
        Victor Forex Academy.
      </p>

      <div class="review-buttons">

        <a href="#" class="review-button">
          ⭐ Trustpilot →
        </a>

        <a href="#" class="review-button">
          🔎 Google Reviews →
        </a>

      </div>

    </div>

  </section>


  <!-- ================= CTA ================= -->

  <section class="cta">

    <div>

      <p class="red-title">
        READY TO START?
      </p>

      <h2>
        Your trading journey
        starts <strong>today.</strong>
      </h2>

      <p>
        Stop guessing. Start learning.
        Build the knowledge and discipline you need
        to approach the forex market professionally.
      </p>

      <a href="#plans" class="btn btn-primary">
        Join Victor Forex Academy →
      </a>

    </div>

  </section>


  <!-- ================= CONTACT ================= -->

  <section class="contact section" id="contact">

    <div class="center-title">

      <p class="red-title">
        GET IN TOUCH
      </p>

      <h2>
        Let's start your
        <strong>trading journey.</strong>
      </h2>

    </div>


    <div class="contact-buttons">

      <!-- CHANGE THESE LINKS TO YOUR REAL LINKS -->

      <a href="https://wa.me/2340000000000"
         class="contact-button whatsapp">
        WhatsApp Us ↗
      </a>

      <a href="#"
         class="contact-button telegram">
        Join Telegram ↗
      </a>

      <a href="mailto:your@email.com"
         class="contact-button email">
        Send Email ↗
      </a>

    </div>

  </section>


  <!-- ================= FOOTER ================= -->

  <footer>

    <div class="footer-logo">
      <span class="logo-circle">V</span>
      VICTOR FOREX ACADEMY
    </div>

    <p>
      Education. Discipline. Strategy.
    </p>

    <div class="footer-links">

      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#academy">Academy</a>
      <a href="#plans">Plans</a>
      <a href="#contact">Contact</a>

    </div>

    <p class="copyright">
      © 2026 Victor Forex Academy. All rights reserved.
    </p>

  </footer>


  <!-- ================= FLOATING WHATSAPP ================= -->

  <a href="https://wa.me/2340000000000"
     class="whatsapp-float"
     aria-label="Chat on WhatsApp">
    ☎
  </a>


  <script src="script.js"></script>

</body>
</html>
