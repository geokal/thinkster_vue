<template>
  <div>
    <FormulateInput type="text" label="What is your name?" v-model="value"/>
    <strong>
      Hello
      <em>{{ value }}</em>!
    </strong>
  </div>
</template>


<script>
export default {
  name: "myName",
  props: {
    value: "My initial value"
  }
};
</script>

<style>
</style>


