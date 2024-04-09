<template>
    <header class="header-container">
        <div class="logo-container">
            <img src="./img/images/gym_logo_1x.png" alt="Avada Gym Logo" class="logo">
        </div>

        <div class="header-text-container">
            <h1 class="header-title">NO PAIN NO GAIN</h1>
            <p>Motivation is what gets you started. Habit is what keeps you going.</p>
        </div>

        <div class="right-section">
            <router-link to="/" class="header-link red">Home</router-link>
            <router-link to="/about" class="header-link">About Us</router-link>
            <router-link to="/facilities" class="header-link">Facilities</router-link>
            <router-link to="/membership" class="header-link">Membership</router-link>
            <router-link to="/testimonials" class="header-link">Testimonials</router-link>
            <router-link to="/blog" class="header-link">Blog</router-link>
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
    background-image: url('./img/images/home-banner.jpg');
    background-size: cover;
    background-position: center;
    color: white;
    width: 100%;
    height: 400px;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding: 20px;
}

.logo-container {
    margin-top: 20px;
}

.right-section {
    margin-top: 20px;
}

.logo {
    height: 40px;
}

.header-title {
    margin-bottom: 10px;
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