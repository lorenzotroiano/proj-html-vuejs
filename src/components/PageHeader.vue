<script>

import SingleLink from './SingleLink.vue';

export default {

  name: "PageHeader",

  components: {
    SingleLink
  },

  data() {
    return {
      links: [
        {
          link: "Home"
        },
        {
          link: "Coursers"
        },
        {
          link: "Instructors"
        },
        {
          link: "Events"
        },
        {
          link: "Pages"
        },
        {
          link: "Elements"
        },

      ]
    }
  }

}

</script>

<template>
  <header>
    <div class="background-filter"></div>
    <nav>
      <div>
        <img src="../../public/img/logo-light.png" alt="">
      </div>

      <div class="link">
        <SingleLink v-for="link in links" :details="link" />
      </div>


      <div class="icons">
        <i class="fa-solid fa-magnifying-glass"></i>
        <i class="fa-solid fa-bag-shopping"></i>
        <i class="fa-solid fa-bars"></i>
      </div>

    </nav>

    <section id="hero">
      <h1>Contemporary Ideas</h1>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta ducimus ullam aspernatur odit eos ratione quae
        voluptatem. Exercitationem culpa repellat, facere quam alias ut eius dolorum corporis placeat maxime voluptatum!
      </p>
      <button><a href="#">Register Now</a></button>
    </section>


  </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;



header {
  position: relative;

  .background-filter {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url(../../public/img/course-9-f-img.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 0%;
    filter: brightness(70%);
    /* Imposta il filtro desiderato */
    z-index: -1;
  }



  height: 650px;

  nav {
    color: white;
    width: 95%;
    margin: 0 auto;
    padding: 40px;

    display: flex;
    justify-content: space-between;
    align-items: center;

    img {
      width: 200px;

    }


    .link {
      display: flex;
      gap: 30px;
    }

    .icons {
      display: flex;
      gap: 35px;
    }

  }


}




#hero {

  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

  // width: 60%;
  // margin: 0 auto;
  text-align: center;
  line-height: 30px;

  // padding: 10px;


  h1 {
    font-size: 70px;
    color: white;
  }

  p {
    margin: 20px 0;
    color: white;
  }

  button {
    border: 0px;
    background-color: $colorePrimario;
    padding: 20px;
    width: 200px;


    a {
      text-decoration: none;
      color: white;
      padding: 20px;
      text-transform: uppercase;
    }
  }
}
</style>
