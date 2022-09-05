<template>
    <h1 class="title">{{ msg }}</h1>
</template>

<script>

    export default {
        name: "MainTitle",
        props: {
            msg: String
        }
    }

</script>

<style lang="scss">
    .title {
        font-size: 3rem;
    }
</style>