<template>
  <div id="app">
    <router-link to="/login"></router-link>
    <router-view></router-view>
  </div>
</template>
<script>
// import Home from './views/Home'
// import Login from './views/Login'
export default {
  data () {
    return {
      name: 'App',
      isLogin: false
    }
  },
  methods: {
  }
  // components: {
  //   Home,
  //   Login
  // }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
