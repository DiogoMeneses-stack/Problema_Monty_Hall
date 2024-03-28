<template>
  <div id="app">
    <h1>Problema de Monty hall</h1>
    <GiftDisplay />
  </div>
</template>

<script>
import GiftDisplay from './components/Gift.vue'

export default {
    name:'App',
    components:{GiftDisplay}
}
</script>

<style>

*{
  font-family: 'Montserrat', sans-serif;
  box-sizing: border-box;
}

body{
  color: white;
  background: linear-gradient(to right, rgb(21, 153, 87), rgb(21, 87, 153));
}

#app{
  display: flex;
  flex-direction: column;
  align-items: center;
}

#app h1{
  border: 1px solid #000;
  background-color: #0004;
  padding: 20px;
  margin-bottom: 60px;
}

</style>