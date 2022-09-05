<template>
    <div class="hero">
        <div class="container">
            <img alt="Vue logo" src="../assets/logo.png">
            <Title msg="La mia prima app con Vue CLI!"></Title>
        </div>
    </div>
</template>


<script>    
    import Title from './Title.vue'

    export default {
        name: 'HeroJumbotron',
        components: {
            Title
        }
    }

</script>

<style lang="scss">
.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 500px;
    padding: 2rem 1rem;
    background-color: cornflowerblue;
}

.container {
    max-width: 1200px;
    margin-inline: auto;
    text-align: center;
}
</style>