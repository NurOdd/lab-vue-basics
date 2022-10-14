<template>
    <div>
        <h2>interacción 4</h2>
        <div v-for="element in data">
            {{element.title}},   {{element.description}},  {{element.content}}
        </div>
    </div>
</template>


<script setup>
const data = [
    {
        title: 'Titulo 1',
        description: 'Descripcion 1',
        content: 'contenido 1'
    },
    {
        title: 'Titulo 2',
        description: 'Descripcion 2',
        content: 'contenido 2'
    },
    {
        title: 'Titulo 3',
        description: 'Descripcion 3',
        content: 'contenido 3'
    },
]

</script>


<style scoped>
</style>