<template>
  <section>
    <h3>Registar - se na Plataforma</h3>
    <form @submit.prevent="registerUser">
      <div>
        <label for="name">Nome:</label>
        <input type="text" v-model="enteredName" />
      </div>
      <div>
        <label for="name">Telefone:</label>
        <input type="tel" v-model="enteredPhone" />
      </div>
      <div>
        <label for="name">E-mail:</label>
        <input type="email" v-model="enteredEmail" />
      </div>
      <div>
        <button>Confirmar</button>
      </div>
    </form>
  </section>
</template>

<script>
export default {
    emits: ['register-contact'],
  data() {
    return {
      enteredName: '',
      enteredPhone: '',
      enteredEmail: '',
    };
  },

  methods: {
      registerUser (){
          this.$emit('register-contact', this.enteredName, this.enteredPhone, this.enteredEmail)
      }
  }
};
</script>