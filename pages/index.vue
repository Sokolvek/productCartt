<template>
  <main>
    <section class="slider">
      <div class="img"></div>
        <article>
          <div class="slide-count">
            <span class="current">{{ this.current }}</span>
            <span class="count-line"></span>
            <span class="total">{{ this.total }}</span>
          </div>
          <div class="slide-title">
            <span>
              <span class="current">J014</span> 
              </span>
            Chair
          </div>
          <div class="description">With the comfort of a lounge chair and the functionality of a dining chair, HAY’s reproduction of Poul M. Voulter’s J110 offers equal measures of strong aesthetics and practicality. Long rods at the back and curved armrests create an inviting expression. Made in lacquered solid beech and available in a variety of colours.</div>
          <a href="#" class="btn">FIND A DEALER</a>
          <div class="dots">
            <span class="dot dot-active"></span>
            <span class="dot"></span>
            <span class="dot"></span>
          </div>
          <div class="side-nav">
            <button class="btn-prev">
              <img src="../assets/imgs/up-arrow.png" alt="">
            </button>
            <button class="btn-next">
              <img src="../assets/imgs/up-arrow.png" alt="">
            </button>

          </div>
          <div class="category">SEATING</div>
        </article>
    </section>
  </main>
</template>

<script>

import ProjectCard from '../components/ProjectCard.vue'

export default {
  name: 'IndexPage',
  data(){
    return{
      current:1,
      total:3

    }
  },
  components:{
    ProjectCard
  }
}
</script>
