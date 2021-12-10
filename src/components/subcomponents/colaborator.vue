<template>
  <div class="card" @click="markedQueue">
    <div class="card-image">
      <figure class="image is-4by3">
        <img
          src="../../assets/imgs/user-profile.png"
          alt="User Profile image"/>
      </figure>
    </div>
    <div class="card-content">
      <div class="media">
        <div class="media-content">
          <p class="title is-4">John Smith</p>
          <p class="subtitle is-6">@johnsmith</p>
        </div>
      </div>

      <div class="content">
        Hora Marcada:
        <br />
        <time datetime="2016-1-1">12:45 <span>às</span> 13:20</time>
      </div>
    </div>
  </div>
</template>

<script>
export default {
   methods:{
     markedQueue () {
       console.log('Confirmação da Marcação!');
     }
   }
}
</script>

<style scoped>
  .card-image img{
    width: auto;
    margin: 4% auto;
  }
</style>