<template>
  <div id="app">
    <!-- <router-view/> -->
    <MyName :name="name"/>
  </div>
</template>

<script>
import MyName from "@/components/MyName"
export default {
  components: {
    MyName
  },
  data() {
        return {           
            name: "MICHEAL ADISA"
        }
    }
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
