---
layout: default
title: Ray
---

<style>
  /* 1. FORCE THE PAGE TO USE FULL WIDTH */
  .wrapper, .container, section {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 auto !important;
    padding: 0 !important;
  }
  header { display: none !important; }

  /* 2. BASE TYPOGRAPHY (Academic Standard) */
  body {
    font-family: 'Lora', serif; /* Elegant serif for body text */
    color: #333;
    line-height: 1.7;
    background-color: #fff;
  }

  /* 3. THE "ACADEMIC BLUE" & HEADER STYLE */
  h1, h2, h3, h4, nav, .sidebar-name {
    font-family: 'PT Sans', sans-serif; /* Clean sans-serif for headers */
    color: #2e7cc7; /* The specific Blue you want */
  }

  h2 {
    border-bottom: 1.5px solid #2e7cc7;
    padding-bottom: 8px;
    margin-top: 50px;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 1.3em;
  }

  /* 4. SIDEBAR STYLING */
  .nav-link {
    display: block;
    padding: 10px 0;
    color: #2e7cc7;
    text-decoration: none;
    font-weight: bold;
    font-family: 'PT Sans', sans-serif;
    border-bottom: 1px solid #f0f0f0;
  }
  
  .nav-link:hover { color: #1a4a7a; text-decoration: underline; }
</style>

<div style="display: flex; width: 100%; align-items: flex-start; padding: 40px 20px;">

  <div style="width: 240px; flex-shrink: 0; position: sticky; top: 40px;">
    <img src="profile.jpg" style="width: 100%; border: 1px solid #eee; margin-bottom: 20px;">
    <div class="sidebar-name" style="font-size: 1.5em; font-weight: bold; margin-bottom: 5px;">Ray</div>
    <p style="font-size: 0.9em; color: #666; font-family: 'PT Sans', sans-serif;">
        PhD Student<br>University Name
    </p>
    <nav style="margin-top: 20px;">
      <a class="nav-link" href="/">Home</a>
      <a class="nav-link" href="#about">About</a>
      <a class="nav-link" href="#research">Research</a>
      <a class="nav-link" href="#publications">Publications</a>
      <a class="nav-link" href="/cv.pdf">CV</a>
    </nav>
  </div>

  <div style="flex-grow: 1; padding-left: 60px; max-width: 1000px;">
    
    <h1 style="margin-top: 0; font-size: 2.8em;">Biography</h1>
    <p>I am a PhD student at <strong>University Name</strong>. My research focuses on ...</p>
    
    <h2 id="about">About</h2>
    <p>Detailed description of your background, education, and general research interests.</p>

    <h2 id="research">Research</h2>
    <p>My current projects include investigating the fundamental properties of...</p>
    <ul>
      <li><strong>Project One:</strong> Focuses on X and its impact on Y.</li>
      <li><strong>Project Two:</strong> Developing new methodologies for Z.</li>
    </ul>

    <h2 id="publications">Selected Publications</h2>
    <p><strong>Ray</strong>, "An Influential Academic Paper Title," <em>Scientific Journal</em>, 2025.</p>
    <p><strong>Ray</strong>, "Conference Contribution on Specific Topic," 2024.</p>
    
  </div>
</div>
