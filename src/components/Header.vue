<script setup>
import NavBar from './NavBar.vue';
</script>

<template>
    <main>
        <header>
            <div class="header-items">
                <NavBar />
            </div>
        </header>
    </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville&family=Ubuntu:wght@400;700&display=swap');

.header-items {
    background-color: #fae1fa;
    height: 170px;
    display: flex;
    font-family: Ubuntu, Arial, Helvetica, sans-serif;
    font-weight: 700;
}

</style>
