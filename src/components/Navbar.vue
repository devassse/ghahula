<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="#">
          <img
            src="../assets/imgs/logo_ghahula.png"
            width="60"
            height="28"
            alt=""
          />
          <span> Ghahula na Copa </span>
        </a>
        <a
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons">
              <a class="button is-black">
                <strong>Registar-se</strong>
              </a>
              <a class="button is-outlined"> Efectuar Login </a>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.navbar-item img {
  max-height: 2.75rem;
}
.navbar-brand span {
  margin-left: 5px;
}
</style>