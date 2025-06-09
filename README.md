<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Raja Typing Institute</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #f0f4f8;
      color: #333;
    }

    header {
      background: #0066cc;
      color: white;
      padding: 20px 40px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 500;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 50px 40px;
      background: linear-gradient(to right, #e6f0ff, #ffffff);
    }

    .hero-text {
      max-width: 600px;
    }

    .hero-text h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #003366;
    }

    .hero-text p {
      font-size: 1.1rem;
      margin-bottom: 30px;
    }

    .hero-text button {
      padding: 10px 20px;
      background: #0066cc;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }

    .features {
      padding: 60px 40px;
      background: #fff;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .feature {
      background: #f9fafc;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
      text-align: center;
    }

    .feature h3 {
      color: #003366;
      margin-bottom: 10px;
    }

    .contact {
      padding: 40px;
      background: #e6f0ff;
      text-align: center;
    }

    .contact h2 {
      margin-bottom: 20px;
    }

    footer {
      background: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>

<body>
  <header>
    <h1>Raja Typing Institute</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#courses">Courses</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>Learn Typing the Smart Way</h1>
      <p>Join Raja Typing Institute and boost your career with top-class typing skills. We offer beginner to advanced level training with government-certified exams.</p>
      <button>Join Now</button>
    </div>
    <img src="https://img.icons8.com/ios-filled/500/keyboard.png" alt="Typing" width="300">
  </section>

  <section class="features" id="courses">
    <div class="feature">
      <h3>Basic & Advanced Typing</h3>
      <p>Learn both English and Tamil typing skills for personal and competitive use.</p>
    </div>
    <div class="feature">
      <h3>Govt Exam Preparation</h3>
      <p>Special training for students aiming for TNPSC and other competitive exams.</p>
    </div>
    <div class="feature">
      <h3>Flexible Timings</h3>
      <p>Attend classes at your convenience — morning, evening, or weekends.</p>
    </div>
    <div class="feature">
      <h3>Free for Toppers</h3>
      <p>Scored 450+ in 10th or 530+ in 12th? Learn typing free — pay only for exam fees.</p>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>📍 Marakadai, Koothanallur, Tamil Nadu</p>
    <p>📞 +91 98765 43210</p>
    <p>📧 rajatypinginstitute@email.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Raja Typing Institute. All rights reserved.</p>
  </footer>
</body>

</html>
