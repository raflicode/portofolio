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
  <div class="container-fluid about" id="about">
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
  <!-- skills -->
  <div class="container-fluid skill py-5" id="skills">
    <div class="container">
      <h2 class="fw-bold display-4 text-center">Skills</h2>
      <!-- Language & Markup -->
      <h4 class="fw-semibold">Languages & Markup</h4>
      <div class="d-flex flex-wrap gap-5 mb-5">
        <img
          src="https://i.pinimg.com/736x/a2/7d/14/a27d14a27b5ef7d35c241d5cc9c1deb4.jpg"
          class="skill-icon"
        />
        <img
          src="https://i.pinimg.com/736x/62/1f/21/621f21fa891b48023ff7c4dff12c7aa0.jpg"
          class="skill-icon"
        />
        <img
          src="https://i.pinimg.com/736x/3d/43/02/3d43022040cff5074ebe1cd483fcdfe4.jpg"
          class="skill-icon"
        />
        <img
          src="https://i.pinimg.com/736x/f2/b5/b9/f2b5b99f75e6f4d1337a9b7afc7fc7c0.jpg"
          class="skill-icon"
        />
      </div>
      <!-- Tools & Framework -->
      <h4 class="fw-semibold">Tools & Framework</h4>
      <div class="d-flex flex-wrap gap-5 mb-5">
        <img
          src="https://i.pinimg.com/736x/b6/e9/14/b6e914bed024672c74364f3664098320.jpg"
          class="skill-icon"
        />
        <img
          src="https://i.pinimg.com/736x/92/d6/60/92d660adb69ff63b4d133cda9592d848.jpg"
          class="skill-icon"
        />
        <img
          src="https://i.pinimg.com/736x/ed/94/e3/ed94e3e6fae5dd09cd8f7652f4a01c3d.jpg"
          class="skill-icon"
        />
        <img
          src="https://i.pinimg.com/736x/11/a7/b5/11a7b5fb70c24e5632f2baccce14603c.jpg"
          class="skill-icon"
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
  background-color: #e2e4e6;
  min-height: 100vh;
  display: flex;
  align-items: center;
}
.skill {
  min-height: 100vh;
  background-color: #f8f9fa;
  display: flex;
  align-items: center;
}
.skill-icon {
  width: 80px;
  height: 80px;
  border: 2px solid #ddd;
  border-radius: 50%;
  object-fit: cover;
  transition: transform 0.3s;
  padding: 5px;
}
.skill-icon:hover {
  transform: scale(1.1);
  border-color: #000;
}
</style>
