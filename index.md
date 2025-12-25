---
layout: default
---

<style>
  /* 1. OVERRIDE THEME CONSTRAINTS (FULL WIDTH) */
  .wrapper, .container, section, body {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  header { display: none !important; } /* Hide default Jekyll sidebar */

  /* 2. TYPOGRAPHY: GEORGIA & COLORS */
  body {
    font-family: 'Georgia', serif;
    color: #333;
    background-color: #fff;
    font-size: 1.05rem;
    line-height: 1.6;
  }

  /* Specifically targeting headers and navigation with Georgia */
  h1, h2, h3, .nav-link, .site-title {
    font-family: 'Georgia', serif;
    color: #2e7cc7; /* Academic Blue */
  }

  h1 { color: #333; } /* Name remains black for contrast */

  h2 {
    border-bottom: 1.2px solid #2e7cc7;
    padding-bottom: 5px;
    margin-top: 40px;
    font-weight: normal;
    font-size: 1.5rem;
  }

  /* 3. SIDEBAR STYLING (TEXT ONLY) */
  .sidebar {
    width: 160px;
    flex-shrink: 0;
    padding: 40px 20px;
    position: sticky;
    top: 0;
  }

  .nav-link {
    display: block;
    padding: 6px 0;
    text-decoration: none;
    font-size: 1.05rem;
  }
  .nav-link:hover { text-decoration: underline; }

  /* 4. MAIN CONTENT AREA */
  .content-area {
    flex-grow: 1;
    padding: 40px 60px;
    max-width: 1200px;
  }

  .profile-header {
    display: flex;
    align-items: flex-start;
    margin-bottom: 30px;
  }
</style>

<div style="display: flex;">

  <div class="sidebar">
    <div class="site-title" style="font-weight: bold; font-size: 1.2rem; margin-bottom: 20px;">Ray</div>
    <nav>
      <a class="nav-link" href="/">Home</a>
      <a class="nav-link" href="#about">About</a>
      <a class="nav-link" href="#research">Research</a>
      <a class="nav-link" href="#publications">Publications</a>
      <a class="nav-link" href="/cv.pdf">CV</a>
    </nav>
  </div>

  <div class="content-area">
    
    <div class="profile-header">
      <img src="profile.jpg" style="width: 200px; margin-right: 35px; border: 1px solid #ddd;">
      <div>
        <h1 style="margin: 0; font-size: 2.2rem; font-weight: normal;">Ray</h1>
        <p style="margin-top: 15px;">
          PhD Student<br>
          University Name<br>
          Email: <a href="mailto:your@email.edu" style="color: #2e7cc7; text-decoration: none;">your@email.edu</a>
        </p>
      </div>
    </div>

    <h2 id="about">About</h2>
    <p>I am a PhD student at <strong>University Name</strong>. My research focuses on...</p>

    <h2 id="research">Research</h2>
    <p>My current research interests include...</p>

    <h2 id="publications">Publications</h2>
    <p><strong>Ray</strong>, "Sample Paper Title," 2025.</p>

  </div>
</div>
