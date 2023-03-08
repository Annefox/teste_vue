<template> 
<button @click-botao="buttonClick"> {{ mensagem }} </button>


</template>

<script>

export default {

  name: "botao",
  methods: {
    buttonClick() {
      console.log("O botao foi clicado!");
    }
  },
  props:{
    mensagem: {
      type: String,
      required: true
    }
  }
};

</script>



<style> 



</style>