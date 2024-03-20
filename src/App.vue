<script>
  export default {
    data(){
      return {
        title:'Vite Hello World',
        paragrafo: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Itaque culpa officia ratione sed accusamus nihil vitae iste placeat fugit quasi eum sint pariatur, dolorem obcaecati doloribus, ab exercitationem! Labore, quas.'
      }
    }
  }
  
  
</script>




<template>

  <div>
    <h1> {{ title }}</h1>
    <p> {{ paragrafo }}</p>

  </div>

</template>





<style scoped>

  h1 {
    color: darkorchid;
  }

  p {
    color:cadetblue;
  }



</style>
