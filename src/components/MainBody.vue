<template>
  <section class="container">
   <p>
      Marque a Fila e Veja quem te Segue na Copa<br>
      <a href="#" target="_blank" rel="noopener">Sou eu a seguir</a>.
    </p>
   <div class="content-holder">
    <div class="columns is-desktop">
      <div class="column">
        <Colaborator />
      </div>
      <div class="column">
        <Colaborator />
      </div>
      <div class="column">
        <Colaborator />
      </div>
      <div class="column">
        <Colaborator />
      </div>
    </div>
   </div>
  </section>
</template>

<script>
import Colaborator from "./subcomponents/colaborator.vue";
export default {
  components: {
    Colaborator,
  },
};
</script>

<style scoped>
section{
    padding: 1% 0;
}
section p{
  padding:2% 0;
}

@media (max-width: 1024px){
  .content-holder{
    padding:2% 10%;
  }
}
</style>