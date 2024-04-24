<script>

    export default {
        name: 'Info',
    }

</script>

<template>

    <section id="info">
        <div class="container pt-5">
            <div class="row border-top mb-4">

            </div>
            <div class="row">
                <div class="col-6">
                    <div class="card">
                        <img src="../../assets/img/anime-logo.webp" alt="">
                    </div>
                </div>
                <div class="col-6">
                    <div class="d-flex justify-content-end align-items-center">
                        <h5 class="text-white">© Anime Tech, Therme by HasnainDEV</h5>
                    </div>
                </div>
            </div>
        </div>  

    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

    #info{
        background-color: $main-color-red;

        .card{
            width: 40%;
            height: 100%;
            background-color: $main-color-red;
            border: 0px solid transparent !important;

            img{
                filter: brightness(0%);
            }
        }
        
        .col-6:nth-last-child(1) .d-flex{
            height: 100%;
        }
    }

   

</style>