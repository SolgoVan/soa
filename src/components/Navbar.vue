<template>
    <nav class="navbar">
        <div class="logo">SOA</div>
        <div class="link">
            <router-link class="router-link" to="/">Acceuil</router-link>
            <router-link class="router-link" to="/member">Membres</router-link>
        </div>
    </nav>
</template>

<script>
    export default {
        name: 'AppNavbar',
    }
</script>

<style scoped>
    .navrbar{
        display: flex;
        justify-content: space-between;
        padding: 1rem;
        background-color: #333;
        color: white;
    }

    .logo{
        font-size: 1.5rem;
        font-weight: bold;
    }

    .link{
        display: flex;
    }

    .router-link{
        margin-right: 1rem;
        color: white;
        text-decoration: none;
    }

    .router-link:hover{
        text-decoration: underline;
    }
</style>