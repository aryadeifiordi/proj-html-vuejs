<template>
    <main>
        <h1>Welcome to our website!</h1>
        <p>This is the main content of our website.</p>
    </main>
</template>

<script>
export default {
    name: 'Main'
};
</script>

<style scoped>
main {
    background-color: black;
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
</style>
