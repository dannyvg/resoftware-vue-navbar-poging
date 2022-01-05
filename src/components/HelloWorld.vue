<template>
<div class="menu">
  <h2 v-for="name in names" :key="name">{{ name }}</h2>
</div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      names: ['Home', 'Diensten', 'Werken bij', 'Vacature', 'Trends and insights', 'Contact']
    }
  }
}
</script>

<style scoped>
.menu{
margin: 0;
width: 100%;
height: 50px;
border-bottom: solid black 1px;
}

h2{
  float: left;
  display: inline;
  padding-right: 30px;
}
</style>
