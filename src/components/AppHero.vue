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
    <div id="hero">
        <h2>HERO</h2>
    </div>
</template>

<style scoped>
#hero {
    background-image: url(/images/hero.jpg);
    height: 400px;

    display: flex;
    justify-content: center;
    align-items: center;

    position: relative;
}

#hero::before {
    background-color: black;
    width: 100%;
    height: 100%;

    position: absolute;
    top: 0;
    left: 0;

    content: "";
    opacity: .6;
}

#hero h2 {
    font-size: 40px;

    z-index: 1;
}
</style>
