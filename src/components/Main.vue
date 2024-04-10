<template>
    <div class="main-container">
        <div class="highlighted-section">
            <h1>WORLD CLASS fitness</h1>
            <img src="/public/img/images/divider-xx-red.png" alt="divider" class="">
            <p>At Avada Gym, everything we do from top to bottom is of the highest quality to ensure we're equipped to
                help you reach your goals of a healthy and fit lifestyle</p>
        </div>
        <div class="signup-section">
            <div>
                <img src="/public/img/images/home_img-compressor-200x111.jpg" alt="">
            </div>
            <div>
                <p>Sign Up For A Free Training Session!</p>
                <div class="input-group">
                    <label for="name">Name</label>
                    <input type="text" id="name">
                </div>
                <div class="input-group">
                    <label for="surname">Surname</label>
                    <input type="text" id="surname">
                </div>
            </div>
        </div>
        <div>
            <h1>strength condition</h1>
        </div>
        <div>
            <h1>real world results</h1>
        </div>
        <div>
            <h1>high performance </h1>
        </div>
        <div>
            <h1>punch picture</h1>
        </div>
        <div>
            <h1>meet our trainers</h1>
        </div>
        <div>
            <h1>performance news</h1>
        </div>
        <div>
            <h1>achieve your fitness goals</h1>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Main'
};
</script>

<style scoped>
.main-container {
    display: flex;
    flex-direction: column;
}

.highlighted-section {
    background-color: #333;
    color: white;
    padding: 20px;
}

.signup-section {
    height: 30vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: grey;
}

.input-group {
    margin-bottom: 10px;
}

.input-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

.input-group input {
    width: 200px;
}
</style>
