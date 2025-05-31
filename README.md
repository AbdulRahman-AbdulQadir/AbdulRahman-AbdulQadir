<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AbdulRahman’s Profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 2rem;
      text-align: center;
    }

    h1 {
      color: #61DAFB;
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    /* 1) Floating (up/down) animation for the name */
    .moving-text {
      display: inline-block;
      animation: float 3s ease-in-out infinite alternate;
      transition: transform 0.3s ease-in-out;
    }

    @keyframes float {
      from { transform: translateY(0px); }
      to   { transform: translateY(-10px); }
    }

    /* 2) Zoom-on-hover */
    .moving-text:hover {
      animation: none;          /* stop floating while hovered */
      transform: scale(1.2);    /* grow to 120% of original size */
    }

    p.subtitle {
      font-size: 1.2rem;
      margin: 0;
    }

    /* 3) Skills container: each badge as its own “box” */
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 0.5rem;
      margin-top: 2rem;
    }
    .skills img {
      width: auto;
      height: 40px;
      transition: transform 0.2s ease-in-out;
      cursor: pointer;
    }
    .skills img:hover {
      transform: scale(1.1);  /* zoom each badge on hover */
    }

    /* 4) Featured Projects styling */
    .project {
      margin: 1.5rem auto;
      max-width: 600px;
      background: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1.5rem;
      text-align: left;
      transition: transform 0.2s ease-in-out;
    }
    .project:hover {
      transform: translateY(-5px);
    }
    .project h3 {
      margin: 0 0 0.5rem;
      font-size: 1.5rem;
      color: #333;
    }
    .project p {
      margin: 0.25rem 0;
      color: #555;
    }
    .project a {
      color: #1d74e5;
      text-decoration: none;
      font-weight: bold;
    }
    .project a:hover {
      text-decoration: underline;
    }

    /* 5) Footer / Connect */
    .connect a img {
      height: 35px;
      margin: 0 0.5rem;
      transition: transform 0.2s ease-in-out;
    }
    .connect a img:hover {
      transform: scale(1.15);
    }
  </style>
</head>
<body>

  <div>
    <!-- Animated name + subtitle -->
    <h1>Hello, I’m <span class="moving-text">AbdulRahman</span></h1>
    <p class="subtitle">🧑‍💻 Django Backend Developer | 🚀 Freelance Aspirant | 📚 Always Learning</p>
  </div>

  <!-- Skills badges: each one zooms on hover -->
  <div class="skills">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
    <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/REST_API-000000?style=for-the-badge&logo=rest&logoColor=white" alt="REST API" />
    <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white" alt="JWT" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  </div>

  <!-- Featured Projects -->
  <div class="project">
    <h3><a href="https://github.com/<your-username>/django-blog-api">Django Blog API</a></h3>
    <p>A RESTful blog API built with Django REST Framework. Features JWT authentication, CRUD endpoints, pagination, and PostgreSQL integration.</p>
  </div>

  <div class="project">
    <h3><a href="https://github.com/<your-username>/invoice-manager">Invoice Manager</a></h3>
    <p>A Django app to manage freelance invoices and clients. Includes user auth (Django Allauth), PDF invoice generation (ReportLab), and MySQL.</p>
  </div>

  <div class="project">
    <h3><a href="https://github.com/<your-username>/ecommerce-backend">E-commerce Backend</a></h3>
    <p>Backend for an e-commerce site using Django and Stripe. Implements product catalog, shopping cart, orders, and payment integration.</p>
  </div>

  <!-- Footer / Connect -->
  <div class="connect" style="margin-top: 2rem;">
    <a href="mailto:your.email@example.com">
      <img src="https://img.shields.io/badge/Email-your.email%40example.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://linkedin.com/in/<your-linkedin>">
      <img src="https://img.shields.io/badge/LinkedIn-<your-linkedin>-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://twitter.com/<your-twitter-handle>">
      <img src="https://img.shields.io/badge/Twitter-@<your-twitter-handle>-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
    </a>
    <a href="https://github.com/<your-username>">
      <img src="https://img.shields.io/badge/GitHub-<your-username>-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </div>

  <p style="margin-top: 2rem; color: #888;">Made with ❤️ using 🐍 Python & 🌐 Django</p>
</body>
</html>
