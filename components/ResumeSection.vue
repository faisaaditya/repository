<template>
  <div class="resume">
    <h2>Resume</h2>
    <div class="container">
      <main class="row">
        <!-- Education Section Starts -->
        <section class="col">
          <header class="title">
            <h2>EDUCATION</h2>
          </header>
          <div class="contents">
            <div
              class="box"
              v-for="(education, index) in educationData"
              :key="index"
            >
              <h4>{{ education.years }}</h4>
              <h3>{{ education.degree }}</h3>
              <p>{{ education.description }}</p>
            </div>
          </div>
        </section>
        

        <!-- Experience Section -->
        <section class="col">
          <header class="title">
            <h2>EXPERIENCE</h2>
          </header>
          <div class="contents">
            <div
              class="box"
              v-for="(experience, index) in experienceData"
              :key="index"
            >
              <h4>{{ experience.years }}</h4>
              <h3>{{ experience.position }}</h3>
              <p>{{ experience.description }}</p>
            </div>
          </div>
        </section>
      
      </main>
    </div>
  </div>
</template>

<script>
export default {
  name: "ResumeSection",
  data() {
    return {
      educationData: [
        {
          years: "2018 - 2021",
          degree: "High School Degree",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          years: "2022 - Present",
          degree: "Bachelor's Degree",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
       
      ],
      experienceData: [
        {
          years: "2018 - 2022",
          position: "UI/UX Designer",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          years: "2018 - 2022",
          position: "Full-Stack Developer",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
        {
          years: "2018 - 2022",
          position: "Frontend Developer",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
        },
      ],
    };
  },
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.resume {
  padding: 50px 0;
  background: #ffffff;
  margin: 20px 0;
  max-width: 100%;
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.container {
  width: 100%;
  padding: 35px 10%;
}

main.row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-column-gap: 20px;
}

.col header.title {
  font-family: helvetica;
  color: #1a73e8; 
  padding: 0px 0px 20px 30px;
}

.col .contents {
  padding: 0px 30px;
  border-left: 2px solid #bababa;
}

.col .contents .box {
  position: relative;
  padding: 20px;
  border: 1px solid #eaeaea;
  background-color: #ffffff;
  cursor: pointer;
  transition: all 0.4s;
  margin-bottom: 20px;
}

.col .contents .box:hover {
  box-shadow: 0px 3px 12px 0px #ccc;
  border: 1px solid transparent;
}

.col .contents .box::before {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  border-radius: 50%;
  right: calc(100% + 22px);
  top: 0;
  background-color: #1a73e8; 
  border: 2px solid white;
}

.box h4 {
  position: relative;
  color: #1a73e8; 
}

.box h3 {
  font-size: 16px; 
  padding: 8px 0px 6px; 
  font-family: helvetica;
  color: #444;
}

.box p {
  line-height: 1.2;
  color: #666;
  font-size: 14px; 
}

@media (max-width: 768px) {
  main.row {
    grid-template-columns: 1fr;
  }
  .row .col:nth-child(2) {
    margin-top: 30px;
  }
}
</style>
