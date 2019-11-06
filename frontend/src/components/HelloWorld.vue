<template>
<!-- 这里router-link to="newcontact"会把路由导航到http://localhost:8080/#/newcontact   -->
    <router-link to="newcontact"><h1>{{ msg }}</h1></router-link>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcom'
    }
  }
}
</script>
<style>
h1 {
  font-weight:normal;
}
a {
  color:#42b983;
}
</style>
