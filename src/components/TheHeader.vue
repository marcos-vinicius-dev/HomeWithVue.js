<template>
    <header>
        <nav>
            <router-link to="/" class="logo">
                <img src="@/assets/logo.svg" alt="Marcos Vinicius">
            </router-link>
            <router-link class="btn" to="/login">
                Contato
            </router-link>
        </nav>
    </header>
</template>
<script>
export default {
    name: "Header"
}
</script>
<style scoped>
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 20px;
    box-shadow: 0 2px 4px rgba(30, 60, 90, 0.1);
}

.logo {
    padding: 10px 0;
}

.logo img{
    width: 40px;
}


</style>
