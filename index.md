---
layout: default
---

<style>
  /* 1. REMOVE THE THEME FOOTER AND HEADER */
  footer { display: none !important; }
  header { display: none !important; }
  
  /* 2. UNLOCK FULL WIDTH */
  .wrapper, .container, section, body {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 3. FONTS: TIMES NEW ROMAN */
  body {
    font-family: "Times New Roman", Times, serif;
    color: #000;
    background-color: #fff;
    font-size: 1.5rem;
    line-height: 1.5;
  }

  /* Blue headers and navigation */
  h1, h2, .nav-link, .site-title {
    font-family: "Times New Roman", Times, serif;
    color: #2e7cc7;
  }

  h1 { font-size: 2rem; font-weight: bold; margin-top: 0; }

  h2 {
    border-bottom: 1px solid #2e7cc7;
    padding-bottom: 2px;
    margin-top: 30px;
    font-weight: bold;
    font-size: 1.5rem;
  }

  /* 4. SIDEBAR WITH CONTRAST & VERTICAL LINE */
  .sidebar {
    width: 120px;
    flex-shrink: 0;
    padding: 30px 15px;
    background-color: #f8f8f8; /* Contrast color */
    border-right: 1px solid #bbb; /* The separator line */
    min-height: 100vh;
    position: sticky;
    top: 0;
  }

  .nav-link {
    display: block;
    padding: 2px 0;
    text-decoration: none;
    font-size: 2rem;
  }
  .nav-link:hover {
  text-decoration-line: underline;
  text-decoration-style: dashed;
  text-decoration-thickness: 2px;
  text-decoration-color: #2e7cc7;
  }

  /* 5. MAIN CONTENT AREA */
  .content-area {
    flex-grow: 1;
    padding: 30px 50px;
    max-width: 1200px;
  }

  .profile-section {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }
</style>

<div style="display: flex;">

  <div class="sidebar">
    <!-- <div class="site-title" style="font-weight: bold; font-size: 1.1rem; margin-bottom: 15px; color: #000;">Home</div> -->
    <nav>
      <a class="nav-link" href="/">Home</a>
      <!--<a class="nav-link" href="#research">Research</a>
      <a class="nav-link" href="#software">Software</a>
      <a class="nav-link" href="#teaching">Teaching</a>
      <a class="nav-link" href="/cv.pdf">CV</a>-->
    </nav>
  </div>

  <div class="content-area">
    
    <div class="profile-section">
      <img src="profile.jpg" style="width: 180px; margin-right: 30px; border: 1px solid #999; padding: 1px;">
      <div>
        <h1>Shirui (Ray) Wang</h1>
        <p>
          PhD Student<br>
          Georgia State University<br>
          Email: swang58[AT]student[dot]gsu[dot]edu
        </p>
      </div>
    </div>

    <h2 id="about">About</h2>
    <p>HiI am a fifth-year PhD student in biostatistics at Georgia State University, working with Prof. Gengsheng Qin. My research interest focuses on...</p>

    <h2 id="research">Research</h2>
    <p>My research interests include...</p>

    <h2 id="publications">Publications</h2>
    <p><strong>Ray</strong>, "Title of Paper," 2025.</p>

  </div>
</div>
