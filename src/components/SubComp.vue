<template>
    <button @mouseover="Toggle">Toggle Button</button>
</template>

<script>
export default {
    name: "SubComp",
    methods: {
        Toggle (){
            console.log ("Delete or Save option")
        }
    }
    }

</script>