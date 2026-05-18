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
  text-underline-offset: 5px;
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
  text-underline-offset: 5px;
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
    <a class="nav-link" href="#research">Research</a>
    <a class="nav-link" href="#software">Software</a> 
    <a class="nav-link" href="#teaching">Teaching</a> 
  </nav>
</div>

  <div class="content-area">
    <div class="profile-section">
      <img src="photo.jpg" style="width: 180px; margin-right: 30px; border: 1px solid #999; padding: 1px;">
      <div>
        <h1>Shirui (Ray) Wang</h1>
        <p>
          PhD Student<br>
          Georgia State University<br>
          Email: swang58[AT]student[dot]gsu[dot]edu<br>
        <a href="https://github.com/swang1021" target="_blank"> <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="28" height="28" style="vertical-align: middle;" > </a>
        <a href="https://scholar.google.com/citations?hl=en&tzom=300&user=m0mzHBIAAAAJ" target="_blank"> <img src="https://user-images.githubusercontent.com/66117993/96351903-818a8b00-1084-11eb-96f6-3a931d66fff6.png" width="26" height="26" alt="Google Scholar" style="vertical-align: middle;" > </a>
        <a href="https://www.researchgate.net/profile/Shirui-Wang-6/publications" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/ResearchGate_icon_SVG.svg" width="26" height="26" alt="ResearchGate" style="vertical-align: middle;" > </a>
        <a href="https://www.linkedin.com/in/shirui-wang-8483432b7" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" width="26" height="26" alt="LinkedIn" style="vertical-align: middle;" > </a>
        </p>
      </div>
    </div>
    <h2 id="about">About Me</h2>
    <p>Hi! I am a fifth-year PhD student in biostatistics at Georgia State University, working with <a href="https://cas.gsu.edu/profile/gengsheng-qin/" target="_blank" rel="noopener">Prof. Gengsheng Qin</a>. Here is my <a href="CV.pdf" target="_blank" rel="noopener">CV (updated Feb 2026)</a>.</p>
    
<section id="research">
    <h2>Research</h2>
    <p>My current research interests center on: 
      <ul> 
        <li>Developing statistical tools to identify and validate biomarkers for (early) disease detection and personalized medicine</li> 
        <li>Causal inference and its application to real‑world observational healthcare data</li> 
        <li>Statistical/mathematical/deep learning modeling of infectious disease dynamics</li>
        <li>Statistical applications in sports analytics</li>
      </ul>
    
<section id="publications"><h2>Publications and Working Papers</h2>
    <p><strong>Wang S</strong>, Shi S, Qin G. Interval estimation for the Youden index of a continuous diagnostic test with verification biased data. <em>Statistical Methods in Medical Research</em> 2025; 34: 796-811. <a href="https://journals.sagepub.com/doi/10.1177/09622802251322989" target="_blank" rel="noopener">doi:10.1177/09622802251322989</a></p>
    <p><strong>Wang S</strong>, Shi S, Qin G. Empirical likelihood inference for the area under the ROC curve with verification biased data. <em>Statistical Methods in Medical Research, Accepted May 2026</em></p>
    <p>Shi S, <strong>Wang S</strong>, Qin G. Interval estimation for three-class Youden index with verification bias. <em>Journal of Biopharmaceutical Statistics</em> 2025; 1: 1-22. <a href="https://www.tandfonline.com/doi/abs/10.1080/10543406.2025.2549361" target="_blank" rel="noopener">doi:10.1080/10543406.2025.2549361</a></p>
    <p>Jia S, <strong>Wang S</strong>, Qin G. Methodological Approaches for the Estimation of Confidence Intervals on Partial Youden Index under Verification Bias. <em>Pharmaceutical Statistics</em> 2026; 25: e70079. <a href="https://onlinelibrary.wiley.com/doi/10.1002/pst.70079" target="_blank" rel="noopener">doi:10.1002/pst.70079</a></p>
    <p>Shi S, <strong>Wang S</strong>, Qin G. Interval Estimation for the Sensitivity of a Test to the Early Diseased Stage with Verification Bias. <em>Revision at Pharmaceutical Statistics</em></p>
    <p><strong>Wang S</strong>, Shi S, Qin G. Empirical likelihood-based confidence intervals for sensitivity of a continuous test at a fixed level of specificity with verification bias. <em>Submitted</em></p>
    <p>Jia S, <strong>Wang S</strong>, Qin G. Empirical Likelihood-Based Confidence Intervals for the Partial AUC with Verification Bias. <em>Revision at Pharmaceutical Statistics</em></p>
    <p><strong>Wang S</strong>, Islami F, Siegel RL, Jemal A, Choudhury PP. Imputation of missing cancer stage at diagnosis accounting for stage-specific survival. <em>Manuscript in preparation</em></p>
    <p>Choudhury PP, Zhao J, <strong>Wang S</strong>, Jemal A, Yabroff R, Islami F. Are disruptions in Medicaid coverage linked to advanced stage diagnosis of screen-detectable cancers? <em>Manuscript in preparation</em></p></section>
    
<section id="software"> <h2>Software</h2> <p><strong><em>rocvb</em></strong>: R package for ROC-Based Inference for Diagnostic Accuracy Under Verification Bias. [<a href="https://cran.r-project.org/web/packages/rocvb/index.html" target="_blank" rel="noopener">CRAN</a>] [<a href="https://github.com/swang1021/rocvb" target="_blank" rel="noopener">GitHub</a>]</p> </section>

<section id="teaching"> <h2>Teaching</h2> <p> I am an enthusiastic and responsible instructor with three years of undergraduate‑level math and statistics teaching experience, dedicated to fostering effective learning environments and supporting student success in the age of AI. </p> 
  <p>My past teacing experience is listed below (semester, course, my role and enrollment). Here is my <a href="Student Evaluations.pdf" target="_blank" rel="noopener"> student evaluations</a>.</p>
  <p>Spring 2025: Elementary Statistics (Online), Primary instructor, Enrollment: 108</p>
  <p>Fall 2024: Elementary Statistics (Online, 2 sections), Primary instructor, Enrollment: 87+76</p>
  <p>Summer 2024: Elementary Statistics (Online), Primary instructor, Enrollment: 31</p>
  <p>Spring 2024: Elementary Statistics (Face-to-Face, 2 sections), Primary instructor, Enrollment: 98+109</p>
  <p>Fall 2023: Elementary Statistics (Online & Face-to-Face), Primary instructor, Enrollment: 43+94</p>
  <p>Spring 2023: Elementary Statistics (Face-to-Face, 2 sections), Primary instructor, Enrollment: 105+95</p>
  <p>Fall 2022: Elementary Statistics (Online & Face-to-Face), Primary instructor, Enrollment: 100+82</p>
  <p>Summer 2022: Calculus for the life sciences (Face-to-Face), Teaching Assistant, Enrollment: 45</p>
  <p>Spring 2022: Applied Probability and Statistics for Computer Science (Face-to-Face, 2 sections), Teaching Assistant, Enrollment: 96+61</p>
  <p>Fall 2021: Applied Probability and Statistics for Computer Science (Face-to-Face, 2 sections), Teaching Assistant, Enrollment: 61+59</p>
  <p>Summer 2021: Linear Algebra I (Online), Teaching Assistant, Enrollment: 35</p>
  <p>Spring 2021: College Algebra (Online), Lab Assistant, Enrollment: 120</p>
  <p>Fall 2020: Precalculus (Online), Lab Assistant, Enrollment: 120</p>
  <p>Spring 2020: Precalculus (Face-to-Face/Online), Lab Assistant, Enrollment: 120</p></section>

<section id="others"> <h2>More about me...</h2>
<p>My hobbies include watching movies, reading and writing. Check my <a href="https://www.douban.com/people/207012599/" target="_blank" rel="noopener">douban</a> and <a href="https://moumouw.home.blog/" target="_blank" rel="noopener">blog</a>.</p></section>
