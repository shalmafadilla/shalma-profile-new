<template>

    <header>
    <nav class="navbar navbar-expand-lg" style="padding: 25px; background-color: #f5e5ef;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); position: fixed; width: 100%; top: 0; z-index: 1000;">
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
        
          <section class="others">
            <div class="con-bio">
              <div class="edu">
                <h1><b>BIODATA</b></h1>
              </div>
                <table>
                  <tr>
                    <td><b>Name</b></td>
                    <td>:</td>
                    <td>Shalma Nur Fadilla</td>
                  </tr>
                  <tr>
                    <td><b>Age</b></td>
                    <td>:</td>
                    <td>20 Years Old</td>
                  </tr>
                  <tr>
                    <td><b>Hobby</b></td>
                    <td>:</td>
                    <td>Listen to Music</td>
                  </tr>
                  <tr>
                    <td><b>Adderss</b></td>
                    <td>:</td>
                    <td>Tulungagung, Jawa Timur</td>
                  </tr>
                </table>
            </div>
  
            <div class="con-bio">
              <div class="edu">
              <h1><b>EDUCATION</b></h1>
              </div>
                <table>
                  <tr>
                    <tr>
                      <td>UNIVERSITAS BRAWIJAYA</td>
                      <td style="color: rgb(106, 106, 106);">|</td>
                      <td style="color: rgb(106, 106, 106);">2023 - Now</td>
                    </tr>
                    <tr>
                      <td>SMAN 1 KAUMAN</td>
                      <td style="color: rgb(106, 106, 106);">|</td>
                      <td style="color: rgb(106, 106, 106);">2020 - 2023</td>
                    </tr>
                    <tr>
                      <td>SMPN 1 KAUMAN</td>
                      <td style="color: rgb(106, 106, 106);">|</td>
                      <td style="color: rgb(106, 106, 106);">2017 - 2020</td>
                    </tr>
                    <td>SDN 1 BOLOREJO</td>
                    <td style="color: rgb(106, 106, 106);">|</td>
                    <td style="color: rgb(106, 106, 106);">2011 - 2017</td>
                  </tr>
                </table>
              </div>
          </section>
        </section>
  
        <section id="portfolio">
          <h1><b>MY PROJECT</b></h1>
          <P>These are all of my projects that I made during the last 2 semesters. And these use any language also creativity for the design.</P>
          <div class="portfolio-inside">
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project1.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Company</h5>
                <p class="card-text">Project membuat website untuk perusahaan beads, Untuk membranding sebuah perusahaan. Dengan fitur home, about us, dan instagram untuk memudahkan pemesanan melalui website.</p>
              </div>
            </div>
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project2.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Profile</h5>
                <p class="card-text">Project membuat website profil pribadi untuk membuat portofolio dan branding diri sendiri.</p>
              </div>
            </div>
          </div>
          <div class="portfolio-inside">
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project3.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Business</h5>
                <p class="card-text">Project membuat website untuk bisnis laundry. Untuk meemudahkan sebuah perusahaan maupun pelanggan. Dengan banyak fitur yang membantu memanajemen pesanan laundry oleh petugas maupun admin.</p>
              </div>
            </div>
            <div class="card" style="width: 500px;">
              <img class="card-img-top" src="/assets/project4.jpg" alt="" style="border-bottom: 1px solid #c2c2c2">
              <div class="card-body" style="text-align: left;">
                <h5 class="card-title">Web Library</h5>
                <p class="card-text">Project membuat website CRUD menggunakan php. Untuk memanajemen jumlah masing-masing barang berdasarkan kategori.</p>
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