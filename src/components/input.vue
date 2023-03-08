<template> 
  <div>
    <p>Message: {{ message }}</p>
    <label>{{ label }}</label>
  <input v-model="inputValue" @input="$emit('input-change', inputValue)">
    

  </div>
</template>

<script>
export default {
  name: "Input",
  props: {
    label: {
      type: String,
      default: "Input Label"
    },
    value: {
      type: String,
      default: ""
    }
  },
  data() {
    return {
      inputValue: this.value,
      message: ""
    };
  }
};
</script>


<style></style>