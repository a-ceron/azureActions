<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
  <Contador/>
</template>

<script>
import { Contador } from "../components/Contador.vue";

export default {
  name: 'HomeView',
  components:{
    Contador,
  }
}
</script>

<style>
  div{
    margin-block: 10px;
  }
  .contador{
    font-size: 80px;
  }
  .botones button{
    font-size: 40px;
    width: 100px;
    margin: 0 10px;

  }
  .cuadrado{
    font-size: 25px;
  }
</style>