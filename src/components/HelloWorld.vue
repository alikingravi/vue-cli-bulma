<template>
  <div class="hello">
      <h1>{{ msg }}</h1>
      <h2>Essential Links</h2>
      <ul>
        <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
        <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
        <li><a href="https://chat.vuejs.org" target="_blank">Community Chat</a></li>
        <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
        <br>
        <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
      </ul>
      <h2>Ecosystem</h2>
      <ul>
        <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
        <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
        <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
        <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
      </ul>

      <div class="container">

        <div class="divider"></div>

        <!-- Hero -->
        <section class="hero is-primary">
          <div class="hero-body">
            <div class="container">
              <h1 class="title">
                Primary title
              </h1>
              <h2 class="subtitle">
                Primary subtitle
              </h2>
            </div>
          </div>
        </section>

        <div class="divider"></div>

        <!-- Columns -->
        <h1>COLUMNS</h1>
        <div class="columns">
          <div class="column">
            <div class="box">
                First column
            </div>
          </div>
          <div class="column">
              <div class="box">
                Second column
              </div>
          </div>
          <div class="column">
            <div class="box">
              Third column
            </div>
          </div>
          <div class="column">
            <div class="box">
              Fourth column
            </div>
          </div>
        </div>

        <div class="divider"></div>

        <!-- Tiles -->
        <div class="tile is-ancestor">
          <div class="tile is-vertical is-8">
            <div class="tile">
              <div class="tile is-parent is-vertical">
                <article class="tile is-child notification is-primary">
                  <p class="title">Vertical...</p>
                  <p class="subtitle">Top tile</p>
                </article>
                <article class="tile is-child notification is-warning">
                  <p class="title">...tiles</p>
                  <p class="subtitle">Bottom tile</p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child notification is-info">
                  <p class="title">Middle tile</p>
                  <p class="subtitle">With an image</p>
                  <figure class="image is-4by3">
                    <img src="https://bulma.io/images/placeholders/640x480.png">
                  </figure>
                </article>
              </div>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification is-danger">
                <p class="title">Wide tile</p>
                <p class="subtitle">Aligned with the right tile</p>
                <div class="content">
                  <!-- Content -->
                </div>
              </article>
            </div>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child notification is-success">
              <div class="content">
                <p class="title">Tall tile</p>
                <p class="subtitle">With even more content</p>
                <div class="content">
                  <!-- Content -->
                </div>
              </div>
            </article>
          </div>
        </div>
      </div>

      <div class="divider"></div>
      
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Vue with Bulma CSS!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import '../assets/sass/app.scss';

.divider {
  margin-top: 20px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
