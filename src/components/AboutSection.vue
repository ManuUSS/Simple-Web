<template>
    <section class="about__section">
        <div class="uk-height-large uk-background-cover uk-overflow-hidden uk-light uk-flex">
            <div class="uk-width-1-2@m uk-text-center uk-margin-4 uk-margin-auto-vertical">
                <h1 uk-parallax="opacity: 0,1,1; y: -100,0,0; x: 100,100,0; scale: 2,1,1; end: 50vh + 50%;">Hey!</h1>
                <p uk-parallax="opacity: 0,1,1; y: 100,0,0; x: -100,-100,0; scale: 0.5,1,1; end: 50vh + 50%;">Here you'll discover something about me!</p>
            </div>
        </div>
    </section>    

</template>
<script>
export default {
    name: 'AboutSection'
}
</script>
<style lang="scss" scoped>
.about {
    &__section {
        color: #111111 !important;
        background-color: #f7f7f7;
        padding: 5rem;
    }
}

</style>