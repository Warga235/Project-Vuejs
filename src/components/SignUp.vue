<template>
    <img class="logo" src="../assets/logo.jpg">
    <h1>Sign Up</h1>
<div class="register">
    <input type="text" placeholder="First Name" />
    <input type="text" placeholder="Email"/>
    <input type="text" placeholder="Password"/>
    <button>Sign Up</button>
</div>
</template>
<script>
    export default {
        name: 'SignUp'
    }
</script>

<style>
    .logo {
        width: 100px;
    }
    .register input {
        width: 300px;
        height: 40px;
        padding-left: 20px;
        margin-bottom: 30px;    
        margin-right: auto;
        margin-left: auto;
        border: 1px solid skyblue;
        display: block;
    }
    .register button {
        width: 320px;
        height: 40px;
        background-color: skyblue;
        border: 1px solid skyblue;
        display: block;
        cursor: pointer;
    }
</style>