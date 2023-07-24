<script setup>
import TheSignInForm from './components/TheSignInForm.vue'
import TheSignUpForm from './components/TheSignUpForm.vue'
</script>

<template>
    <div class="center">
        <div class="box">
            <TheSignInForm />
        </div>
    </div>
    <div class="center">
        <div class="box">
            <TheSignUpForm />
        </div>
    </div>
</template>

<style scoped>
.center {
    display: flex;
    justify-content: center;
}
.box {
    width: 60%;
    box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.25);
    padding: 1rem;
    background-color: white;
    border-radius: 5px;
    margin-bottom: 1rem;
}
</style>
