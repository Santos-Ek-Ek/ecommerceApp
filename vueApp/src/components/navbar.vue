
<template>
    <nav class="navbar">

        <div class="left">
            <div class="logo"><a href="">ZAMNA-EXPRESS</a></div>
        </div>

        <div class="center">
            <input type="search" placeholder="Buscar productos, marcas y más...">
            <button id="button1" type="submit">Buscar</button>
        </div>

        <div class="right">
            <div class="icon-wishlist">
                <font-awesome-icon :icon="['fas', 'heart']" />
                <span><a href="">Favoritos</a></span>
            </div>

            <div class="icon-user">
                <font-awesome-icon :icon="['fas', 'user']" />
                <span><a href="">Ingresar</a></span>             
            </div>

            <div class="icon-cart">
                <a href=""><font-awesome-icon :icon="['fas', 'shopping-cart']" /></a>
            </div>

        </div>

    </nav>
</template>

<script>


export default {
    name: 'navbar'
}

</script>

<style scoped>
    @import url(../style.css);
</style>


