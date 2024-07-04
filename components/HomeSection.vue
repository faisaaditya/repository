<template>
  <div class="home">
    <div class="aboutMe">
      <div class="card-body">
        <h2 class="card-title">About Me</h2>
        <p class="text-start">
          Hello! I'm Faisa Aditya, currently pursuing a Bachelor's degree in
          Informatics at AMIKOM Yogyakarta and working as a freelance graphic
          designer. While I haven't yet worked professionally in web
          development, I have skills in design using CorelDRAW, Photoshop, and
          Adobe Illustrator. My web development skills include HTML and CSS at
          an intermediate level, and I'm currently learning JavaScript. I'm also
          exploring frameworks like Bootstrap and Vue.js. I enjoy engaging in
          creative projects and learning new things every day!
        </p>
      </div>
    </div>
    <!-- Home Project status -->
    <div class="row gutters-sm">
      <div class="col-sm-6 mb-3">
        <div class="card h-100">
          <div class="card-body">
            <h6 class="d-flex align-items-center mb-3">Project Status</h6>
            <small>Web Design</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 80%"
                aria-valuenow="80"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>Website Markup</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 72%"
                aria-valuenow="72"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>One Page</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 89%"
                aria-valuenow="89"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>Mobile Template</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 55%"
                aria-valuenow="55"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>Backend API</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 66%"
                aria-valuenow="66"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-sm-6 mb-3">
        <div class="card h-100">
          <div class="card-body">
            <h6 class="d-flex align-items-center mb-3">Project Status</h6>
            <small>Web Design</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 80%"
                aria-valuenow="80"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>Website Markup</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 72%"
                aria-valuenow="72"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>One Page</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 89%"
                aria-valuenow="89"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>Mobile Template</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 55%"
                aria-valuenow="55"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
            <small>Backend API</small>
            <div class="progress mb-3" style="height: 5px">
              <div
                class="progress-bar bg-primary"
                role="progressbar"
                style="width: 66%"
                aria-valuenow="66"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeSection",
};
</script>

<style scoped>
.home {
  padding: 50px 0;
  background: #ffffff;
  margin: 20px 0;
  max-width: 100%;
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
</style>
