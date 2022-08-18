<template>
  <div class="main-page">
    <toDoList />
    <addForm />
  </div>
</template>
<script>
import addForm from "./Home/addForm.vue";
import toDoList from "./Home/toDoList.vue";
export default {
  name: "Home-Page",
  components: {
    addForm,
    toDoList,
  },
};
</script>
<style>
.main-page {
  width: 90%;
  height: 100%;
  align-items: center;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  flex-wrap: wrap;
}
</style>