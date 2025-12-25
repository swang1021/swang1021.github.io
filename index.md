---
layout: default
title: Ray
---

<style>
  /* 1. TARGET THE THEME'S MAIN BOXES TO UNLOCK FULL WIDTH */
  .wrapper, .container, section, .inner {
    max-width: 98% !important;
    width: 98% !important;
    margin: 0 auto !important;
    padding: 10px !important;
  }

  /* 2. HIDE THE THEME'S AUTOMATIC SIDEBAR COMPLETELY */
  header { 
    display: none !important; 
  }

  /* 3. SET ACADEMIC FONTS & COLORS */
  body {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: #333;
  }

  h2 {
    color: #003366;
    border-bottom: 1px solid #003366;
    padding-bottom: 5px;
    margin-top: 40px;
  }

  nav a {
    text-decoration: none;
    color: #007bff;
    display: block;
    padding: 8px 0;
    font-size: 1.1em;
  }
</style>

<div style="display: flex; width: 100%; align-items: flex-start;">

  <div style="width: 220px; flex-shrink: 0; border-right: 1px solid #eee; padding-right: 20px;">
    <h3 style="margin-top:0;">Navigation</h3>
    <nav>
      <a href="/">Home</a>
      <a href="#about">About</a>
      <a href="#research">Research</a>
      <a href="#publications">Publications</a>
      <a href="/cv.pdf">CV</a>
    </nav>
  </div>

  <div style="flex-grow: 1; padding-left: 40px;">
    
    <div style="display: flex; align-items: center; margin-bottom: 40px;">
      <img src="profile.jpg" style="width:200px; border:1px solid #ccc; margin-right:30px;">
      <div>
        <h1 style="margin:0; font-size: 2.8em;">Ray</h1>
        <p style="font-size: 1.2em; line-height: 1.5; margin-top: 10px;">
          PhD Student<br>
          University Name<br>
          Email: <a href="mailto:your@email.edu">your@email.edu</a>
        </p>
      </div>
    </div>

    <h2 id="about">About</h2>
    <p>I am a PhD student at University Name. My research focuses on the intersection of X and Y...</p>

    <h2 id="research">Research</h2>
    <p>My current research interests include:</p>
    <ul>
      <li>Topic A: Description of work.</li>
      <li>Topic B: Description of work.</li>
    </ul>

    <h2 id="publications">Publications</h2>
    <p><strong>Ray</strong>, "Sample Paper Title," 2025.</p>
    
  </div>
</div>
