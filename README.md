## Hi there 👋
![luffy](https://github.com/user-attachments/assets/a5f3877e-a1ce-4dac-83d9-baccf9fc8472)

<!--
**suresurya/suresurya** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>S S V R Surya | Java Developer</title>

  <!-- Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: #000;
      color: #eaeaea;
    }

    /* ---------- NAVBAR ---------- */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    .nav-left {
      display: flex;
      align-items: center;
      gap: 15px;
    }

    .nav-left img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
    }

    .nav-links a {
      color: #ccc;
      text-decoration: none;
      margin: 0 12px;
      font-size: 15px;
    }

    .nav-links a:hover {
      color: #fff;
    }

    .nav-right i {
      color: #ccc;
      margin-left: 18px;
      font-size: 18px;
      cursor: pointer;
    }

    .nav-right i:hover {
      color: #fff;
    }

    /* ---------- HERO ---------- */
    .hero {
      display: flex;
      align-items: center;
      min-height: calc(100vh - 80px);
      padding: 0 60px;
    }

    .hero-content {
      max-width: 850px;
    }

    .avatar-wrapper {
      position: relative;
      width: 130px;
      margin-bottom: 30px;
    }

    .avatar-wrapper img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 2px solid #1f1f1f;
    }

    .online-dot {
      position: absolute;
      bottom: 12px;
      right: 12px;
      width: 12px;
      height: 12px;
      background: #00ff5a;
      border-radius: 50%;
      border: 2px solid #000;
    }

    h1 {
      font-size: 42px;
      font-weight: 600;
      margin-bottom: 25px;
    }

    h1 span {
      color: #8ab4f8;
    }

    .description {
      color: #bdbdbd;
      font-size: 16px;
      line-height: 1.7;
      max-width: 780px;
    }

    /* ---------- BUTTONS ---------- */
    .buttons {
      margin-top: 35px;
      display: flex;
      gap: 18px;
    }

    .btn {
      padding: 12px 22px;
      border-radius: 10px;
      font-size: 14px;
      cursor: pointer;
      background: transparent;
      color: #eaeaea;
      border: 1px dashed #555;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      transition: all 0.3s ease;
    }

    .btn:hover {
      background: #111;
      border-color: #888;
    }

    /* ---------- RESPONSIVE ---------- */
    @media (max-width: 768px) {
      .navbar {
        padding: 20px;
      }

      .hero {
        padding: 0 20px;
      }

      h1 {
        font-size: 32px;
      }
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav class="navbar">
    <div class="nav-left">
      <img src="image.png" alt="Profile">
      <div class="nav-links">
        <a href="#">Work</a>
        <a href="#">Projects</a>
        <a href="#">Resume</a>
      </div>
    </div>

    <div class="nav-right">
      <i class="fab fa-github"></i>
      <i class="fab fa-linkedin"></i>
      <i class="fas fa-sun"></i>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-content">

      <div class="avatar-wrapper">
        <img src="<img width="2048" height="2048" alt="pfp" src="https://github.com/user-attachments/assets/5f5f41da-cb94-4480-98a4-c8630b416447" />" alt="Avatar">
        <div class="online-dot"></div>
      </div>

      <h1>
        Hi, I am <span>S.S V R SURYA</span> -- A Java Dev.
      </h1>

      <p class="description">
        I am Sure Sri Venak Rama Surya, a B.Tech CSE (3rd Year) student at
        Vignan Foundation for Science & Technology. I am a JAVA DEVELOPER (Fresher)
        with strong fundamentals in Core Java and hands-on experience in Spring Boot,
        REST APIs, MySQL, JDBC, and Hibernate. I have built multiple database-driven
        Java applications and am seeking internship opportunities to gain real-world
        industry experience.
      </p>

      <div class="buttons">
        <button class="btn">
          <i class="fas fa-file"></i> My Resume
        </button>

        <button class="btn">
          <i class="fas fa-paper-plane"></i> Contact Me
        </button>
      </div>

    </div>
  </section>

</body>
</html>
