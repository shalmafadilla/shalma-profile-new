<template>
  <header>
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Web Profile Page</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
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
    <!-- Konten lainnya -->
  </main>
</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
/* General CSS */
.navbar {
  padding: 25px;
  background-color: #f5e5ef;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
}

.navbar-nav {
  height: 50px;
  align-items: center;
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

.foto {
  width: 40%;
  float: right;
}

/* Media queries for mobile */
@media (max-width: 768px) {
  .navbar {
    padding: 10px;
  }

  .navbar-nav {
    flex-direction: column;
    text-align: center;
  }

  .foto {
    width: 100%;
    float: none;
    text-align: center;
  }

  #main-section {
    flex-direction: column;
    height: auto;
    text-align: center;
  }

  .others {
    flex-direction: column;
    width: 90%;
  }

  .portfolio-inside {
    flex-direction: column;
    width: 90%;
    gap: 20px;
  }

  .project {
    width: 100%;
  }

  footer {
    padding: 10px;
  }
}
</style>
