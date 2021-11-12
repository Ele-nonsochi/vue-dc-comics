<template>
<main class="container_main">
  <div class="container">
  <div class="cards_container">
  <Card 
  v-for="(card, i) in cardsArray" :key="i"
  :thumbnail="card.thumb"
  :title="card.series"
  />
  </div>
  </div>
</main>
</template>

<script>
import JsonData from "@/assets/datajsn/dc-comics.json";
import Card from "./Card.vue";

 export default {
     name: "PageMain",
     components:{
       Card,
     },
     data(){
       return{
         cardsArray: JsonData,
       };
     },
 };
</script>