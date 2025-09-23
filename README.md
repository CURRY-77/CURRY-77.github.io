<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Club Management - Pitch</title>
<style>
  /* Reset and base */
  * {
    box-sizing: border-box;
    margin: 0; padding: 0;
  }
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background-color: #f9fafb;
    color: #333;
  }
  header {
    background-color: #0052cc;
    color: white;
    padding: 1.5rem 2rem;
    text-align: center;
  }
  header h1 {
    font-weight: 700;
    font-size: 2rem;
    letter-spacing: 2px;
  }

  main {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1.2rem;
  }
  section {
    background: white;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgb(0 0 0 / 0.1);
    margin-bottom: 2rem;
    padding: 1.8rem 2rem;
  }
  h2 {
    color: #0052cc;
    font-size: 1.6rem;
    margin-bottom: 1rem;
    border-bottom: 2px solid #0052cc;
    padding-bottom: 0.3rem;
  }
  h3 {
    margin-top: 1.2rem;
    margin-bottom: 0.6rem;
    color: #222;
  }
  ul {
    margin-left: 1.2rem;
    list-style: disc inside;
    margin-bottom: 1rem;
  }
  ul li {
    margin-bottom: 0.5rem;
  }
  p {
    margin-bottom: 1rem;
  }
  strong {
    color: #003a99;
  }
  footer {
    text-align: center;
    padding: 1rem 2rem;
    color: #666;
    font-size: 0.9rem;
  }
  /* Responsive for mobile */
  @media (max-width: 600px) {
    main {
      margin: 1rem;
      padding: 0 1rem;
    }
    header h1 {
      font-size: 1.5rem;
    }
  }
</style>
</head>

<body>
<header>
  <h1>CLUB MANAGEMENT</h1>
</header>

<main>
  <section id="why">
    <h2>Why?</h2>
    <h3>1. The Feed Page</h3>
    <ul>
      <li>Students are not notified about college events.</li>
      <li>A feed page will post all upcoming events.</li>
      <li>Posts are managed by Admin, President, and Vice President roles with defined rules.</li>
    </ul>

    <h3>2. The Clubs Page</h3>
    <ul>
      <li>Students don’t know the types and number of clubs available.</li>
      <li>They can browse and apply to clubs (max 4 simultaneously to reduce request traffic).</li>
      <li>Applications are accessible by the club's President and Vice President.</li>
    </ul>

    <h3>3. The My Clubs Page</h3>
    <ul>
      <li>Shows clubs a student has joined once applications are accepted.</li>
      <li>Users gain eligibility to apply for leaves related to events through this page.</li>
    </ul>

    <h3>4. The Hackathons Page</h3>
    <ul>
      <li>Students are often unaware of upcoming hackathons or struggle to find teams.</li>
      <li>Hackathon posts and team-finding posts managed by Staff or technical clubs.</li>
      <li>A “Find a Team” subsection allows students to find or form teams with specific requirements.</li>
    </ul>

    <h3>5. Settings Page</h3>
    <ul>
      <li>Displays user details: Name, Semester, ERP ID, Department/Branch, clubs, and roles.</li>
    </ul>
  </section>

  <section id="what">
    <h2>What?</h2>
    <h3>1. Login / Sign Up</h3>
    <ul>
      <li><strong>Old User:</strong> Credentials checked against the database; access granted if authorized.</li>
      <li><strong>New User:</strong> Registration requires college email verification via OTP, then profile info saved to SQL database.</li>
    </ul>

    <h3>2. Feed Page</h3>
    <ul>
      <li>Posts by Admin/President/Vice President visible to all logged-in users.</li>
      <li>Posts include captions, photos, and optional external links.</li>
      <li>Users can like posts and share direct links (no embedding).</li>
    </ul>

    <h3>3. Clubs Page</h3>
    <ul>
      <li>Visible to everyone; displays clubs by category with descriptions.</li>
      <li>Logged-in users can apply with their details and motivation (max 4 applications at a time).</li>
    </ul>

    <h3>4. My Clubs</h3>
    <ul>
      <li>Shows clubs joined and member lists.</li>
      <li>Users can apply for event-related leave (submits event name and role).</li>
      <li>Leave requests processed by P/VP, then Admin; notifications sent to respective HOD/coordinator.</li>
      <li>Users can request to leave clubs with a reason; acceptance leads to removal and notification.</li>
    </ul>

    <h3>5. Settings</h3>
    <ul>
      <li>Displays user profile details including clubs joined and roles held.</li>
    </ul>
  </section>
</main>

<footer>
  &copy; 2025 Club Management Pitch | Designed for Clear Communication
</footer>
</body>
</html>
