<template>
    <main>
        <h1>NO PAIN NO GAIN</h1>
        <p>Motivation is what gets you started. Habit is what keeps you going.</p>
    </main>
</template>

<script>
export default {
    name: 'Main'
};
</script>

<style scoped>
main {
    background-image: url('./img/images/home-banner.jpg');
    background-size: cover;
    background-position: center;
    color: white;
    padding: 20px;
    position: fixed;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100vh;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

h1 {
    font-size: 6rem;
}
</style>