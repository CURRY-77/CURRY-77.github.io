<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    :root {
      --color-background: var(--color-cream-50);
      --color-surface: var(--color-cream-100);
      --color-text: var(--color-slate-900);
      --color-text-secondary: var(--color-slate-500);
      --color-primary: var(--color-teal-500);
      --color-primary-hover: var(--color-teal-600);
      --color-border: rgba(94,82,64,0.2);
      --font-family-base: "FKGroteskNeue", "Geist", "Inter", -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,sans-serif;
      --font-weight-bold: 600;
      --radius-base: 8px;
      --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.04),0 2px 4px -1px rgba(0, 0, 0, 0.02);
    }
    body {
      font-family: var(--font-family-base);
      background: var(--color-background);
      color: var(--color-text);
      margin: 0;
      padding: 0;
    }
    .portfolio-container {
      max-width: 680px;
      margin: 40px auto;
      background: var(--color-surface);
      border-radius: var(--radius-base);
      box-shadow: var(--shadow-md);
      padding: 32px 28px;
      border: 1px solid var(--color-border);
    }
    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    header h1 {
      font-size: 2.2rem;
      font-weight: var(--font-weight-bold);
      margin-bottom: 6px;
      letter-spacing: -1px;
    }
    header p {
      color: var(--color-text-secondary);
      font-size: 1.1rem;
      margin-top: 0;
    }
    section {
      margin-bottom: 2.2rem;
    }
    section:last-child {
      margin-bottom: 0;
    }
    .skills-list, .projects-list {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      list-style: none;
      padding: 0;
    }
    .skills-list li, .project-card {
      background: #e9f6f7;
      color: var(--color-primary-hover);
      border-radius: var(--radius-base);
      padding: 7px 16px;
      font-size: 1rem;
      margin: 0;
      border: 1px solid var(--color-border);
    }
    .project-card {
      display: block;
      min-width: 170px;
      max-width: 320px;
      margin-bottom: 7px;
      background: #f5fffe;
      color: var(--color-text);
      border-radius: var(--radius-base);
      box-shadow: 0 2px 6px 0 rgba(33,128,141,0.08);
      border-left: 5px solid var(--color-primary);
    }
    .project-card-title {
      font-weight: 600;
      margin-bottom: 0;
      letter-spacing: -0.5px;
    }
    .project-card-desc {
      color: var(--color-text-secondary);
      font-size: 0.98rem;
      margin-bottom: 5px;
    }
    .contact-list {
      list-style-type: none;
      padding-left: 10px;
      font-size: 1.02rem;
    }
    .contact-list li {
      margin-bottom: 7px;
    }
    .contact-link {
      color: var(--color-primary);
      text-decoration: none;
      font-weight: 500;
      transition: color 0.2s;
    }
    .contact-link:hover, .contact-link:focus-visible {
      color: var(--color-primary-hover);
      text-decoration: underline;
      outline: none;
    }
    @media (max-width: 700px) {
      .portfolio-container {
        margin: 12px;
        padding: 20px;
      }
      header h1 {
        font-size: 1.28rem;
      }
    }
  </style>
</head>
<body>
  <div class="portfolio-container">
    <header>
      <h1>Rahul Sharma</h1>
      <p>Software Developer | Python, Java, Web Apps</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>
        I am a software developer specializing in Python (Django), Java, and modern web technologies. Experienced in building secure web apps, backend APIs, and deploying cloud solutions. I love exploring new frameworks and elegant code.
      </p>
    </section>

    <section>
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>Python</li>
        <li>Django</li>
        <li>FastAPI</li>
        <li>Java</li>
        <li>PostgreSQL</li>
        <li>MongoDB</li>
        <li>HTML/CSS</li>
        <li>JavaScript</li>
        <li>AWS EC2/S3</li>
        <li>Socket Programming</li>
        <li>Security (OAuth2, SSO, OTP)</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>
      <div class="projects-list">
        <div class="project-card">
          <p class="project-card-title">Django Cloud Portal</p>
          <p class="project-card-desc">
            Full-stack web app for student communities, featuring login with OTP email, AWS S3 file storage, PostgreSQL backend, and secure OAuth2-based authentication.
          </p>
          <a class="contact-link" href="https://github.com/yourprofile/django-cloud-portal" target="_blank" rel="noopener noreferrer">View on GitHub</a>
        </div>
        <div class="project-card">
          <p class="project-card-title">Java Socket Comm</p>
          <p class="project-card-desc">
            Two-way client/server Java socket communication library, ideal for learning, demo projects, or classroom coding labs.
          </p>
          <a class="contact-link" href="https://github.com/yourprofile/java-socket-comm" target="_blank" rel="noopener noreferrer">View on GitHub</a>
        </div>
        <div class="project-card">
          <p class="project-card-title">PC Builder Guide</p>
          <p class="project-card-desc">
            Interactive web tool recommending PC components for Indian markets, with real-time price filtering and configuration features (Python/Flask).
          </p>
          <a class="contact-link" href="https://github.com/yourprofile/pc-builder-guide" target="_blank" rel="noopener noreferrer">View on GitHub</a>
        </div>
      </div>
    </section>

    <section>
      <h2>Contact</h2>
      <ul class="contact-list">
        <li>Email: <a class="contact-link" href="mailto:rahul.sharma@email.com">rahul.sharma@email.com</a></li>
        <li>GitHub: <a class="contact-link" href="https://github.com/yourprofile" target="_blank" rel="noopener noreferrer">github.com/yourprofile</a></li>
        <li>LinkedIn: <a class="contact-link" href="https://linkedin.com/in/rahul-sharma" target="_blank" rel="noopener noreferrer">linkedin.com/in/rahul-sharma</a></li>
      </ul>
    </section>
  </div>
</body>
</html>
