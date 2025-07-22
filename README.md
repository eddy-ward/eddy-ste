<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Study Coding and Web Development with Eddy</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      color: #333;
      text-align: center;
      scroll-behavior: smooth;
    }
    header {
      background: linear-gradient(45deg, #4CAF50, #2196F3);
      color: white;
      padding: 30px 10px;
      animation: fadeIn 1.5s ease-in-out;
    }
    .container {
      max-width: 960px;
      margin: auto;
      padding: 20px;
    }
    h1, h2, h3 {
      margin-bottom: 10px;
    }
    ul {
      list-style: none;
      padding: 0;
    }

    .btn {
      background-color: #4CAF50;
      color: white;
      padding: 10px 25px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin: 15px 0;
      transition: background-color 0.3s ease;
    }
    .btn:hover {
      background-color: #388e3c;
    }

    .section {
      background: white;
      border-radius: 10px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 0 10px #ccc;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeSlideUp 0.8s forwards;
    }

    .section:nth-child(2) { animation-delay: 0.2s; }
    .section:nth-child(3) { animation-delay: 0.4s; }
    .section:nth-child(4) { animation-delay: 0.6s; }
    .section:nth-child(5) { animation-delay: 0.8s; }
    .section:nth-child(6) { animation-delay: 1s; }
    .section:nth-child(7) { animation-delay: 1.2s; }

    .packages {
      display: flex;
      flex-direction: column;
    }
    .packages .card {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      margin: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .packages .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    }

    .testimonial {
      font-style: italic;
      margin-bottom: 10px;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
      transition: border-color 0.3s ease;
    }
    form input:focus, form textarea:focus {
      border-color: #4CAF50;
      outline: none;
    }

    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }

    @media (min-width: 600px) {
      .packages {
        flex-direction: row;
        justify-content: space-between;
      }
      .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
    }

    @keyframes fadeSlideUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

<header>
  <h1>Study Coding & Web Development with Eddy</h1>
  <p>Boost your tech skills and become job-ready!</p>
  <a href="https://wa.me/256765658578" target="_blank"><button class="btn">💬 Chat on WhatsApp</button></a>
</header>

<div class="container">

  <div class="section">
    <h2>📘 What You'll Learn</h2>
    <ul>
      <li>✔️ HTML, CSS, JavaScript</li>
      <li>✔️ Web design and mobile-first development</li>
      <li>✔️ Project-based learning & problem solving</li>
    </ul>
  </div>

  <div class="section packages">
    <div class="card">
      <h3>Beginner</h3>
      <p>Intro to web development<br>HTML + CSS basics</p>
      <strong>UGX 50,000</strong>
    </div>
    <div class="card">
      <h3>Intermediate</h3>
      <p>JavaScript, projects, layout design</p>
      <strong>UGX 100,000</strong>
    </div>
    <div class="card">
      <h3>Advanced</h3>
      <p>Portfolio, hosting, freelancing tips</p>
      <strong>UGX 150,000</strong>
    </div>
  </div>

  <div class="section">
    <h2>🎬 Video Preview</h2>
    <iframe width="100%" height="200" src="https://www.youtube.com/embed/Ke90Tje7VS0" allowfullscreen></iframe>
  </div>

  <div class="section gallery">
    <h2>📸 Sample Projects</h2>
    <img src="https://via.placeholder.com/300x200?text=Project+1" alt="project">
    <img src="https://via.placeholder.com/300x200?text=Project+2" alt="project">
  </div>

  <div class="section">
    <h2>🙋 Frequently Asked Questions (FAQs)</h2>
    <p><strong>Q:</strong> Do I need a laptop?<br><strong>A:</strong> A smartphone is enough to start.</p>
    <p><strong>Q:</strong> Are classes live or recorded?<br><strong>A:</strong> Both are available.</p>
    <p><strong>Q:</strong> How do I pay?<br><strong>A:</strong> Mobile Money or cash.</p>
  </div>

  <div class="section">
    <h2>🌟 Testimonials</h2>
    <p class="testimonial">“Eddy helped me land my first freelance job!” – Brian K.</p>
    <p class="testimonial">“I learned faster than in school. Best mentor!” – Sarah M.</p>
  </div>

  <div class="section">
    <h2>📩 Contact Me</h2>
    <form action="https://formspree.io/f/YOUR-FORM-ID" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="_replyto" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button class="btn" type="submit">Send Message</button>
    </form>
    <p>or <a href="https://wa.me/256765658578" target="_blank">Message me on WhatsApp</a></p>
  </div>

</div>

</body>
</html>
<div class="section gallery">
  <h2>📸 Sample Projects</h2>
  <img src="https://images.unsplash.com/photo-1598257006458-54f7240c2b6d?auto=format&fit=crop&w=600&q=80" alt="Student Coding">
  <img src="https://images.unsplash.com/photo-1581093588401-88b26f41d0d2?auto=format&fit=crop&w=600&q=80" alt="Laptop with Code">
  <img src="https://images.unsplash.com/photo-1612902372482-f2e4aa5d7622?auto=format&fit=crop&w=600&q=80" alt="People in Coding Class">
</div>
