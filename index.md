---
layout: default
---

<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,700;1,400&family=PT+Sans:wght@400;700&display=swap" rel="stylesheet">

<style>
  /* 2. FORCE FULL WIDTH & REMOVE THEME MARGINS */
  .wrapper, .container, section, body {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  
  /* Hide the theme's automatic header */
  header { display: none !important; }

  /* 3. TYPOGRAPHY & COLORS */
  body {
    font-family: 'Lora', serif; /* Classic academic serif font */
    color: #333;
    background-color: #fff;
    font-size: 1.1rem;
  }

  h1, h2, h3, nav, .name-label {
    font-family: 'PT Sans', sans-serif; /* Clean headers */
    color: #2e7cc7; /* The specific Zeyu Bian Blue */
  }

  h2 {
    border-bottom: 1.5px solid #2e7cc7;
    padding-bottom: 8px;
    margin-top: 40px;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 1.2rem;
    font-weight: 700;
  }

  /* 4. SIDEBAR NAVIGATION LINKS */
  .nav-link {
    display: block;
    padding: 10px 0;
    color: #2e7cc7;
    text-decoration: none;
    font-weight: bold;
    border-bottom: 1px solid #f5f5f5;
  }
  .nav-link:hover { text-decoration: underline; }

  /* 5. THE MAIN LAYOUT FLEXBOX */
  .academic-layout {
    display: flex;
    padding: 40px;
  }

  .sidebar {
    width: 250px;
    flex-shrink: 0;
    border-right: 1px solid #eee;
    padding-right: 30px;
  }

  .content {
    flex-grow: 1;
    padding-left: 50px;
    max-width: 1200px; /* Limits line length for readability while still being wide */
  }
</style>

<div class="academic-layout">

  <div class="sidebar">
    <img src="profile.jpg" style="width: 100%; border: 1px solid #ddd; margin-bottom: 20px;">
    <div class="name-label" style="font-size: 1.8rem; font-weight: bold;">Ray</div>
    <p style="font-size: 0.9rem; color: #666; margin-top: 5px;">PhD Student<br>University Name</p>
    <nav style="margin-top: 25px;">
      <a class="nav-link" href="/">Home</a>
      <a class="nav-link" href="#about">About</a>
      <a class="nav-link" href="#research">Research</a>
      <a class="nav-link" href="#publications">Publications</a>
      <a class="nav-link" href="/cv.pdf">CV</a>
    </nav>
  </div>

  <div class="content">
    <h1 style="margin-top: 0; font-size: 3rem;">Biography</h1>
    <p>I am a PhD student at <strong>University Name</strong>. My research focuses on the intersection of X and Y...</p>

    <h2 id="about">About</h2>
    <p>Detailed description of your background and education.</p>

    <h2 id="research">Research</h2>
    <p>Current projects include investigating the properties of...</p>

    <h2 id="publications">Selected Publications</h2>
    <p><strong>Ray</strong>, "Sample Paper Title," <em>Scientific Journal</em>, 2025.</p>
  </div>

</div>
