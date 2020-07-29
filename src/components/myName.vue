<template>
    <div class="centered">
        <h1>{{name}}</h1>
    </div>
</template>

<script>
export default {
    props : ['name']
}
</script>

<style scoped>
    .centered {
        background:#c8d1d4;
        display: flex;
        justify-content:center;
        align-items:center;
        min-height: 100vh;
    }
</style>