<script>

    export default {
        name: 'HeaderMain',

    }

</script>

<template>
    <section id="header-main">
        <div class="container mt-2 mb-2">
            <div class="row align-items-center">
                <div class="col">
                    <img src="../../assets/img/anime-logo-300x89.webp" alt="Logo">
                </div>
                <div class="col d-flex justify-content-end">
                    <img src="../../assets/img/header-banner-300x38.webp" alt="Banner">
                </div>
            </div>
        </div>
    </section>  
</template>

<style scoped lang="scss">

    #header-main .row > .col:last-child img {
        width: 90% !important;
    }

    img{
        filter: brightness(100%)
    }
</style>