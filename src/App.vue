<template>
  <main>
    <MainText></MainText>
    <RatingList></RatingList>
    <CommentBoxes></CommentBoxes>
  </main>
  
</template>

<script>
import MainText from './components/MainText.vue';
import RatingList from './components/RatingList.vue';
import CommentBoxes from './components/CommentBoxes.vue';

export default {
  name: 'App',
  components: {
    MainText,
    RatingList,
    CommentBoxes,
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
