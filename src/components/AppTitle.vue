<script>
export default {
    data() {
        return {
            title: "Vue Hello World",
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
