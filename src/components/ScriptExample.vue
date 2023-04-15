<template>
    <div>

    </div>
</template>

<script>
    export default {
        data() {
            return {
                tweets: [`tweet1`, `tweet2`, `tweet3`],

                num_friends: 2,
                
                logged_in: true,

                background: `green`

            }
        },
        methods: {
            makeGreen: function(){

                document.body[`style`][`background-color`] = this.background;
            }
        },

        mounted: function(){
            this.makeGreen();
        }

    }
</script>

<style scoped>

</style>