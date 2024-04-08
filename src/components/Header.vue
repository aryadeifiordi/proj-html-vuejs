<template>
    <header class="header-container">
        <div class="left-section">

            <img src="./img/images/gym_logo_1x.png" alt="Avada Gym Logo" class="logo">
        </div>

        <div class="right-section">
            <a href="#" class="header-link red">Home</a>
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
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 999;
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
    border-radius: 10px;
    padding: 10px;
}

.logo {
    height: 40px;

}

.header-link {
    color: #fff;
    text-decoration: none;
    margin-left: 20px;
    font-family: Arial, sans-serif;
    text-transform: uppercase;
}

.header-link.red {
    color: red;

}

.header-link:hover {
    text-decoration: underline;
}
</style>