<template>
        <section class="section_main">
            <article class="article_main">
                <script-example></script-example>
            </article>
        </section>
</template>

<script>
import ScriptExample from './ScriptExample.vue';
    export default {
        name: `Script_example`,

        components:{
            ScriptExample

        }
    
    }
</script>

<style scoped>

.section_main{
    display: grid;

    align-items: center;

    justify-items: center;
}

.article_main{

    
}

</style>