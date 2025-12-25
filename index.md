---
layout: default
title: Ray
---

<style>
  /* This expands the page to full width */
  .wrapper {
    max-width: 95% !important;
    margin: 0 auto !important;
  }
  
  /* Hides the default theme header/sidebar to give you total control */
  header { 
    display: none !important; 
  }
  
  /* Fixes the main section width */
  section {
    width: 100% !important;
    float: none !important;
    padding: 0 !important;
  }

  /* Styling for your custom sidebar links */
  nav a {
    text-decoration: none;
    color: #003366;
    display: block;
    padding: 5px 0;
    font-size: 1.1em;
  }

  nav a:hover {
    text-decoration: underline;
  }

  /* Section headers like Zeyu Bian's */
  h2 {
    color: #003366;
    border-bottom: 1.5px solid #003366;
    padding-bottom: 5px;
    margin-top: 40px;
    font-family: serif;
  }
</style>

<table style="width:100%; border:none; border-collapse:collapse; margin-top: 20px;">
  <tr>
    <td style="width:15%; vertical-align:top; border-right: 1px solid #eee; padding-right: 20px;">
      <h3 style="margin-top:0;">Navigation</h3>
      <nav>
        <a href="/">Home</a>
        <a href="#about">About</a>
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="/cv.pdf">CV</a>
      </nav>
    </td>

    <td style="width:85%; vertical-align:top; padding-left: 40px;">
      
      <div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
        <img src="profile.jpg" style="width:200px; border:1px solid #ccc; margin-right:30px;">
        <div>
          <h1 style="margin:0; font-size: 2.5em;">Ray</h1>
          <p style="font-size: 1.2em; line-height: 1.6;">
            PhD Student<br>
            University Name<br>
            Department of Science<br>
            Email: <a href="mailto:your@email.edu">your@email.edu</a>
          </p>
        </div>
      </div>

      <h2 id="about">About</h2>
      <p>I am a PhD student at University Name. My research focuses on the intersection of X and Y...</p>

      <h2 id="research">Research</h2>
      <p>My current research interests include:</p>
      <ul>
        <li><strong>Research Topic 1:</strong> Description of your work and methodology.</li>
        <li><strong>Research Topic 2:</strong> Description of your work and methodology.</li>
      </ul>

      <h2 id="publications">Publications</h2>
      <p><strong>Ray</strong>, "Title of your first major paper," <em>Journal of Research</em>, 2025.</p>
      <p><strong>Ray</strong>, "Title of your conference paper," <em>Proceedings of Science</em>, 2024.</p>
      
    </td>
  </tr>
</table>
