<template>
    <header class="header-container">
        <div class="left-section">
            <!-- Inserisci qui il logo -->
            <img src="./img/images/gym_logo_1x.png" alt="Avada Gym Logo" class="logo">
        </div>

        <div class="right-section">
            <a href="#" class="header-link">Home</a>
            <a href="#" class="header-link">About Us</a>
            <a href="#" class="header-link">Facilities</a>
            <a href="#" class="header-link">Membership</a>
            <a href="#" class="header-link">Testimonials</a>
            <a href="#" class="header-link">Blog</a>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header'
};
</script>

<style scoped>
.header-container {
    background-color: transparent;
    /* Trasparente */
    width: 100%;
    position: fixed;
    /* Header fisso in cima alla pagina */
    top: 0;
    left: 0;
    z-index: 999;
    /* Assicura che l'header sia sovrapposto al contenuto */
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.left-section {
    display: flex;
    align-items: center;
}

.right-section {
    display: flex;
    background-color: rgba(0, 0, 0, 0.5);
    /* Sfondo trasparente con un po' di opacità */
    border-radius: 10px;
    /* Arrotondare i bordi */
    padding: 10px;
    /* Aggiungere un po' di spazio intorno ai link */
}

.logo {
    height: 40px;
    /* Altezza del logo */
}

.header-link {
    color: #fff;
    text-decoration: none;
    margin-left: 20px;
}

.header-link:hover {
    text-decoration: underline;
}
</style>