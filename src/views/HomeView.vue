<template>
  <div class="home">
    <img alt="Vue logo" src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.istockphoto.com%2Fphotos%2Fbiker&psig=AOvVaw2iNL-cBiGGRnPgzfWltjhB&ust=1671375833926000&source=images&cd=vfe&ved=0CA8QjRxqFwoTCKDYk6j2gPwCFQAAAAAdAAAAABAE/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
<style scoped>
h3 {
  margin: 40px 0 0;
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

