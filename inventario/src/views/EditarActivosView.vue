<template>
    <div>
        <h1>{{titulo}} : {{$route.params.id}}</h1>
    </div>
</template>
<script>
    export default {
        name: 'EditarActivosView',
        data() {
            return {
                titulo: 'Editar Activos'
            }
        },
        methods: {
        },
        computed: {
        },
        mounted() {
        },
        components: {
        }
    }
</script>

<style>
</style>