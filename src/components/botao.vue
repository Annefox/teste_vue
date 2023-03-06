<template> 
<button> {{ mensagem }} </button>

</template>



<script>
export default {

  name: "botao",

  props:{
    mensagem: {
      type: String,
      required: true
    }
  }
}
</script>



<style>

</style>