<template>
  <div>
    <input type="text" v-model="collectedTodo">
    <button v-on:click="addToDo">입력</button>
  </div>
</template>

<script>
export default {
  name: "InputToDo",
  data: function () {
    return {
      collectedTodo: ""
    }
  },
  methods: {
    addToDo: function () {
      sessionStorage.setItem(this.collectedTodo, this.collectedTodo)
    }
  }
}
</script>

<style scoped>

</style>