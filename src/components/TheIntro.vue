<template>
    <section class=" intro | padding-block-600" id="intro">
        <div class=" intro-content flow container">
          <p class="name | ff-heading">
            Hy, my name is <span class="fs-intro-heading block">Tomas Gil Amoedo</span>
          </p>
          <h2 class="fw-bold text-primary-500 padding-top-100 ">I develop for the web
          </h2>
          <p>
            I'm a [tech stack and technical specifications]
          </p>
          <p>
            Currently I'm working as a Front-end Developer in
            <a class="work-link | text-neutral-400 fw-semibold italic" href="https://www.redpadel.com/">Redpadel</a>.
          </p>
        </div>
      </section>
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

.intro-content {
  font-family: $ff-alternate-heading;
  background: $neutral-clr-200;

  p {
    font-size: 1.3rem;
  }

  & > .name {
    font-size: 1;
    letter-spacing: .1em;
  }
  .fs-intro-heading {
    font-weight: bold;
    font-size: 4rem;
    color: $accent-clr-400;
  }
  h2 {
    font-size: 4rem;
    font-weight: 600;
  }
  a {
    text-decoration: none;
    color: $accent-clr-600;
  }
}

</style>