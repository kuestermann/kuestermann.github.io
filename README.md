# kuestermann.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Big Data Portfolio - Konstantin Küstermann</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #1f2937;
      --accent: #3b82f6;
      --background: #f9fafb;
      --text: #111827;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--background);
      color: var(--text);
      line-height: 1.6;
      padding: 20px;
    }
    header {
      background-color: var(--primary);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    nav a {
      margin: 0 15px;
      color: #cbd5e1;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover {
      color: white;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    h2 {
      margin-bottom: 15px;
      color: var(--accent);
    }
    ul {
      list-style: disc;
      margin-left: 20px;
    }
    footer {
      text-align: center;
      margin-top: 60px;
      color: #6b7280;
      font-size: 0.9rem;
    }
    a.button {
      display: inline-block;
      margin-top: 10px;
      background: var(--accent);
      color: white;
      padding: 10px 16px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }
    a.button:hover {
      background-color: #2563eb;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Konstantin Küstermann</h1>
    <p>Big Data Student | Python • Spark • SQL • ML</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#tools">Tools</a>
      <a href="#resume">Resume</a>
    </nav>
  </header>
  <section id="about">
    <h2>About Me</h2>
    <p>I'm an industrial engineer and aspiring Big Data architect. I specialize in scalable data solutions using Spark, Python, and cloud platforms. I’m passionate about turning raw data into actionable insights and building automation that accelerates the energy transition.</p>
  </section>
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Programming: Python, SQL, Java</li>
      <li>Data Engineering: Apache Spark, Kafka, Hadoop</li>
      <li>Analytics: Pandas, NumPy, Jupyter</li>
      <li>Machine Learning: scikit-learn, TensorFlow (Basics)</li>
    </ul>
  </section>
  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>IAB Investment Calculator</strong> – Built an interactive tool to calculate optimal tax-optimized investment volumes based on §7g EStG.</li>
      <li><strong>Retail Sales Dashboard</strong> – Created an end-to-end pipeline using PySpark and visualized results in Power BI.</li>
      <li><strong>Real-Time Sentiment Analysis</strong> – Streamed tweets via Kafka and analyzed them with Spark Streaming.</li>
    </ul>
  </section>
  <section id="tools">
    <h2>Tools & Platforms</h2>
    <ul>
      <li>Apache Spark, Hadoop, Hive</li>
      <li>Docker, Git, VS Code</li>
      <li>AWS S3, Google BigQuery, Databricks</li>
    </ul>
  </section>
  <section id="resume">
    <h2>Resume</h2>
    <p>You can view or download my resume below:</p>
    <a href="resume.pdf" class="button" target="_blank">Download Resume</a>
  </section>
  <footer>
    <p>© 2025 Konstantin Küstermann | Built with GitHub Pages</p>
  </footer>
</body>
</html>
