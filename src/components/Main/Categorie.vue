<script>

    export default {
        name: 'Categorie',
    }

</script>

<template>
    <section id="categorie">
        <div class="ms-container mt-4 mb-2">
            <div class="row">
                <div class="col-2">
                    <div class="card text-white">
                        <img src="../../assets/img/anime-fashion.webp" alt="">
                        <h4>FASHION</h4>
                    </div>
                </div>
                <div class="col-2">
                    <div class="card text-white">
                        <img src="../../assets/img/success-story.webp" alt="">
                        <h4>CULTURE</h4>
                    </div>
                </div>
                <div class="col-2">
                    <div class="card text-white">
                        <img src="../../assets/img/healthy-foods.webp" alt="">
                        <h4>FOOD</h4>
                    </div>
                </div>
                <div class="col-2">
                    <div class="card text-white">
                        <img src="../../assets/img/visit-france.webp" alt="">
                        <h4>LIFESTYLE</h4>
                    </div>
                </div>
                <div class="col-2">
                    <div class="card text-white">
                        <img src="../../assets/img/travel-alone.webp" alt="">
                        <h4>STORIES</h4>
                    </div>
                </div>
                <div class="col-2">
                    <div class="card text-white">
                        <img src="../../assets/img/best-places.webp" alt="">
                        <h4>TRAVEL</h4>
                    </div>
                </div>
                
            </div>
        </div>
    </section>  
</template>

<style scoped lang="scss">

    #categorie {
        
        .col-2{
            padding-right: 6px !important;
        }
        .col-2:nth-child(1){
            padding-left: 0px !important;
        }
        .col-2:nth-last-child(1){
            padding-right: 0px !important;
        }
        img{
            position: relative;
            border-radius: 5px;
        }

        h4{
                position: absolute;
                z-index: 2;
                top: 45%;
                left: 50%;
                transform: translate(-50%, -50%);
            }
    }

</style>