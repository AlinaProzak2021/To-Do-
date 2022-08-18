<template>
  <form class="add__form">
    <h1 class="add__h1">Add TODO</h1>
    <input type="text" class="add__input" placeholder="Name" />
    <input
      type="text"
      class="add__input add__input__mb20"
      placeholder="Description"
    />
    <h3 class="add__h3">Condition</h3>
    <div class="add__buttons">
      <button class="add__button add__button__grey">TODO</button>
      <button class="add__button add__button__blue">DOING</button>
      <button class="add__button add__button__green">DONE</button>
    </div>
    <button class="add__button add__button__w440">Save</button>
  </form>
</template>
<script>
export default {
  name: "add-form",
};
</script>
<style>
.add__form {
  background: #d8cfe3;
  box-shadow: 0px 0px 15px rgba(63, 63, 63, 0.44);
  border-radius: 40px;
  width: 700px;
  display: flex;
  flex-direction: column;
}
.add__h1 {
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 52px;
  padding-top: 45px;
  letter-spacing: 0.05em;
  color: #353535;
  text-align: center;
  margin-bottom: 20px;
}
.add__input {
  background: #ddd9e1;
  border: 2px solid #8249ca;
  border-radius: 25px;
  width: 620px;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 20px;
  height: 60px;
  padding-left: 20px;
  outline-color: #6167ff;
  font-size: 18px;
  line-height: 34px;
  letter-spacing: 0.05em;
}
.add__input__mb20 {
  margin-bottom: 10px;
}
.add__h3 {
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 40px;
  letter-spacing: 0.05em;
  text-align: center;
  color: #353535;
  margin-bottom: 10px;
}
.add__buttons {
  width: 640px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  margin-bottom: 30px;
}
.add__button {
  width: 180px;
  height: 40px;
  border-radius: 25px;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 34px;
  letter-spacing: 0.05em;
  color: #353535;
}
.add__button__grey {
  background: #787878;
  border: 2px solid #8249ca;
}
.add__button__blue {
  background: #989cff;
  border: 2px solid #7d56cf;
  border-radius: 25px;
}
.add__button__green {
  background: #73cc7c;
  border: 2px solid #8249ca;
  border-radius: 25px;
}
.add__button__w440 {
  width: 640px;
  margin: 0 auto;
  background: #ddd9e1;
  border: 2px solid #8249ca;
  border-radius: 25px;
  margin-bottom: 60px;
  height: 50px;
}
</style>