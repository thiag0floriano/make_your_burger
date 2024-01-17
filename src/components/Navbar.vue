<template>
    <nav>
        <RouterLink to="/">
            <img src="" id="logo">
        </RouterLink>
        <router-link to="/">Home</router-link> |
        <router-link to="/pedidos">Pedidos</router-link>
    </nav>
</template>

<script>
export default{
    name: 'Navbar',
    props: ["logo", "alt"]
}
</script>

<style scoped>

</style>