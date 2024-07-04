<template>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css"
  />
  <section class="hero">
    <div class="container">
      <header class="header-section text-center">
        <nav class="navbar navbar-expand-lg navbar-light bg-white rounded">
          <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse justify-content-center"
            id="navbarNav"
          >
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" @click="activeSection = 'home'">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click="activeSection = 'resume'">Resume</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" @click="activeSection = 'projects'"
                  >Projects</a
                >
              </li>
              <li class="nav-item" @click="activeSection = 'contacts'">
                <a class="nav-link">Contact</a>
              </li>
            </ul>
          </div>
        </nav>
      </header>

      <!-- Profile  -->
      <div class="main-body mt-3">
        <div class="row gutters-sm">
          <div class="col-md-4 mb-3">
            <!-- CARD Profile 1 -->
            <div class="card">
              <div class="card-body">
                <div
                  class="d-flex flex-column align-items-center text-center rounded-4"
                >
                  <img
                    src="../assets/images/fotoProfile.jpg"
                    alt="Admin"
                    class="rounded-circle"
                    width="150"
                  />
                  <div class="mt-3">
                    <h4>Faisa Aditya Athallah</h4>
                    <p class="text-secondary mb-1">
                      Web Developer - Graphics Designer
                    </p>
                    <p class="text-muted font-size-sm">
                      Sleman, D.I. Yogyakarta
                    </p>
                    <button class="btn btn-primary">Download CV</button>
                  </div>
                </div>
              </div>
            </div>

            <!-- Profile SOSMED -->

            <div class="card mt-3">
              <ul class="list-group list-group-flush">
                <li
                  class="list-group-item d-flex justify-content-between align-items-center flex-wrap"
                >
                  <h6 class="mb-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-globe mr-2 icon-inline"
                    >
                      <circle cx="12" cy="12" r="10"></circle>
                      <line x1="2" y1="12" x2="22" y2="12"></line>
                      <path
                        d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"
                      ></path></svg
                    >Website
                  </h6>
                  <span class="text-secondary">Upcoming</span>
                </li>
                <li
                  class="list-group-item d-flex justify-content-between align-items-center flex-wrap"
                >
                  <h6 class="mb-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-github mr-2 icon-inline"
                    >
                      <path
                        d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                      ></path></svg
                    >Github
                  </h6>
                  <span class="text-secondary">faisaaditya</span>
                </li>
                <li
                  class="list-group-item d-flex justify-content-between align-items-center flex-wrap"
                >
                  <h6 class="mb-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-twitter mr-2 icon-inline text-info"
                    >
                      <path
                        d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
                      ></path></svg
                    >Twitter
                  </h6>
                  <span class="text-secondary">@adityaAtha</span>
                </li>
                <li
                  class="list-group-item d-flex justify-content-between align-items-center flex-wrap"
                >
                  <h6 class="mb-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-instagram mr-2 icon-inline text-danger"
                    >
                      <rect
                        x="2"
                        y="2"
                        width="20"
                        height="20"
                        rx="5"
                        ry="5"
                      ></rect>
                      <path
                        d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"
                      ></path>
                      <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg
                    >Instagram
                  </h6>
                  <span class="text-secondary">faisaaditya</span>
                </li>
                <li
                  class="list-group-item d-flex justify-content-between align-items-center flex-wrap"
                >
                  <h6 class="mb-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-facebook mr-2 icon-inline text-primary"
                    >
                      <path
                        d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
                      ></path></svg
                    >Facebook
                  </h6>
                  <span class="text-secondary">Faisa Aditya</span>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-md-8 mb-3">
            <component :is="getCurrentSection" />
          </div>

          <!-- Component Menu-->
        </div>
      </div>
    </div>
    <div class="container my-5">
      <div class="text-center p-3" style="background-color: tr">
    © 2024 Copyright :
    <a class="text-white" >Faisaaditya</a>
  </div>
<footer class="bg-dark text-center text-white">
  </footer>
  </div>
  </section>
</template>

<script>
import HomeSection from "./HomeSection.vue";
import ResumeSection from "./ResumeSection.vue";
import ProjectsSection from "./ProjectsSection.vue";
import ContactSection from "./ContactSection.vue";

export default {
  name: "HeroSection",
  components: {
    HomeSection,
    ResumeSection,
    ProjectsSection,
    ContactSection,
  },
  data() {
    return {
      activeSection: "home",
    };
  },
  computed: {
    getCurrentSection() {
      switch (this.activeSection) {
        case "resume":
          return "ResumeSection";
        case "projects":
          return "ProjectsSection";
        case "contacts":
          return "ContactSection";
        default:
          return "HomeSection";
      }
    },
  },
};
</script>

<style scoped>
.hero {
  text-align: center;
  padding: 100px 0;
  background: #ddd9d9;
}

.navbar {
  padding: 5px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
.card {
  background: #ffffff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
</style>
