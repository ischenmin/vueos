<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
        </a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
        >
          Forum
        </a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
        >
          Docs for This Template
        </a>
      </li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
<!--  <ul id="nav">
    <li v-for="item in items">
      {{ item.message }}
    </li>
  </ul>-->
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
#nav {
  position:relative;
  box-sizing: border-box;
  min-height: 1rem;
  margin-bottom:0.22rem;
  width:100%;
  height: 9.08rem;
  display: -webkit-flex; /* Safari */
  display: flex;
  flex-flow: row wrap;
  align-content:space-between;
  margin-top:0.5rem;
  padding:0 3%;
}
#nav li {
  display:black;
  box-sizing: border-box;
  height: 2.77rem;
  flex: 1 0 20%;
  background:url();
  background-position: center;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  border-radius:0.2rem;
}
#nav li:nth-child(odd){margin-right:3%;}
#nav li.active {
  -webkit-box-shadow:0 0 5px 3px #fa2f50;
  -moz-box-shadow:0 0 5px 3px #fa2f50;
  box-shadow:0 0 5px 3px #fa2f50;

}
</style>
