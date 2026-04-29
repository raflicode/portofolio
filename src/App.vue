<template>
  <!-- navbar -->
  <nav
    class="navbar navbar-expand-lg navbar-dark p-2 bg-dark rounded-bottom shadow-lg fixed-top"
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
            <a class="nav-link" href="#certificate">Certificate</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- hero section -->
  <div class="container-fluid banner align-content-center" id="home">
    <div class="container text-center">
      <img class="mb-5" src="src/assets/logo.png" width="100px" alt="logo" />
      <h4 class="display-6 fw-semibold">Welcome to my Portfolio</h4>
      <h3 class="display-1 fw-bold">Rafli Aulia Al Giffari</h3>
      <h5>
        I'm a passionate Web Developer who loves turning coffee into code.
      </h5>
    </div>
  </div>
  
  <!-- about -->
  <div class="container-fluid about align-content-center pt-5 pb-5" id="about" data-aos="fade-up">
    <div class="container">
      <h2 class="display-3 text-center fw-bold">
        About <span class="text-dark-emphasis">Me</span>
      </h2>
      <p class="text-center mb-5">
        Just someone who's into web development and modern technology.
      </p>
      <div class="d-flex flex-column flex-md-row align-items-center pt-5 gap-4">
        <div class="col-md-8"data-aos="fade-right">
          <p>
            Hey, I’m Rafli Aulia Al Giffari, a Software Engineering student
            who’s super passionate about learning new things and diving deep
            into coding. My dream is to become a skilled fullstack developer,
            mastering both front-end and back-end, so I can build cool apps that
            actually help people. To me, coding isn’t just about writing lines
            of code — it’s about constantly growing and not being afraid to
            fail. I love exploring the latest tech and working on projects that
            make a difference, especially those related to mental health.
            Basically, I wanna be a developer who’s not just smart but also fun
            to work with!
          </p>
        </div>
        <img
          src="src/assets/gb.jpg"
          class="col-md-3 float-md-end mt-auto crop-img rounded-circle"
          height="260" data-aos="fade-left"
        />
      </div>
    </div>
  </div>
  <!-- skills -->
  <div class="container-fluid skill py-5" id="skills" data-aos="fade-up">
    <div class="container">
      <h2 class="fw-bold display-4 text-center">Skills</h2>
      <!-- Language & Markup -->
      <h4 class="fw-semibold"data-aos="fade-right">Languages & Markup</h4>
      <div
        class="d-flex flex-wrap justify-content-center justify-content-md-start gap-5 mb-5"
        data-aos="fade-right"
      >
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
      <h4 class="fw-semibold"data-aos="fade-right">Tools & Framework</h4>
      <div
        class="d-flex flex-wrap justify-content-center justify-content-md-start gap-5 mb-5"
        data-aos="fade-right"
      >
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

  <!-- project -->
<div class="container-fluid project py-5" id="project" data-aos="fade-up">
  <div class="container text-center">
    <h2 class="fw-bold display-4 mb-2">My Project</h2>
    <p class="text-muted mb-5">A collection of projects I've worked on.</p>

    <div class="row justify-content-center gap-4">

      <!-- Card Project 1 -->
      <div class="col-md-3 col-sm-6" data-aos="fade-up">
        <div class="work-card shadow-lg border-0 rounded-4 overflow-hidden text-start">
          <img src="../src/assets/dumy_project.jpg" class="work-img" alt="Domposer" />
          <div class="p-3">
            <h5 class="fw-bold">Dummy</h5>
            <p class="text-muted small">
              Domposer is a website builder that helps users easily build and manage projects with an intuitive UI.
            </p>
          </div>
        </div>
      </div>

      <!-- Card Project 2 -->
      <div class="col-md-3 col-sm-6" data-aos="fade-up" data-aos-delay="100">
        <div class="work-card shadow-lg border-0 rounded-4 overflow-hidden text-start">
          <img src="../src/assets/dumy_project.jpg" class="work-img" alt="Bay.js" />
          <div class="p-3">
            <h5 class="fw-bold">Dummy</h5>
            <p class="text-muted small">
              A lightweight library for web components. No dependencies, fast, and easy to integrate.
            </p>
          </div>
        </div>
      </div>

      <!-- Card Project 3 -->
      <div class="col-md-3 col-sm-6" data-aos="fade-up" data-aos-delay="200">
        <div class="work-card shadow-lg border-0 rounded-4 overflow-hidden text-start">
          <img src="../src/assets/dumy_project.jpg" class="work-img" alt="Cookiemunch" />
          <div class="p-3">
            <h5 class="fw-bold">Dumy</h5>
            <p class="text-muted small">
              A customizable cookie plugin made with vanilla JS and SCSS to manage cookie preferences.
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>
</div>

<!-- certificate -->
<div class="container-fluid certificate py-5" id="certificate" data-aos="fade-up">
  <div class="container text-center">
    <h2 class="fw-bold display-4 mb-5">Certificates</h2>

    <div class="row justify-content-center gap-4">
      <!-- Certificate 1 -->
      <div class="col-md-4 col-sm-6" data-aos="fade-up">
        <div class="card border-0 shadow-lg rounded-4 overflow-hidden">
          <img src="../src/assets/sertifikat1.jpg" class="card-img-top" alt="Certificate 1">
          <div class="card-body bg-dark text-light">
            <h5 class="fw-semibold mb-0">UI/UX DESIGN WITH FIGMA</h5>
          </div>
        </div>
      </div>

      <!-- Certificate 2 -->
      <div class="col-md-4 col-sm-6" data-aos="fade-up" data-aos-delay="100">
        <div class="card border-0 shadow-lg rounded-4 overflow-hidden">
          <img src="../src/assets/dumy_project.jpg" class="card-img-top" alt="Certificate 2">
          <div class="card-body bg-dark text-light">
            <h5 class="fw-semibold mb-0">Dummy</h5>
          </div>
        </div>
      </div>

      <!-- Certificate 3 -->
      <div class="col-md-4 col-sm-6" data-aos="fade-up" data-aos-delay="200">
        <div class="card border-0 shadow-lg rounded-4 overflow-hidden">
          <img src="../src/assets/dumy_project.jpg" class="card-img-top" alt="Certificate 3">
          <div class="card-body bg-dark text-light">
            <h5 class="fw-semibold mb-0">Dummy</h5>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- contact -->
<div class="container-fluid contact py-5" id="contact" data-aos="fade-up">
  <div class="container">
    <h2 class="fw-bold display-4 text-center mb-4">Contact</h2>
    <p class="text-center mb-5">
      Feel free to reach out — I’d love to connect!
    </p>
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card p-4 shadow-lg border-0">
          <form id="contact-form">
            <div class="mb-3">
              <label class="form-label fw-semibold">Name</label>
              <input
                type="text"
                class="form-control"
                name="name"
                placeholder="Your name"
                required
              />
            </div>
            <div class="mb-3">
              <label class="form-label fw-semibold">Email</label>
              <input
                type="email"
                class="form-control"
                name="email"
                placeholder="Your email"
                required
              />
            </div>
            <div class="mb-3">
              <label class="form-label fw-semibold">Message</label>
              <textarea
                class="form-control"
                name="message"
                rows="4"
                placeholder="Write your message here..."
                required
              ></textarea>
            </div>
            <button type="submit" class="btn btn-dark w-100 fw-semibold">
              Send Message
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</div>


</template>

<style>
.banner {
  background-image: url("https://images.unsplash.com/photo-1689691849957-1ce9f9315e91?q=80&w=1631&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding: 11%;
  color: #ffff;
  min-height: 100vh;
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

.project {
  min-height: 100vh;
  background-color: #f9fafc;
  display: flex;
  align-items: center;
}

.work-card {
  background: #fff;
  transition: all 0.3s ease;
  border: 1px solid #e6e6e6;
}

.work-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
}

.work-img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-bottom: 1px solid #eee;
}

.work-card h5 {
  color: #111;
}

.work-card p {
  line-height: 1.4;
}

.certificate {
  min-height: 100vh;
  background-color: #e2e4e6;
  display: flex;
  align-items: center;
}

.certificate .card {
  cursor: pointer;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.certificate .card img {
  width: 100%;
  height: 220px;
  object-fit: scale-down;
  background-color: #fff;
}

.certificate .card:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
}

.contact {
  background-color: #f8f9fa;
  min-height: 100vh;
  display: flex;
  align-items: center;
}

.contact .card {
  border-radius: 12px;
  background-color: #fff;
}

.contact .btn:hover {
  transform: scale(1.03);
  transition: 0.3s ease;
}

</style>

<script>
import AOS from "aos";
import "aos/dist/aos.css";

export default {
  name: "App",
  mounted() {
    AOS.init({
      duration: 1000,
      once: true,
    });
  },
};

import emailjs from "emailjs-com";
import { ref } from "vue";

const name = ref("");
const email = ref("");
const message = ref("");

// ganti ID-nya pake punyamu
const SERVICE_ID = "service_8qtezzh";
const TEMPLATE_ID = "template_5chl70x";
const PUBLIC_KEY = "CRtbCqZ__KHs_rNd7";

const sendEmail = () => {
  emailjs
    .send(SERVICE_ID, TEMPLATE_ID, {
      name: name.value,
      email: email.value,
      message: message.value,
    }, PUBLIC_KEY)
    .then(
      (response) => {
        alert("Pesan berhasil dikirim");
        console.log("SUCCESS!", response.status, response.text);
        name.value = "";
        email.value = "";
        message.value = "";
      },
      (error) => {
        alert("Gagal mengirim pesan");
        console.error("FAILED...", error);
      }
    );
};

</script>
