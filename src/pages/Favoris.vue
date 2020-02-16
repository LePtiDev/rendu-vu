<template>
    <div>
        <p>
            favoris
        </p>
        <p>{{this.$store.getters.favorite}}</p>
    </div>
</template>

<script>


export default {
    name: 'Favoris',
    components: {

    },

    data(){
        return{

        }
    },
}

</script>

<style scoped>

    div{
        width: 100%;
        height: 90vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
    }
</style>