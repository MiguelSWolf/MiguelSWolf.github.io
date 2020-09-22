<template>
  <main class="main about">
    <div class="background has-letters">
      <h2><span>About</span><span> me</span></h2>
    </div>
    <div class="container">
      <div class="box box-about">
        <h2 class="box-title">Hello There</h2>
        <div>
          <div class="box-content">
            <h3 class="content">
              My name is Miguel Wolf, and I'm a front-end developer based in
              Brazil. I've been working in this area for almost 10 years.
            </h3>
          </div>
        </div>
      </div>
    </div>
    <section class="main technology">
      <div class="container">
        <div class="list">
          <h2 class="list-title">
            Technology
          </h2>
          <div class="items">
            <div class="group">
              <p class="item is-big">VueJS</p>
              <p class="item">Vuex</p>
              <p class="item">Vue Resources</p>
              <p class="item">Axios</p>
              <p class="item">Next</p>
              <p class="item">Nuxt</p>
            </div>

            <div class="group">
              <p class="item is-big">PHP</p>
              <p class="item">Laravel</p>
              <p class="item">CodeIgniter</p>
              <p class="item">Wordpress</p>
            </div>

            <div class="group">
              <p class="item is-big">Web</p>
              <p class="item">HTML5</p>
              <p class="item">CSS3</p>
              <p class="item">SCSS</p>
              <p class="item">Bulma.io</p>
              <p class="item">Bootstrap</p>
              <p class="item">JS Vanilla</p>
              <p class="item">Gulp</p>
              <p class="item">Webpack</p>
            </div>

            <div class="group">
              <p class="item is-big">DB</p>
              <p class="item">MySQL</p>
              <p class="item">MariaDB</p>
              <p class="item">SQLite</p>
              <p class="item">PostgreSQL</p>
              <p class="item">Firebase</p>
            </div>

            <div class="group">
              <p class="item is-big">AWS</p>
              <p class="item">Amazon SES</p>
              <p class="item">Amazon EC2</p>
              <p class="item">Amazon E3</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
<style lang="scss" scope>
.background.has-letters,
.main {
  min-height: $height;
}
</style>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
