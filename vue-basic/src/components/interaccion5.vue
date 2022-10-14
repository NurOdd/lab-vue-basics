<template>
    <div  :class="{bcgColor: colorChange}">
        <h2>
        interacion 5
        </h2>
        <button @click="clickMe">Click Me!</button>
    </div>
</template>


<script setup>
const colorChange = ref(true);
const clickMe = () =>{
    colorChange.value = !colorChange.value
}
</script>


<style scoped>
.bcgColor {
    background-color: darkorange;
}
</style>