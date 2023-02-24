<template>
<Batata />
<Batata />
<Batata /> 
ola usa 
<input/>
<input/>
<input/>

<Texto />
</template>

<script>
import Batata from './components/botao.vue';
import Input from './components/input.vue';
import Texto from './components/texto.vue';

export default {
  name: 'App',
  components: {
    Batata, Input, Texto
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
