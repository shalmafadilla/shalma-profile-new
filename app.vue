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
template {
  font-weight: 100;
}

/* GLOBAL */
html {
  scroll-behavior: smooth;
}

p {
  color: rgb(106, 106, 106);
  line-height: 1.8;
}

main {
  background-image: url("bg.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  width: 100%;
  overflow-x: hidden;
}

/* NAVBAR */
.navbar-nav {
  height: 50px;
  align-items: center;
}

.navbar-brand {
  font-weight: 700;
  color: #d85b98 !important;
}

.nav-link {
  color: #6a6a6a !important;
  font-weight: 500;
  transition: 0.3s ease;
}

.nav-link:hover {
  color: #e773ab !important;
}

/* HERO SECTION */
.main-section {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  padding: 120px 40px 60px;
  gap: 40px;
}

.foto {
  flex: 1;
  min-width: 280px;
  text-align: center;
}

.foto img {
  max-width: 100%;
  width: 420px;
  border-radius: 30px;
  object-fit: cover;
}

.name {
  flex: 1;
  min-width: 280px;
  font-size: 20px;
}

.name h1 {
  margin: 0;
  line-height: 1.2;
}

.name p {
  margin-top: 14px;
  font-size: 18px;
}

.cv {
  width: max-content;
  padding: 10px 22px;
  background-color: #e773ab;
  color: #fff3fa;
  border-radius: 30px;
  margin-top: 18px;
  transition: 0.3s ease;
  box-shadow: 0 8px 20px rgba(231, 115, 171, 0.2);
}

.cv h6 {
  margin: 0;
}

.cv:hover {
  background-color: #c02170;
  cursor: pointer;
  transform: translateY(-2px);
}

/* ABOUT ME */
#aboutme {
  font-size: 20px;
  margin: 0 auto;
  padding: 70px 20px 40px;
  text-align: center;
  background: linear-gradient(to bottom, #fff7fb, #fff3fa);
}

#aboutme > div:first-child {
  max-width: 950px;
  margin: 0 auto;
}

#aboutme h1 {
  color: #d85b98;
  margin-bottom: 14px;
}

#aboutme p {
  max-width: 850px;
  margin: 0 auto;
}

/* ABOUT CARDS */
.others {
  display: flex;
  justify-content: center;
  gap: 28px;
  flex-wrap: wrap;
  margin-top: 40px;
  padding: 0 20px 30px;
}

.info-card {
  width: 100%;
  max-width: 500px;
  background: rgba(255, 255, 255, 0.82);
  border: 1px solid #f7dce9;
  border-radius: 28px;
  padding: 28px;
  text-align: left;
  box-shadow: 0 10px 30px rgba(231, 115, 171, 0.08);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
}

.card-title {
  font-size: 28px;
  color: #d85b98;
  margin-bottom: 22px;
  text-align: center;
}

.info-list {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.info-item {
  display: flex;
  flex-direction: column;
  gap: 6px;
  padding: 14px 16px;
  background-color: #fff8fc;
  border-radius: 18px;
  border: 1px solid #f7dce9;
}

.label {
  font-size: 14px;
  color: #b06a8b;
  letter-spacing: 0.3px;
}

.value {
  font-size: 17px;
  color: #444;
  font-weight: 600;
}

.timeline {
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.timeline-item {
  background-color: #fff8fc;
  border: 1px solid #f7dce9;
  border-radius: 18px;
  padding: 18px 20px;
}

.timeline-top {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 12px;
  flex-wrap: wrap;
}

.timeline-top h4 {
  margin: 0;
  font-size: 18px;
  color: #444;
}

.timeline-top span {
  font-size: 14px;
  color: #b06a8b;
  background-color: #fdebf3;
  padding: 6px 12px;
  border-radius: 999px;
}

.timeline-item p {
  margin: 10px 0 0;
  color: #666;
  font-size: 15px;
}

/* PORTFOLIO */
#portfolio {
  font-size: 20px;
  margin: 0 auto;
  text-align: center;
  padding: 60px 20px;
  background-color: #fff3fa;
}

#portfolio h1 {
  color: #d85b98;
  margin-bottom: 12px;
}

#portfolio > p {
  max-width: 850px;
  margin: 0 auto 30px;
}

.portfolio-inside {
  display: flex;
  gap: 40px;
  margin: 0 auto 20px;
  width: 100%;
  padding: 10px 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  border: none !important;
  border-radius: 24px !important;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(231, 115, 171, 0.12);
  transition: 0.3s ease;
}

.card:hover {
  transform: translateY(-6px);
}

.card-img-top {
  height: 250px;
  object-fit: cover;
}

.card-body {
  padding: 22px;
}

.card-title {
  color: #d85b98;
}

/* CONTACT */
#contact-me {
  font-size: 20px;
  margin: 0 auto;
  text-align: center;
  padding: 60px 20px 30px;
  background-color: #e884ba;
  color: white;
}

#contact-me h1,
#contact-me h4 {
  color: white;
}

.contact-me {
  margin-top: 24px;
}

.contact-me a {
  display: inline-block;
  margin: 0 8px;
}

.contact-me img {
  transition: 0.3s ease;
}

.contact-me img:hover {
  transform: translateY(-4px) scale(1.05);
  opacity: 0.85;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 18px 12px;
  background-color: #e884ba;
  color: white;
  font-size: 15px;
}

/* RESPONSIVE */
@media (max-width: 992px) {
  .main-section {
    padding: 120px 24px 50px;
  }

  .foto img {
    width: 340px;
  }
}

@media (max-width: 768px) {
  .main-section {
    flex-direction: column;
    text-align: center;
    gap: 20px;
    padding: 120px 20px 50px;
  }

  .foto {
    width: 100%;
    display: block;
    margin: 0 auto;
    text-align: center;
  }

  .foto img {
    margin-top: 20px;
    width: 85%;
    max-width: 320px;
  }

  .name {
    text-align: center;
    font-size: 18px;
  }

  .cv {
    margin: 18px auto 0;
  }

  #aboutme {
    padding: 50px 16px 30px;
  }

  .info-card {
    padding: 22px 18px;
  }

  .card-title {
    font-size: 24px;
  }

  .timeline-top {
    flex-direction: column;
    align-items: flex-start;
  }

  #portfolio,
  #contact-me {
    padding-left: 16px;
    padding-right: 16px;
  }

  .portfolio-inside {
    gap: 24px;
    padding: 10px 0;
  }
}
</style>