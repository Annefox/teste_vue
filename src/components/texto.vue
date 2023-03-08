<template> 
<h1> Titulo </h1>
<h2> 
    A expressão Lorem ipsum em design gráfico e editoração é um texto padrão em latim utilizado na 
    produção gráfica para preencher os 
    espaços de texto em publicações para testar e ajustar aspectos 
    visuais antes de utilizar conteúdo real.
</h2>
<button v-on:click="$emit('aceito')">foi</button>
</template>

<script>
export default{
    name: "Texto",
    props: {
    titulo: {
      type: String,
      required: true,
    },
    texto: {
      type: String,
      required: true,
    },
  },
  emits: ['aceito']
}

</script>

<style>

</style>