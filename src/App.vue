<template>

  <TheHeader />
    <!-- Intro Section -->

    <TheIntro />

    <section style="margin-block: 10em;"></section>

    <TheHeader2 />

    <TheIntro2 />
  
    <div class="gradient-500"></div>
  
    <!-- Projects section -->
    <section id="projects" class="projects | padding-block-700">
      <div class="container">
  
        <div class="project-main-headings">
          <h1 class="fs-terciary-heading ff-heading underline fw-semibold capitalize">My work experience</h1>
          <h2 class="fs-fourth-heading ff-heading pt-04">Showcasing my professional projects and contributions</h2>
        </div>
        <div class="solo-projects">
                  <!-- Project Card 1 -->
                  <article class="project-card">
                    <div class="project-card__text">
                      <h3 class="fs-terciary-heading ff-heading fw-semibold text-prusian-blue pt-04 text-center">Red padel Site
                      </h3>
                      <div class="project-card__body">
                        <p class="project-card__description | pt-04">A brief description of the project [Lore dffffffa afdsa
                          asdasdasdas]</p>
                        <div class="project-details | pt-04">
                          <p>My role: Completed last 50% of the development using Vue.js</p>
                          <p>My contributions: Implemented several optimizations, removed Cumulative Layout Shift, solved around
                            60-70
                            bugs, made screens responsive, worked with CSS, images, gradients and layouts.</p>
                        </div>
                      </div>
                      <p class="ff-heading pt-04 underline text-center pt-08">Technologies used:</p>
                      <ul class="project-card__tech-list | pt-04" role="list">
                        <li>Vue.js</li>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>JavaScript</li>
                        <li>TypeScript</li>
                      </ul>
                    </div>
                    <!-- <a class="pt-04 block" href="project-link.com">View Project</a> -->
                    <!-- <div class="project-card__image-container"> -->
                    <img class="project-card__image" src="assets/images/redpadelProyect1.png" alt="Redpadel-Site">
                    <!-- </div> -->
                  </article>
                  <article>
        <section>
          <h2>Introduction</h2>
          <p>This project was a subdomain landing page for a cold cuts brand, with the goal of letting customers know that the company was now selling pork meat cuts as well. The site consisted of a home page, products page, recipes page, and About us page.</p>
        </section>
        <section>
          <h2>Challenge</h2>
          <p>The main challenge was the lack of design resources and input from the company. Starting the project on my own with few restrictions was difficult in terms of execution.</p>
        </section>
        <section>
          <h2>Solution</h2>
          <p>To overcome this challenge, I used my initiative and resourcefulness to find a solution. I googled for UI/UX designers discord channels and used AI to craft a message to bring in designers to join the team. I was able to collaborate with designers from different parts of the world, including California, to improve the end result of the project.</p>
        </section>
        <section>
          <h2>Collaboration</h2>
          <p>Working with designers from different parts of the world was a valuable experience that broadened my perspective and improved the overall outcome of the project. It showed that I have no barriers when it comes to working with people from different backgrounds and locations.</p>
        </section>
        <section>
          <h2>Outcome</h2>
          <p>The project was a success and received positive feedback from customers. I was able to showcase my technical skills in using VueJS 3 and Google Maps API, as well as my ability to work with a team and overcome challenges.</p>
        </section>
        <section>
          <h2>Conclusion</h2>
          <p>This project highlights my initiative, resourcefulness, and ability to work with people from different parts of the world. These skills set me apart as a front-end developer and make me a valuable asset to any team or project.</p>
        </section>
        <section>
          <h2>Project Details</h2>
          <p>The project was developed using VueJS 3 with Vite and utilized the Google Maps API. The API key was secured in a dotenv file.</p>
        </section>
        <section>
          <h2>Screenshots</h2>
          <p>Insert images or videos of key features and the overall design of the project.</p>
        </section>
        <section>
          <h2>Source Code</h2>
          <p>The source code for the project can be found at: <a href="link to source code">link to source code</a></p>
        </section>
  
  
  
  
                  </article>
          <h3 class="fs-fourth-heading">Solo Proyects</h3>
        </div>
  
        <div class="collaborative-projects">
  
          <h3 class="fs-fourth-heading">Collaborative Projects</h3>
  
          <!-- Project Card 1 -->
          <article class="project-card">
            <div class="project-card__text">
              <h3 class="fs-terciary-heading ff-heading fw-semibold text-prusian-blue pt-04 text-center">Red padel Site
              </h3>
              <div class="project-card__body">
                <p class="project-card__description | pt-04">A brief description of the project [Lore dffffffa afdsa
                  asdasdasdas]</p>
                <div class="project-details | pt-04">
                  <p>My role: Completed last 50% of the development using Vue.js</p>
                  <p>My contributions: Implemented several optimizations, removed Cumulative Layout Shift, solved around
                    60-70
                    bugs, made screens responsive, worked with CSS, images, gradients and layouts.</p>
                </div>
              </div>
              <p class="ff-heading pt-04 underline text-center pt-08">Technologies used:</p>
              <ul class="project-card__tech-list | pt-04" role="list">
                <li>Vue.js</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>TypeScript</li>
              </ul>
            </div>
            <!-- <a class="pt-04 block" href="project-link.com">View Project</a> -->
            <!-- <div class="project-card__image-container"> -->
            <img class="project-card__image" src="assets/images/redpadelProyect1.png" alt="Redpadel-Site">
            <!-- </div> -->
          </article>
  
  
          // note: This was my first project using Vue.js, but I was able to quickly learn its functionality and make
          meaningful contributions
  
          <!-- Project Card 2 -->
          <article data-position="inverted" class="project-card | not-first mt-2">
            <div class="project-card__text">
              <h3 class="fs-terciary-heading ff-heading fw-semibold text-prusian-blue pt-04 capitalize text-center">Red
                Padel web app</h3>
              <!-- Proyect card body -->
  
              <div class="project-card__body">
                <p class="project-card__description | pt-04 ">A digital platform for padel players in Miami, featuring
                  ratings, matches, tournaments, and more.</p>
                <div class="project-details | pt-04">
                  <p>My role: Lead developer on a web app that serves hundreds of active users.</p>
                  <p>My contributions: Built the app using Vue.js, MongoDB, and GraphQL. Developed end-to-end tests using
                    Cypress.js, made screens responsive, created CMS sections for client, resolved bugs daily, and
                    participated in agile meetings.</p>
                </div>
              </div>
              <p class="ff-heading pt-04 underline text-center pt-08">Technologies used:</p>
              <ul data-wide="extended" class="project-card__tech-list not-first | pt-04" role="list">
                <li>Vue.js</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>TypeScript</li>
                <li>Cypress.js</li>
                <li>Apollo Client</li>
                <li>MongoDB</li>
                <li>GraphQL</li>
              </ul>
              <a href="project-link.com">View Live Project</a>
            </div>
  
            <!-- <div class="project-card__image-container"> -->
            <img class="project-card__image" src="assets/images/proyectapp.png" alt="Red Padel web app">
            <!-- </div> -->
          </article>
  
          You could add a sentence such as "Implemented API connections using Apollo client to bring club data from
          MongoDB and populate the "clubs" screen, following a Figma design file provided by the designer.
        </div>
      </div>
  
    </section>
  
    <section id="about" class="about">
      <div class="container padding-block-700 flow" style="--flow-spacer:0.4em">
        <h1 class="fs-terciary-heading fw-semibold underline capitalize">about me</h1>
        <h3 class="italic fs-secondary-heading ff-heading text-primary-600 padding-block-400 ">"Be unique, useful, and relentless. The world is yours"</h3>
        <div class="about-content">
          <img src="assets/images/profile-pic.png" alt="Tomas Gil Amoedo" class="about-photo">
          <div class="about-text">
            <ul class="accordion" role="list">
              <li>
                <input type="radio" name="accordion" id="first" checked>
                <label for="first"> Introduction</label>
                <div class="content">
                  <p>
                  <b>Welcome to my portfolio!</b> My name is <b>Tomas Gil amoedo</b> and I am a driven front-end developer with over a year of experience in front-end development"
                  .
                  </p>
                </div>
              </li>
              <li>
                <input type="radio" name="accordion" id="second">
                <label for="second"> Skills</label>
                <div class="content">
                  <p> I specialize in Vue.js and have a strong foundation in HTML, CSS, JavaScript and TypeScript. I am passionate about crafting digital experiences that are not only beautiful but also intuitive and user-friendly.
                  </p>
                </div>
                </li>
                <li>
                  <input type="radio" name="accordion" id="third">
                  <label for="third"> Experience</label>
                  <div class="content">
                    <p>I am experienced in responsive design, cross-browser compatibility, and web performance optimization, ensuring that your website is accessible and fast. I have experience with version control systems and Agile development methodologies, allowing me to manage and organize projects effectively.
                    </p>
                  </div>
                  </li>
              <li>
                <input type="radio" name="accordion" id="fourth">
                <label for="fourth">Interests</label>
                <div class="content">
                  <p>I am always eager to expand my horizons, to push boundaries and to explore new frontiers in the field of web development.
                  </p>
                </div></li>
              <li>
                <input type="radio" name="accordion" id="fifth">
                <label for="fifth"> Contact Information</label>
                <div class="content">
                  <p> I would be thrilled to connect with you, and to learn and grow together. Reach out via email or LinkedIn for job opportunities, freelance work or just to connect. Thank you for visiting my portfolio!
                    </p>
                </div>
                </li>
            </ul>
            
                
              
            <a href="2023frontEnd-resume.pdf" download="2023frontEnd-resume.pdf" data-type="inverted" class="button mt-1">Download Resume</a>
          </div>
        </div>
      </div>
    </section>
  
    <div class="gradient"></div>
    <section class="contact" id="contact">
      <div class="container padding-block-700 flow">
        <h3 class="fs-terciary-heading fw-semibold capitalize underline">contact me</h3>
        <p>Thank you for visiting my portfolio! Please don't hesitate to reach out via email or LinkedIn for job
          opportunities, freelance work or just to connect. I look forward to hearing from you!</p>
        <a class="link | text-neutral-400 fw-semibold block capitalize italic"
          href="mailto:tomasgilamoedo@gmail.com">email me</a>
      </div>
    </section>
  
    <footer class="footer">
      <div class="container padding-block-700 flow">
        <div>
          <h3>Tomas Gil Amoedo - Front-End Developer</h3>
        </div>
        <div class="social-links">
          <ul class="social-links__list">
            <li>
              <a href="https://www.linkedin.com/in/tomas-gil-amoedo/">
                <!-- <xml version="1.0" encoding="utf-8">
                  <svg class="nav-icon" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
                    <path fill="#0A66C2"
                      d="M12.225 12.225h-1.778V9.44c0-.664-.012-1.519-.925-1.519-.926 0-1.068.724-1.068 1.47v2.834H6.676V6.498h1.707v.783h.024c.348-.594.996-.95 1.684-.925 1.802 0 2.135 1.185 2.135 2.728l-.001 3.14zM4.67 5.715a1.037 1.037 0 01-1.032-1.031c0-.566.466-1.032 1.032-1.032.566 0 1.031.466 1.032 1.032 0 .566-.466 1.032-1.032 1.032zm.889 6.51h-1.78V6.498h1.78v5.727zM13.11 2H2.885A.88.88 0 002 2.866v10.268a.88.88 0 00.885.866h10.226a.882.882 0 00.889-.866V2.865a.88.88 0 00-.889-.864z" />
                  </svg>
              </a>
            </li>
            <li>
              <a href="https://github.com/Tommydemian">
                <xml version="1.0" encoding="utf-8">
                  <svg class="nav-icon" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
                    <path fill="#161514" fill-rule="evenodd"
                      d="M8 1C4.133 1 1 4.13 1 7.993c0 3.09 2.006 5.71 4.787 6.635.35.064.478-.152.478-.337 0-.166-.006-.606-.01-1.19-1.947.423-2.357-.937-2.357-.937-.319-.808-.778-1.023-.778-1.023-.635-.434.048-.425.048-.425.703.05 1.073.72 1.073.72.624 1.07 1.638.76 2.037.582.063-.452.244-.76.444-.935-1.554-.176-3.188-.776-3.188-3.456 0-.763.273-1.388.72-1.876-.072-.177-.312-.888.07-1.85 0 0 .586-.189 1.924.716A6.711 6.711 0 018 4.381c.595.003 1.194.08 1.753.236 1.336-.905 1.923-.717 1.923-.717.382.963.142 1.674.07 1.85.448.49.72 1.114.72 1.877 0 2.686-1.638 3.278-3.197 3.45.251.216.475.643.475 1.296 0 .934-.009 1.688-.009 1.918 0 .187.127.404.482.336A6.996 6.996 0 0015 7.993 6.997 6.997 0 008 1z"
                      clip-rule="evenodd" />
                  </svg> -->
              </a>
            </li>
            <li>
              <a href="mailto:tomasgilamoedo@gmail.com">
                <!-- <xml version="1.0" encoding="utf-8">
                  <!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
                  <svg class="nav-icon" version="1.1" id="_x32_" xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512" xml:space="preserve">
                    <style type="text/css">
                      .st0 {
                        fill: #000000;
                      }
                    </style> -->
                    <!-- <g>
                      <path class="st0" d="M510.746,110.361c-2.128-10.754-6.926-20.918-13.926-29.463c-1.422-1.794-2.909-3.39-4.535-5.009
                        c-12.454-12.52-29.778-19.701-47.531-19.701H67.244c-17.951,0-34.834,7-47.539,19.708c-1.608,1.604-3.099,3.216-4.575,5.067
                        c-6.97,8.509-11.747,18.659-13.824,29.428C0.438,114.62,0,119.002,0,123.435v265.137c0,9.224,1.874,18.206,5.589,26.745
                        c3.215,7.583,8.093,14.772,14.112,20.788c1.516,1.509,3.022,2.901,4.63,4.258c12.034,9.966,27.272,15.45,42.913,15.45h377.51
                        c15.742,0,30.965-5.505,42.967-15.56c1.604-1.298,3.091-2.661,4.578-4.148c5.818-5.812,10.442-12.49,13.766-19.854l0.438-1.05
                        c3.646-8.377,5.497-17.33,5.497-26.628V123.435C512,119.06,511.578,114.649,510.746,110.361z M34.823,99.104
                        c0.951-1.392,2.165-2.821,3.714-4.382c7.689-7.685,17.886-11.914,28.706-11.914h377.51c10.915,0,21.115,4.236,28.719,11.929
                        c1.313,1.327,2.567,2.8,3.661,4.272l2.887,3.88l-201.5,175.616c-6.212,5.446-14.21,8.443-22.523,8.443
                        c-8.231,0-16.222-2.99-22.508-8.436L32.19,102.939L34.823,99.104z M26.755,390.913c-0.109-0.722-0.134-1.524-0.134-2.341V128.925
                        l156.37,136.411L28.199,400.297L26.755,390.913z M464.899,423.84c-6.052,3.492-13.022,5.344-20.145,5.344H67.244
                        c-7.127,0-14.094-1.852-20.142-5.344l-6.328-3.668l159.936-139.379l17.528,15.246c10.514,9.128,23.922,14.16,37.761,14.16
                        c13.89,0,27.32-5.032,37.827-14.16l17.521-15.253L471.228,420.18L464.899,423.84z M485.372,388.572
                        c0,0.803-0.015,1.597-0.116,2.304l-1.386,9.472L329.012,265.409l156.36-136.418V388.572z" />
                    </g>
                  </svg> -->
              </a>
            </li>
          </ul>
        </div>
        <p>&copy; 2022 Tomas Gil Amoedo. All rights reserved.</p>
      </div>
    </footer>
  

</template>


<script>
import TheHeader from './components/TheHeader.vue';
import TheHeader2 from './components/TheHeader2.vue';
import TheIntro from './components/TheIntro.vue';
import TheIntro2 from './components/TheIntro2.vue';
export default {
  components: {
    TheHeader,
    TheHeader2,
    TheIntro,
    TheIntro2
  }
}
</script>

<style lang="scss" scoped>
@import '../src/scss/main.scss';

</style>
