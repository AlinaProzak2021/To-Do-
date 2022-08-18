<template>
  <div class="todo-list">
    <div class="todo-list__search">
      <input type="text" class="todo-list__input" placeholder="Search..." />
      <img src="../../../resources/search.png" alt="" />
    </div>
    <button class="todo-list__button">Add TODO</button>
    <div class="todo-list__list">
      <ul></ul>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.todo-list {
  width: 370px;
  height: 505px;
  background: #d8cfe3;
  box-shadow: 0px 0px 15px 5px rgba(63, 63, 63, 0.44);
  border-radius: 40px;
  display: flex;
  flex-direction: column;
}
.todo-list__search {
  width: 310px;
  height: 35px;
  background: #ddd9e1;
  border: 2px solid #8249ca;
  border-radius: 25px;
  display: flex;
  margin: 0 auto;
  margin-top: 35px;
  align-items: center;
  margin-bottom: 20px;
}
.todo-list__input {
  width: 260px;
  height: 100%;
  background: none;
  border: none;
  padding-left: 20px;
  outline: none;
}
.todo-list__search > img {
  width: 20px;
  height: 20px;
}
.todo-list__button {
  width: 310px;
  margin: 0 auto;
  height: 35px;
  background: #ddd9e1;
  border: 2px solid #8249ca;
  border-radius: 25px;
  color: #353535;
}
</style>