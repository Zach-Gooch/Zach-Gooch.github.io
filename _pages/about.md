---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  #about-home {
    display: block;
  }

  .sidebar {
    display: none;
    float: left;
    max-width: 300px;
    margin: 20px;
  }

  .page__content {
    margin-left: 320px;
  }

  @media (max-width: 768px), (orientation: portrait) {
    .about-container {
      flex-direction: column;
      align-items: center;
    }

    .about-image,
    .about-text {
      width: 90%;
      max-width: none;
    }

    .page__content {
      margin-left: 0;
    }
  }

  @media (min-width: 768px) and (max-width: 1024px) {
  #about-home {
    display: none;
  }

  .sidebar {
    display: block !important;
  }

  .page__content {
    margin-left: 320px;
  }
}

</style>


<!-- Your Custom Layout -->
<section id="about-home">

  <!-- Name -->
  <div style="text-align: center; margin-bottom: 30px;">
    <h1 style="font-size: 2.5em; margin: 0;">Colin P. Adams</h1>
  </div>

  <!-- Main Layout: Image + Text -->
  <div class="about-container">

    <!-- Profile Picture -->
  <div class="about-image">
      <img src="/images/Another Nice Picture.jpg" alt="Colin P. Adams" 
           style="width: 100%; height: auto; border-radius: 15px; 
                  padding: 5px; border: 1px solid #ccc;">
    </div>

    <!-- Bio + Buttons -->
  <div class="about-text" id="about-me">
      <p>
        I am a second-year Ph.D. student in economics and Charles and Persis Rockwood Fellow at Florida State University. I expect to graduate from FSU in May 2028.
        I am an applied microeconomist with research interests in crime, public, and labor economics. I have a particular interest in the causes of recidivism as well as the economics of financial education.
      </p>
      <p>
        Previously, I graduated from Georgia College & State University with a B.S. in Economics and a B.S. in Finance.
        <a href="https://frontpage.gcsu.edu/node/14695" target="_blank">Here</a> is an article about me from my time at GCSU.
      </p>

  <div class="button-container" style="margin-top: 20px;">
        <a href="/CV.pdf" class="icon-button" target="_blank"><i class="fas fa-file-alt"></i> CV</a>
        <a href="https://scholar.google.com/citations?user=JVDSOfEAAAAJ" class="icon-button" target="_blank"><i class="ai ai-google-scholar"></i> Google Scholar</a>
        <a href="https://www.researchgate.net/profile/Colin-Adams-3" class="icon-button" target="_blank"><i class="fab fa-researchgate"></i> ResearchGate</a>
        <a href="https://orcid.org/0009-0002-3490-5927" class="icon-button" target="_blank"><i class="ai ai-orcid"></i> ORCID</a>
        <a href="https://www.linkedin.com/in/colin-p-adams/" class="icon-button" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
      </div>
    </div>

  </div>
</section>
