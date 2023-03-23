<script>
export default {
    data() {
        return {
            title: "La mia prima app con Vite!",
        }
    },
}
</script>

<template>
    <div id="title-wrapper">
        <h1>{{ title }}</h1>
    </div>
</template>

<style scoped>
#title-wrapper {
    text-align: center;
}
</style>
