## Hi there 👋


<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mrigesh Koyande - Portfolio</title>
  <style>
    /* Base Styles */
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #89f7fe, #66a6ff);
      margin: 0;
      padding: 0;
      color: #333;
    }

    .header {
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(15px);
      -webkit-backdrop-filter: blur(15px);
      color: white;
      padding: 20px;
      text-align: center;
      border-radius: 20px;
      margin: 20px auto;
      width: 90%;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    }

    .header button {
      margin-top: 10px;
      padding: 8px 15px;
      background-color: rgba(255, 255, 255, 0.3);
      color: #fff;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      backdrop-filter: blur(10px);
      transition: 0.3s;
    }

    .header button:hover {
      background: rgba(255, 255, 255, 0.5);
    }

    .content {
      padding: 20px;
      max-width: 1000px;
      margin: 20px auto;
      border-radius: 20px;
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(15px);
      -webkit-backdrop-filter: blur(15px);
      box-shadow: 0 8px 25px rgba(0,0,0,0.25);
      color: #fff;
    }

    .section-title {
      color: #90ee90;
      margin-bottom: 10px;
      font-size: 1.5em;
      text-shadow: 0 0 5px rgba(0,0,0,0.3);
    }

    .skills, .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .skills div, .contact div {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      padding: 15px;
      border-radius: 15px;
      flex: 1;
      min-width: 200px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      color: #fff;
    }

    .links a {
      display: inline-block;
      margin: 10px 15px 10px 0;
      color: #90ee90;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .links a:hover {
      color: #fff;
      text-shadow: 0 0 5px #90ee90;
    }

    .certifications ul {
      list-style-type: none;
      padding: 0;
    }

    .certifications li {
      margin: 10px 0;
    }

    .footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #fff;
      background: rgba(0,0,0,0.3);
      margin-top: 20px;
      border-radius: 15px;
      width: 90%;
      margin-left: auto;
      margin-right: auto;
    }

    /* Dark Mode */
    body.dark {
      background: linear-gradient(135deg, #1f1c2c, #928dab);
      color: #f0f0f0;
    }

    body.dark .content {
      background: rgba(0,0,0,0.3);
    }

    body.dark .skills div,
    body.dark .contact div {
      background: rgba(0,0,0,0.4);
    }

    body.dark .links a {
      color: #66ff99;
    }

    body.dark .header {
      background: rgba(0,0,0,0.4);
    }

    body.dark .footer {
      background: rgba(255,255,255,0.1);
      color: #ccc;
    }

    /* Responsive Design */
    @media (max-width: 600px) {
      .skills, .contact {
        flex-direction: column;
      }

      .links a {
        display: block;
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>
  <header class="header">
    <h1>Mrigesh Koyande</h1>
    <p>Gaming Content Creator | Free Fire Max Enthusiast | Android Developer | AI & ML Specialist | Data Analyst</p>
    <button onclick="toggleDarkMode()">Toggle Dark Mode</button>
  </header>

  <main class="content">
    <section>
      <h2 class="section-title">About Me</h2>
      <p>I am Mrigesh Koyande, an Indian gaming content creator passionate about Free Fire Max. My YouTube channel showcases intense gameplay, strategic plays, and live interaction with my audience. With over 1,200 videos, I have built a community of enthusiastic gamers and followers. In addition, I am pursuing Android development, AI & ML certifications, and work as a data analyst.</p>
    </section>

    <section>
      <h2 class="section-title">Skills</h2>
      <div class="skills">
        <div><strong>Game Strategy:</strong> Advanced Free Fire strategies and tips.</div>
        <div><strong>Clutch Plays:</strong> Specializing in 1v4 and intense clutch moments.</div>
        <div><strong>Streaming:</strong> Live streaming on YouTube with high engagement.</div>
        <div><strong>Android Development:</strong> Building mobile apps using Kotlin & Java.</div>
        <div><strong>AI & ML:</strong> Certified in Machine Learning & AI Algorithms.</div>
        <div><strong>Data Analysis:</strong> Working with tools like Python, Excel, and SQL.</div>
      </div>
    </section>

    <section class="certifications">
      <h2 class="section-title">Certifications</h2>
      <ul>
        <li><strong>Android Development:</strong> Courses in app design, UI, and backend integration.</li>
        <li><strong>AI & ML Certification:</strong> Projects in TensorFlow and scikit-learn.</li>
        <li><strong>Data Analyst Certification:</strong> Specialized in Python, SQL, and real-world datasets.</li>
      </ul>
    </section>

    <section>
      <h2 class="section-title">Connect With Me</h2>
      <div class="links">
        <a href="https://www.youtube.com/channel/UCEPou_Of0PlXjsFY2h8km4g" target="_blank">YouTube Channel</a>
        <a href="https://www.instagram.com/mrigeshkoyande/" target="_blank">Instagram Profile</a>
        <a href="https://in.linkedin.com/in/mrigesh-koyande-783309315" target="_blank">LinkedIn Profile</a>
      </div>
    </section>

    <section>
      <h2 class="section-title">Contact</h2>
      <div class="contact">
        <div>Email: <a href="mailto:mrigeshkoyande@gmail.com">mrigesh.koyande@example.com</a></div>
        <div>Phone: +91 93729 25324</div>
        <div>Location: Mumbai, India</div>
      </div>
    </section>
  </main>

  <footer class="footer">
    &copy; 2025 Mrigesh Koyande | All Rights Reserved
  </footer>

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle("dark");
    }
  </script>
>
