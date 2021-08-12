<template>
    <header>
        <h1>Welcome to my website</h1>
        <button @click="Button">Try Me!</button>
    </header>
</template>

<script>
    export default {
        name : "WelcomeHeader",
        methods : {
            Button (){
                console.log ("Add something more")
            }
        }
    }
</script>

<style scoped>

</style>