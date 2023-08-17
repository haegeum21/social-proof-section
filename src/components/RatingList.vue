<template>
    <section class="rating">
        <div v-for="(rate, index) in rates" :key="rate" :class=retStr(index)>
            <div class="stars">
                <img src="../../images/icon-star.svg" alt=""><img src="../../images/icon-star.svg" alt=""><img src="../../images/icon-star.svg" alt=""><img src="../../images/icon-star.svg" alt=""><img src="../../images/icon-star.svg" alt="">
            </div>
            <h2>{{ rate }}</h2>
        </div>
    </section>
</template>

<script>

export default {
  name: 'RatingList',
  data(){
    return{
        rates: ["Rated 5 Stars in Reviews", "Rated 5 Stars in Report Guru", "Rated 5 Stars in BestTech"],
    }
  },
  methods:{
    retStr(n){
        if(n==0){
            return "rates one";
        } else if(n == 1){
            return "rates two";
        }

        return "rates three";
    }
  }
}
</script>