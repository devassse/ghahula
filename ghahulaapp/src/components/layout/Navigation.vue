<template>
    <section id="navigation">
        <h2 class="logo">
            <img src="@/assets/logos/logo_ghahula.png" alt="">
            Ghahula
        </h2>
    </section>
</template>

<script>
export default {
    
}
</script>

<style scoped>
#navigation{
    padding: 15px;

    background: #f1f1f1;

    display: flex;
    justify-content: space-between;
}
.logo{
    display: flex;
    align-items: center;
    cursor: pointer;
}
.logo img{
    width: 50px;
    margin-right: 10px;
}

</style>