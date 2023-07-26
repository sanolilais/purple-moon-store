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
    margin: auto;
}

.navbar-items__logo-site {
    color: #952194;
}

.navbar-items__links__menu {
    display: flex;
    list-style: none;
    gap: 30px;
}

.navbar-items__links__menu li a {
    text-decoration: none;
    font-size: 14px;
    justify-content: space-around;
    color: #511e51;

}
</style>
