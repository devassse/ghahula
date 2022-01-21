<template>
  <section class="userblock">
    <img class="img-profile" src="@/assets/imgs/profile.png" alt="">
    <h3>{{ nickname }}</h3>
    <h3>{{ name }} {{ lastname }}</h3>
    <h5>{{email}}</h5>
    <h4>{{hrs}}</h4>
    <div>
        <button>Ofecer</button>
    </div>
  </section>
</template>

<script>
export default {
  props: ["nickname","name", "lastname", "email", "hrs"],
};
</script>
<style scoped>
.userblock{
    width: 25%;
    padding: 10px 5px;
    background-color: #f1f1f1;
    border-radius: 5px;
}
.img-profile{
    width: 50%;
}
</style>