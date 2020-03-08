<template>
  <div class="hello">
    <h1>\{{ msg }}</h1>
    <div class="introduction">
      This template is forked from <a href="https://github.com/vuejs-templates/webpack">vuejs-templates/webpack</a>. 
      I add some other tools which will be used most often in my projects, they includes:
      <div class="tool-list">
        <div>1.<a href="https://github.com/axios/axios">axios</a>: it's used to request HTTP API.</div>
        <div>2.<a href="https://vuex.vuejs.org/">vuex</a>: it's a state management pattern + library for Vue.js applications.</div>
        <div>3.<a href="https://element.eleme.cn/#/zh-CN/component/installation">element-ui</a>: it provides many components to build our App UI. </div>
        <div>4.<a href="https://github.com/shunseven/express-proxy-mock">express-proxy-mock</a>: it can help us config HTTP proxy and set API mock data in a single page, After you start your project, visite localhost:8080/config (8080 is your project port), you'll see the page.</div>
      </div>
      <div class="template-use">
        Init a Vue.js project with this template and vue-cli 2.x:
        <div class="cmd">$ vue init shinancao/webpack my-project</div>
      </div>
    </div>
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
.introduction {
  margin: auto 20%;
  text-align: left;
}
.tool-list {
  margin: 10px auto;
}
.tool-list div {
  padding-bottom: 5px;
}
.template-use {
  margin: 10px auto;
}
.cmd {
  background-color: #f6f8fa;
  line-height: 20px;
  padding: 10px;
  margin: 10px auto;
  border-radius: 2px;
}
</style>
