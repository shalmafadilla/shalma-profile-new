<template>

  <header>
          <nav class="navbar navbar-expand-lg bg-body-tertiary" style="padding: 25px;">
              <div class="container-fluid">
                  <a class="navbar-brand" href="#">Web Profile Page</a>
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                      <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarNav">
                      <ul class="navbar-nav ms-auto">
                          <li class="nav-item">
                              <a class="nav-link active" aria-current="page" href="#main-section">Home</a>
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
        <section id="main-section">
          <div class="foto">
            <img src="/assets/profile.jpg" alt="foto" width="400px" />
          </div>
          <div class="name">
            <h1 style="color:#ff90bb;"><b>SHALMA NUR FADILLA</b></h1>
            <p>Information Technology Student</p>
            <div class="icon">
            <img src="/assets/html.jpg" alt="html" class="img-fluid me-3 mb-3" width="40px" />
            <img src="/assets/css.jpg" alt="css" class="img-fluid me-3 mb-3" width="40px" />
            <img src="/assets/java.jpg" alt="java" class="img-fluid me-3 mb-3" width="40px" />
            <img src="/assets/cpp.jpg" alt="cpp" class="img-fluid me-3 mb-3" width="40px" />
            <img src="/assets/python.jpg" alt="python" class="img-fluid me-3 mb-3" width="40px" />
            <img src="/assets/php.jpg" alt="php" class="img-fluid me-3 mb-3" width="40px" />
          </div>
          </div>
        </section>
        
        <section id="aboutme">
          <div>
            <h1><b>ABOUT ME</b></h1>
            <p>I am a person who like to learn the new things, especially technology. Let's be friends! 🖤</p>
          </div>
        </section>
  
        <section class="others">
          <div class="con-bio">
            <div class="edu">
              <h1><b>BIODATA</b></h1>
                <div class="item">
                  <P>Name:</P>
                  <h4>SHALMA NUR FADILLA</h4>
                </div>
                <div class="item">
                  <P>Age:</P>
                  <h4>20 Years Old</h4>
                </div>
                <div class="item">
                  <P>Hobby:</P>
                  <h4>Listen to Music</h4>
                </div>
                <div class="item">
                  <P>Address:</P>
                  <h4>Tulungagung, Jawa Timur</h4>
                </div>
            </div>
          </div>
  
          <div class="con-bio">
            <div class="edu">
              <h1><b>EDUCATION</b></h1>
                <div class="item">
                  <h4>SDN 1 BOLOREJO</h4>
                  <P>2011 - 2017</P>
                </div>
                <div class="item">
                  <h4>SMPN 1 KAUMAN</h4>
                  <P>2017 - 2020</P>
                </div>
                <div class="item">
                  <h4>SMAN 1 KAUMAN</h4>
                  <P>2020 - 2021</P>
                </div>
                <div class="item">
                  <h4>UNIVERSITAS BRAWIJAYA</h4>
                  <P>2023 - Now</P>
                </div>
            </div>     
          </div>
        </section> 
  
        <section id="portfolio">
          <h1><b>MY PROJECT</b></h1>
          <P>These are all of my projects that I made during the last 2 semesters. And these use any language also creativity for the design.</P>
          <div class="portfolio-inside">
            <div class="project">
              <img src="/assets/project1.jpg" alt="" width="500px">
              <h3>Web Company</h3>
            </div>
            <div class="project">
              <img src="/assets/project2.jpg" alt="" width="500px">
              <h3>Web Profile</h3>
            </div>
          </div>
          <div class="portfolio-inside">
            <div class="project">
              <img src="/assets/project3.jpg" alt="" width="500px">
              <h3>Web Business</h3>
            </div>
            <div class="project">
              <img src="/assets/project4.jpg" alt="" width="500px">
              <h3>Web Library</h3>
            </div>
          </div>
        </section>
        
        <section id="contact-me">
          <h1><b>CONTACT ME</b></h1>
          <P>Please contact me bellow for more.</P>
          <div class="contact-me">
            <a href="https://github.com/shalmafadilla">
              <img src="/assets/gh.png" alt="github" class="img-fluid me-3 mb-3" width="50px">
            </a>
            <a href="https://www.linkedin.com/in/shalma-nur-fadilla-130392283?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">
              <img src="/assets/in.png" alt="linkedin" class="img-fluid me-3 mb-3" width="50px">
            </a>
            <a href="https://www.instagram.com/shalmanaff?igsh=Mzc2eWxmbjc4MzFt">
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
  
  main {
    background-image: url("bg.png");
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
  }
  
  #main-section {
    display: flex;
    height: 750px;
    justify-content: center;
    align-items: center;
  }
  
  .name {
    font-size: 20px;
  }
  
  .foto {
    width: 40%;
    float: right;
  }
  
  #aboutme {
    font-size: 20px;
    margin: 0 auto;
    margin-top: 0px;
    width: 75%;
    text-align: center;
    border-radius: 30px;
    padding: 20px;
  }
  
  /* section others */
  .others {
    display: flex;
    justify-content: space-between;
    width: 75%;
    border-radius: 30px;
    margin: 0 auto;
    margin-top: 20px;
    padding: 20px;
    gap: 50px;
  }
  
  .con-bio{
    font-size: 20px;
    margin: 0 auto;
    margin-top: 0px;
  
    width: 75%;
    border-radius: 30px;
    padding: 20px;
  
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
    border-radius: 30px;
    padding: 20px;
  
  }
  
  .portfolio-inside{
    display: flex;
    font-size: 20px;
    margin: 0 auto;
    margin-top: 0px;
    width: 75%;
    border-radius: 30px;
    padding: 20px;
  }
  
  .project{
  
    justify-content: space-between;
    width: 50%;
    border-radius: 30px;
    margin-top: 20px;
    padding: 20px;
    gap: 50px;
  }
  
  #contact-me{
    font-size: 20px;
    margin: 0 auto;
    margin-top: 0px;
    width: 75%;
    text-align: center;
    border-radius: 30px;
    padding: 20px;
  
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
    margin-top: 20px;
    padding: 20px 0px;
    color: rgb(131, 131, 131);
  }
  </style>