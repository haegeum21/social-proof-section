<template>
  <main>
    <MainText></MainText>
    <RatingList></RatingList>
  </main>
  
</template>

<script>
import MainText from './components/MainText.vue';
import RatingList from './components/RatingList.vue';

export default {
  name: 'App',
  components: {
    MainText,
    RatingList
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
