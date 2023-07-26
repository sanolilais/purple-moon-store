<script setup>
</script>
<template>
    <nav class="navbar-items">
        <span class="navbar-items__logo-site">Purple Moon Store</span>
        <ul class="navbar-items__links__menu">
            <li><a href="#">Meu Carrinho</a></li>
            <li><a href="#">Categorias</a></li>
            <li><a href="#">Favoritos</a></li>
            <li><a href="#">Fale Conosco</a></li>
        </ul>
    </nav>
</template>

<style>
.navbar-items {
    display: flex;
    align-items: center;
}

.navbar-items__links__menu {
    display: flex;
    list-style: none;
    gap: 30px;
}

</style>