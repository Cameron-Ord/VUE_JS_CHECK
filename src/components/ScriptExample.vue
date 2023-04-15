<template>
    <span>
    
        <h1>I am the script example</h1>

        <div class="container">

            <p>Friends: {{ num_friends }}</p>

            <p v-if="logged_in === true">You are logged in</p>

            <p></p>

            <p></p>
        </div>

    </span>
</template>

<script>




    export default {

     

        data() {
            return {
                names: [`Cameron`, `JSON`, `Brad`, `Jack`],

                num_friends: [1, 14, 0, 30],

                logged_in: false
            }
        },


    }
</script>

<style scoped>

.container{

    align-items: center;

    justify-items: center;

    display: grid;
}

</style>