<script>

    export default {
        name: 'Banner',
    }

</script>

<template>

    <section id="banner">
        <div class="container pt-5 pb-4 mt-4 mb-4">
            <div class="row">
                <div class="col">
                    <img src="../../assets/img/page-banner-1-768x71.webp" alt="">
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

    #banner{
        background-color: $main-color-grey;

        img{
            object-fit: cover;
            width: 100%;
            height: 80%;
        }
    }

</style>