<template> 
  <div>


  </div>
</template>
    <label>{{ label }}</label>
    <input v-model="inputValue" @input="$emit('input-change', inputValue)">
    <p>Message is: {{ message }}</p>

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