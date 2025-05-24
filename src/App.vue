<template>
  <!-- navbar -->
  <nav
    class="navbar navbar-expand-lg navbar-dark p-2 bg-dark rounded shadow-lg fixed-top"
  >
    <div class="container-fluid pe-4 ps-4">
      <a class="navbar-brand d-flex align-items-center gap-2" href="/">
        <img
          src="src/assets/logo.png"
          width="38px"
          alt="logo"
          class="d-inline-block"
        />
        <span class="fw-bold fs-5 text-light">Myportofolio.</span>
      </a>
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
            <a class="nav-link active" aria-current="page" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#project">Project</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#project">Certificate</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- hero section -->
  <div class="container-fluid banner" id="home">
    <div class="container text-center">
      <img class="mb-5" src="src/assets/logo.png" width="100px" alt="logo" />
      <h4 class="display-6 fw-semibold">Welcome to my Portfolio</h4>
      <h3 class="display-1 fw-bold">Rafli Aulia Al Giffari</h3>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsa dolorum
        reiciendis esse recusandae incidunt numquam beatae consequatur nostrum
        eos, repellat sapiente, voluptas enim maxime quos fugit exercitationem
        aliquid, unde optio.
      </p>
    </div>
  </div>
  <!-- about -->
  <div class="container-fluid bg-light-subtle about" id="about">
    <div class="container">
      <h2 class="display-3 text-center fw-bold">
        About <span class="text-dark-emphasis">Me</span>
      </h2>
      <p class="text-center mb-5">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos molestias
        obcaecati est ex mollitia dolore.
      </p>
      <div class="d-flex flex-column flex-md-row align-items-center pt-5 gap-4">
        <div class="col-md-8">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas quasi
            dignissimos suscipit voluptates rerum harum. Lorem, ipsum dolor sit
            amet consectetur adipisicing elit. Tempora dolore aperiam
            repudiandae minima vitae porro veritatis quas ducimus aliquam
            excepturi rem optio quasi vel asperiores magni velit suscipit,
            perspiciatis reprehenderit corporis molestiae molestias voluptate
            soluta provident mollitia. Eos maiores voluptate doloribus culpa
            quae odio sapiente! Ipsam repellat a reiciendis quidem?
          </p>
        </div>
        <img
          src="src/assets/gb.jpg"
          class="col-md-3 float-md-end mt-auto crop-img rounded-circle"
          height="260"
        />
      </div>
    </div>
  </div>
</template>
<style>
.banner {
  background-image: url("https://images.unsplash.com/photo-1632334804712-d8046e6f0ce2?q=80&w=1631&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding: 11%;
  color: #ffff;
}
.about {
  min-height: 100vh;
  display: flex;
  align-items: center;
}
</style>
