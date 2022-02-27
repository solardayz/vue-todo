<template>
  <HeaderToDo></HeaderToDo>
  <InputToDo></InputToDo>
  <ListToDo></ListToDo>
  <FooterToDo></FooterToDo>
</template>

<script>
import HeaderToDo from "@/components/HeaderToDo";
import InputToDo from "@/components/InputToDo";
import ListToDo from "@/components/ListToDo";
import FooterToDo from "@/components/FooterToDo";

export default {
  name: 'App',
  components: {
    HeaderToDo,
    InputToDo,
    ListToDo,
    FooterToDo
  }
}
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
