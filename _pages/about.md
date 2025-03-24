---
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
  - /home
  - /home.html
---

<style>
  .about-container {
    display: flex;
    flex-direction: column;
    gap: 30px;
    margin: 30px auto;
    padding: 0 20px;
    max-width: 1200px;
  }

  .about-header {
    text-align: center;
  }

  .about-body {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }

  .left-panel {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .profile-image img {
    max-width: 300px;
    height: auto;
    border-radius: 15px;
    padding: 5px;
    border: 1px solid #ccc;
  }

  .about-text {
    max-width: 700px;
  }

  @media (min-width: 768px) {
    .about-body {
      flex-direction: row;
      align-items: flex-start;
      justify-content: space-between;
    }

    .about-text {
      text-align: left;
    }
  }
</style>

<section id="about-home" class="about-container">

  <!-- Name -->
  <div class="about-header">
    <h1 style="font-size: 2.5em; margin: 0;">Colin P. Adams</h1>
  </div>

  <!-- Image + Buttons | Text -->
  <div class="about-body">

    <!-- Left: Image + Buttons -->
  <div class="left-panel">
      <div class="profile-image">
        <img src="/images/Another Nice Picture.jpg" alt="Colin P. Adams">
      </div>

  <div class="button-container" style="margin-top: 15px;">
        <a href="/CV.pdf" class="icon-button" target="_blank">
          <i class="fas fa-file-alt"></i> CV
        </a>
        <a href="https://scholar.google.com/citations?user=JVDSOfEAAAAJ" class="icon-button" target="_blank">
          <i class="ai ai-google-scholar"></i> Google Scholar
        </a>
        <a href="https://www.researchgate.net/profile/Colin-Adams-3" class="icon-button" target="_blank">
          <i class="fab fa-researchgate"></i> ResearchGate
        </a>
        <a href="https://orcid.org/0009-0002-3490-5927" class="icon-button" target="_blank">
          <i class="ai ai-orcid"></i> ORCID
        </a>
        <a href="https://www.linkedin.com/in/colin-p-adams/" class="icon-button" target="_blank">
          <i class="fab fa-linkedin"></i> LinkedIn
        </a>
      </div>
    </div>

    <!-- Right: Bio Text -->
  <div class="about-text">
      <p>
        I am a second-year Ph.D. student in economics and Charles and Persis Rockwood Fellow at Florida State University. I expect to graduate from FSU in May 2028.
        My research interests are in crime, public, and labor economics with a particular interest in the causes of recidivism in the US.
      </p>
      <p>
        Previously, I graduated from Georgia College & State University with a B.S. in Economics and a B.S. in Finance.
        <a href="https://frontpage.gcsu.edu/node/14695" target="_blank">Here</a> is an article about me from my time at GCSU.
      </p>
    </div>

  </div>
</section>

