<template>
    <div v-on:click="click">
        <h2>{{ name }}</h2>
        <p>{{ description }}</p>
        <p id="red">Você clicou aqui {{ clicks }} vezes</p>
    </div>
</template>

<script>
    export default{
        data(){
            return{
                name: 'Maçã',
                description: 'Uma fruta muito gostosa',
                clicks: 0
            }
        },
        methods: {
            click(){
                this.clicks++
            }
        },
    }
</script>

<style>
    #red {
    font-weight: bold ;
    color: rgb(144, 12, 12);
}
</style>