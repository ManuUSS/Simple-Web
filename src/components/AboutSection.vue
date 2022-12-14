<template>
    <section class="about__section">
        <div class="uk-container">
            <div class="uk-height-large uk-background-cover uk-overflow-hidden uk-light uk-flex">
                <div class="uk-width-1-2@m">
                    <h1 uk-parallax="opacity: 0,1,1; y: -100,0,0; x: 100,100,0; scale: 2,1,1; end: 50vh + 50%;" class="font--black">Hey!</h1>
                    <p uk-parallax="opacity: 0,1,1; y: 100,0,0; x: -100,-100,0; scale: 0.5,1,1; end: 50vh + 50%;" class="font--black ">Here you'll discover something about me!</p>
                </div>
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
.about__section {
    
    color: #111111 !important;
    background-color: #f7f7f7;
    padding: 5rem;

    .uk-container {
        color: #111111 !important;
    }
    
}

.font--black {
    color: #111111;
}

</style>