<template>
<Batata mensagem="Clique aqui!"/>
<Batata mensagem="Envie aqui"/>
<Batata mensagem="aaaaaaaaaaaaaaaa"/> 


<Input input-text label="Clique aqui" value=" Escreva algo"/>
<Input/>
<Input/>

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
