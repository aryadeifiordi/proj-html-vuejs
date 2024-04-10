<template>
    <div class="container-background">


        <header class="header-container">
            <div class="logo-container">
                <img src="/public/img/images/gym_logo_2x.png" alt="Avada Gym Logo" class="logo">
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
    </div>
</template>

<script>
export default {
    name: 'Header'
};
</script>

<style scoped>
.container-background {
    background-image: url(./img/images/home-banner.jpg);
    background-size: cover;
    background-position: center;
    height: 80vh;
}

.header-container {
    height: 20vh;
    color: white;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: 56rem;
}


.header-text-container {

    width: 10rem;
    margin-top: 15rem;
    margin-left: 15rem;
}

.right-section {
    margin-top: 20px;
    margin-right: 20px;
    background-color: black;
    color: white;
    height: 20px;
    width: 550px;
    display: flex;
    justify-content: space-between;

}


.logo {
    align-self: flex-start;
    height: 80px;
    margin-left: 2rem;
    margin-top: 2rem;
}

.header-title {
    margin-bottom: 10px;
}

.header-link {
    color: white;
    text-decoration: none;
    margin-bottom: 20px;
    font-family: Arial, sans-serif;
    text-transform: uppercase;
}

.header-link.red {
    color: red;
    text-decoration: none;
    margin-bottom: 10px;
    font-family: Arial, sans-serif;

}

.header-link:hover {
    text-decoration: underline;
}
</style>
