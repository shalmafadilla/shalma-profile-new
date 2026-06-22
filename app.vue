<template>

    <header>
      <nav class="navbar navbar-expand-lg" style="padding: 25px; 
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
  position: fixed; 
  width: 100%; 
  top: 0; 
  z-index: 1000; 
  background: rgba(255, 255, 255, 0.7); 
  backdrop-filter: blur(10px); 
  -webkit-backdrop-filter: blur(10px);">

      <div class="container-fluid">
        <a class="navbar-brand" href="#">Shalma's Profile Page</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#main-section">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#aboutme">About Me</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#portfolio">Portfolio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact-me">Contact Me</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  
  <main>
    <section class="main-section">
      <div class="foto">
        <img src="/assets/profile.jpg" alt="foto" width="500px" style="flex-wrap: wrap;"/>
      </div>
      <div class="name">
        <h1 style="color:#e773ab;"><b>Hello, I'am</b></h1>
        <h1 style="color:#e773ab;"><b>Shalma Nur Fadilla</b></h1>
        <p>Front-end Developer & UI/UX Enthusiast</p>
        <div class="action">
          <div class="cv">
            <a href="https://drive.google.com/file/d/1z4rlAUoqdPDfXePcZN8Zl2tz57fvh8Mq/view?usp=drive_link" style="text-decoration: none; color: #fff3fa;">
            <h6>My Resume</h6></a>
          </div>

        </div>
      </div>
    </section>
        
    <section id="aboutme">
      <div>
        <h1><b>ABOUT ME</b></h1>
        <p>Soon-to-be Information Technology graduate from Universitas Brawijaya with interests in Project Management, Product Development, Quality Assurance (QA), and Front-End Web Development. Experienced in developing and managing web-based digital products through academic and organizational projects, with strong skills in project coordination, software testing, problem-solving, and team collaboration. Passionate about delivering user-centered digital solutions and continuously learning new technologies to create impactful products, and let's be friend!</p>
      </div>
        
          <section class="others">
  <div class="info-card">
    <h2 class="card-title">Personal Info</h2>
    <div class="info-list">
      <div class="info-item">
        <span class="label">Name</span>
        <span class="value">Shalma Nur Fadilla</span>
      </div>
      <div class="info-item">
        <span class="label">Location</span>
        <span class="value">Malang, East Java</span>
      </div>
      <div class="info-item">
        <span class="label">Focus</span>
        <span class="value">Front-End, UI/UX, QA, Project Management</span>
      </div>
      <div class="info-item">
        <span class="label">Status</span>
        <span class="value">Final-year IT Diploma Student</span>
      </div>
    </div>
  </div>

  <div class="info-card">
    <h2 class="card-title">Education</h2>
    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-top">
          <h4>Information Technology</h4>
          <span>2023 - Present</span>
        </div>
        <p>Universitas Brawijaya</p>
      </div>

      <div class="timeline-item">
        <div class="timeline-top">
          <h4>Senior High School</h4>
          <span>2020 - 2023</span>
        </div>
        <p>SMAN 1 Kauman</p>
      </div>
    </div>
  </div>
</section>
        </section>
  
        <section id="portfolio">
          <h1><b>MY PROJECT(s)</b></h1>
          <P>These are all the projects I developed over the past two semesters, with various programming languages and showcasing creativity on its design.</P>
          <div class="portfolio-inside">
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project1.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Company</h5>
                <p class="card-text">This project aims to create a company website for a beads business as a branding tool, featuring a Home page, an About Us page, and Instagram integration to make it easier for customers to place orders through the website. </p>
              </div>
            </div>
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project2.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Profile Page</h5>
                <p class="card-text">This profile page showcases the developer's profile, work experience, skills, and projects that have worked on as part of their digital portfolio.</p>
              </div>
            </div>
          </div>
          <div class="portfolio-inside">
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project3.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Library Web App</h5>
                <p class="card-text">A website-based library application that allows administrators to efficiently manage the book borrowing process for users. </p>
              </div>
            </div>
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project4.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Inventory</h5>
                <p class="card-text">This project creates a CRUD website using PHP to manage the quantity of each item based on its category.</p>
              </div>
            </div>
          </div>
        </section>
        
        <section id="contact-me">
          <h1><b>CONTACT ME</b></h1>
          <h4>Please contact me bellow for more.</h4>
          <div class="contact-me">
            <a href="https://github.com/shalmafadilla">
              <img src="/assets/gh.png" alt="github" class="img-fluid me-3 mb-3" width="50px">
            </a>
            <a href="https://www.linkedin.com/in/shalma-nur-fadilla-130392283?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">
              <img src="/assets/in.png" alt="linkedin" class="img-fluid me-3 mb-3" width="50px">
            </a>
            <a href="https://www.instagram.com/nurfadillashalma?igsh=MXBnemc0aWFnbWxjcg==">
              <img src="/assets/ig.png" alt="ig" class="img-fluid me-3 mb-3" width="50px">
            </a>
            <a href="https://x.com/shalmanaff?s=21">
              <img src="/assets/x.png" alt="x" class="img-fluid me-3 mb-3" width="50px">
            </a>
          </div>
        </section>
        
        <footer>&copy;2024-made with 💖 by Shalma Nur Fadilla.</footer>
        </main>
  </template>
  
  <script>
  export default {
    name: 'HomePage'
  }
  </script>
  
  <style scoped>
  template{
    font-weight: 100;
  }
  
  .navbar-nav {
    height: 50px;
    align-items: center;
  }
  
  p{
    color: rgb(106, 106, 106);
  }

  td{
    text-align: left;
    font-size: 15px;
  }
  
  main {
    background-image: url("bg.png");
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
  }
  
  .main-section {
    display: flex;
    height: 750px;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }
  
  .name {
    font-size: 20px;
  }

  .cv {
    width: max-content;
    padding: 7px 17px;
    background-color: #e773ab;
    color: #fff3fa;
    border-radius: 25px;
    align-items: center;
    justify-content: center;
  }

  .cv:hover{
    background-color: #c02170;
    cursor: pointer;;
  }

@media (max-width: 768px) {
  .foto {
    width: 100%;
    display: block;
    margin: 0 auto;
    text-align: center;
  }

  .foto img {
    margin-top: 100px;
    width: 86%;
  }

  .name {
    text-align: center;
  }
}

  #aboutme {
    font-size: 20px;
    margin: 0 auto;
    margin-top: 20px;
    padding-top: 30px;
    text-align: center;
    background-color: #fff3fa;
  }
  
  /* section others */
  .others {
    display: flex;
    margin: 0 auto;
    margin-top: 20px;
    padding: 20px;
    gap: 50px;
    justify-content: center;
    flex-wrap: wrap;
  }
  
  .edu{
    text-align: center;
  }

  .con-bio{
    margin: 0 auto;
    margin-top: 0px;
    border-radius: 30px;

  }
  
  .bio {
    padding: 30px;
    margin: 0 auto;
  }
  
  #portfolio{
    font-size: 20px;
    margin: 0 auto;
    margin-top: 0px;
    text-align: center;
    padding: 20px;
    background-color: #fff3fa;
  
  }
  
  .portfolio-inside{
    display: flex;
    gap: 100px;
    margin: 0 auto;
    margin-bottom: 20px;
    width: 100%;
    padding: 20px;
    justify-content: center;
    flex-wrap: wrap;
  }
  
  #contact-me{
    font-size: 20px;
    margin: 0 auto;
    margin-top: 0px;
    text-align: center;
    padding: 20px;
    background-color: #e884ba;
  }
  
  .item {
    margin-top: 10px;
    margin-bottom: 10px;
  }
  
  a img:hover {
    opacity: 0.7;
    transition: opacity 0.3s ease;
  }
  
  footer{
    text-align: center;
    padding: 20px 0px;
    background-color: #e884ba;
  }
  </style>