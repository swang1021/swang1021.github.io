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
    line-height: 1.2;
  }

  /* Blue headers and navigation */
  h1, h2, .nav-link, .site-title {
    font-family: Georgia, "Times New Roman", serif;
    color: #2e7cc7;
  }

  h1 { font-size: 3rem; font-weight: bold; margin-top: 0; }

  h2 {
    border-bottom: 1px solid #2e7cc7;
    padding-bottom: 2px;
    margin-top: 30px;
    font-weight: bold;
    font-size: 2rem;
  }

  .content-area a {
  font-weight: inherit;          /* don’t force bold */
  text-decoration: none;
  }

  .content-area a:hover {
  font-weight: inherit !important;                 /* stop “bold on hover” */
  text-decoration-line: underline !important;      /* force underline */
  text-decoration-style: dotted !important;        /* or dashed */
  text-decoration-thickness: 1px;
  text-underline-offset: 3px;
  }

  /* 4. SIDEBAR WITH CONTRAST & VERTICAL LINE */
  .sidebar {
  width: 100px;
  flex-shrink: 0;
  padding: 30px 15px;
  background-color: #f8f8f8;
  border-right: 1px solid #bbb;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;  /* Horizontal center */
  }

  .nav-link {
    display: block;
    padding: 2px 0;
    font-weight: bold;
    text-decoration: none;
    font-size: 1.5rem;
  }
  .nav-link:hover {
  text-decoration-line: underline;
  text-decoration-style: dotted;
  text-decoration-thickness: 1px;
  text-underline-offset: 3px;
  }

  /* 5. MAIN CONTENT AREA */
  .content-area {
    flex-grow: 1;
    padding: 30px 50px;
    max-width: none;
  }

  .profile-section {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }
</style>

<div style="display: flex;"> <div class="sidebar"> 
  <!--<div class="site-title" style="font-weight: bold; font-size: 1.1rem; margin-bottom: 15px; color: #000;">Home</div>-->
  <nav> <a class="nav-link" href="/">Home</a>
    <!--<a class="nav-link" href="#research">Research</a> <a class="nav-link" href="#software">Software</a> <a class="nav-link" href="#teaching">Teaching</a> <a class="nav-link" href="/cv.pdf">CV</a>-->
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
    <h2 id="about">About Me</h2>
    <p>Hi! I am a fifth-year PhD student in biostatistics at Georgia State University, working with <a href="https://cas.gsu.edu/profile/gengsheng-qin/" target="_blank" rel="noopener">Prof. Gengsheng Qin</a>. Here is my <a href="CV_Shirui Wang.pdf" target="_blank" rel="noopener">CV (updated Dec 2025)</a>.</p>
    <h2 id="research">Research</h2>
    <p>My current research interests center on developing statistical tools to identify and validate biomarkers for (early) disease detection and personalized medicine.</p>
    <h2 id="publications">Publications and Working Papers</h2>
    <p><strong>Wang S</strong>, Shi S, Qin G. Interval estimation for the Youden index of a continuous diagnostic test with verification biased data. <em>Statistical Methods in Medical Research</em> 2025; 34: 796-811. <a href="https://journals.sagepub.com/doi/10.1177/09622802251322989" target="_blank" rel="noopener">doi:10.1177/09622802251322989</a></p>
    <p>Shi S, <strong>Wang S</strong>, Qin G. Interval estimation for three-class Youden index with verification bias. <em>Journal of Biopharmaceutical Statistics</em> 2025; 1: 1-22. <a href="https://www.tandfonline.com/doi/abs/10.1080/10543406.2025.2549361" target="_blank" rel="noopener">doi:10.1080/10543406.2025.2549361</a></p>
    <p>Shi S, <strong>Wang S</strong>, Qin G. Interval Estimation for the Sensitivity of a Test to the Early Diseased Stage with Verification Bias. <em>Revision at Pharmaceutical Statistics</em>
    <p>Jia S, <strong>Wang S</strong>, Qin G. Methodological Approaches for the Estimation of Confidence Intervals on Partial Youden Index under Verification Bias. <em>Revision at Pharmaceutical Statistics</em>
    <p><strong>Wang S</strong>, Shi S, Qin G. Empirical likelihood inference for the area under the ROC curve with verification biased data. <em>Submitted</em>
    <p><strong>Wang S</strong>, Shi S, Qin G. Empirical likelihood-based confidence intervals for sensitivity of a continuous test at a fixed level of specificity with verification bias. <em>Submitted</em>
    <p>Jia S, <strong>Wang S</strong>, Qin G. Empirical Likelihood-Based Confidence Intervals for the Partial AUC with Verification Bias. <em>Revision at Pharmaceutical Statistics</em>
    <p><strong>Wang S</strong>, Islami F, Siegel RL, Jemal A, Choudhury PP. Imputation of missing cancer stage at diagnosis accounting for stage-specific survival. <em>Manuscript in preparation</em>
    <p>Choudhury PP, Zhao J, <strong>Wang S</strong>, Jemal A, Yabroff R, Islami F. Are disruptions in Medicaid coverage linked to advanced stage diagnosis of screen-detectable cancers? <em>Manuscript in preparation</em>
    <h2 id="others">More about me...</h2>
    <p>My hobbies include watching movies, reading and writing. Check my <a href="https://www.douban.com/people/207012599/" target="_blank" rel="noopener">douban</a> and <a href="https://moumouw.home.blog/" target="_blank" rel="noopener">blog</a>.</p>
