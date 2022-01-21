<template>
<Navigation/>
  <section id="container">

    <Registration @register-contact="registerNewUser"/>


    <UserOnQueue nickname="@devasse" name="Joao Devson" lastname="Mucavel" email="joao.mucavel@ideiasdinamicas.com" hrs="12:15 as 12:30"/>
  </section>
</template>

<script>

import Navigation from './components/layout/Navigation.vue' 
import UserOnQueue from './components/modules/queue/UserOnQueue.vue'
import Registration from './components/modules/registration/NewUser.vue'

export default {
  name: 'App',
  data () {
    return {

      contactsList: [
        {name: 'Joao Devsom', lastname: 'Mucavel', phone: '844559091', email: 'joaodevsonm@gmail.com'}
      ]

    }
  },
  components: {
    Navigation,
    UserOnQueue,
    Registration,
  },

  methods: {
    registerNewUser () {

    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#container{
  width: 70%;
  margin: 5% auto;
}
</style>
