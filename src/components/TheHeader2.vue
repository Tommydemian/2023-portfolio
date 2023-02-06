<template>
    <header>
      <div class="container">
        <nav class="primary-navigation">
          <ul class="nav-links" role="list">
            <li><a href="index.html">
                <!-- <xml version="1.0" encoding="utf-8">
                  <svg class="logo" viewBox="0 0 32 32" id="icon" xmlns="http://www.w3.org/2000/svg">
                    <defs>
                      <style>
                        .cls-1 {
                          fill: #000000;
                        }
  
                        .cls-2 {
                          fill: none;
                        }
                      </style>
                    </defs>
                    <title>logo--glassdoor</title>
                    <path class="cls-1"
                      d="M10.8281,28H21.1719a3.43,3.43,0,0,0,3.43-3.43V10.3306h-3.43V24.57H7.3981A3.43,3.43,0,0,0,10.8281,28Z" />
                    <path class="cls-1"
                      d="M21.1719,4H10.8281a3.43,3.43,0,0,0-3.43,3.43v14.24h3.43V7.43H24.6019A3.43,3.43,0,0,0,21.1719,4Z" />
                    <rect id="_Transparent_Rectangle_" class="logo" />
                  </svg> -->
                  <!-- <span>Tomas Gil Amoedo</span> -->
              </a></li>
            <li> <a href="index.html#projects">Projects</a></li>
            <li> <a href="index.html#about">About</a></li>
            <li> <a href="index.html#contact">Contact</a></li>
            <li> <a href="https://www.linkedin.com/in/tomas-gil-amoedo/">
              <Icon class="linkedin-icon" icon="mdi:linkedin" color="#0072b1" />
            </a></li>
            <li> <a href="https://www.linkedin.com/in/tomas-gil-amoedo/">
            <Icon class="github-icon" icon="mdi:github" />
            </a></li>
            <li> <a href="2023frontEnd-resume.pdf" download="2023frontEnd-resume.pdf" class="button inline-flex"> Resume</a></li>
          </ul>
        </nav>
      </div>
    </header>
</template>

<script>
import { Icon } from '@iconify/vue';
export default {
  components: {
    Icon
  },
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>
@import '../scss/variables';
@import '../scss/utility';

header {
  background-color: $neutral-clr-100;
  padding: 1em;
}

.primary-navigation {
  .nav-links{
    display: flex;
    justify-content: space-between;
    align-items: center;

    a {
      text-decoration: none;
      font-family: $ff-heading;
      color: $neutral-clr-800;

      .linkedin-icon, 
      .github-icon {
        width: 2em;
        height: 2em;
      }

    }
  }
}

</style>