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
@import url('https://fonts.googleapis.com/css2?family=Merriweather+Sans:wght@800&family=Poppins:wght@500&family=Signika+Negative:wght@500;700&display=swap');

.navbar-items {
    display: flex;
    align-items: center;
    margin: auto;
}

.navbar-items__logo-site {
    font-family: 'Merriweather Sans' , sans-serif;
    font-size: 22px;
    font-weight: 800;
    color: #952194;
}

.navbar-items__links__menu {
    font-family: 'Signika Negative', sans-serif;
    font-size: 18px; 
    font-weight: 700;
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
