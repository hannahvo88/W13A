<template>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
            Corporis similique itaque harum doloremque corrupti nihil eum quisquam repellendus temporibus. 
            Aperiam expedita harum laborum eaque perferendis mollitia quidem repellendus dicta totam!</p>
        
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Facilis minus officia voluptates pariatur fugiat. Possimus repellat neque ipsum eius, accusamus quas. 
            Dolores sed recusandae corrupti amet tempore, tenetur aspernatur consectetur.</p>
        <sub-comp></sub-comp>
    
    </div>
</template>

<script>

import SubComp from './SubComp.vue'

    export default {
        name : "MainPage",
        components: {
            SubComp,
            
        } 
    }
</script>

<style scoped>

    p {
        display: grid;
        border: black solid 1px;
    }

</style>