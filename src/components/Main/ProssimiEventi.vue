<script>

    export default {
        name: 'ProssimiEventi',
    }

</script>

<template>

    <section id="prossimi-eventi">
        <div class="container mt-5"> 
            <div class="row">
                <div class="col-3">
                    <div class="row flex-column mb-2">
                        <div class="card">
                            <img src="../../assets/img/anime-fashion.webp" class="card-img" alt="...">
                            <span class="ms-tag-standard ms-first-tag ps-3 pe-3">Fashion</span>
                            <span class="ms-tag-standard ms-second-tag ps-3 pe-3">Lifestyle</span>
                            <div class="card-img-overlay">
                                <div class="d-flex text-white justify-content-center">
                                    <span class="card-text me-4"> <i class="fa-solid fa-user" style="color: #ffffff;"></i> demo </span>
                                    <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                </div>
                                <h5 class="card-title text-center text-white">Fashion Trend Now A Days</h5>
                            </div>
                        </div>
                    </div>
                    <div class="row flex-column">
                        <div class="card">
                            <img src="../../assets/img/travel-alone.webp" class="card-img" alt="...">
                            <span class="ms-tag-standard ms-first-tag ps-3 pe-3">Travel</span>
                            <span class="ms-tag-standard ms-second-tag ps-3 pe-3">Stories</span>
                            <div class="card-img-overlay">
                                <div class="d-flex text-white justify-content-center">
                                    <span class="card-text me-4"> <i class="fa-solid fa-user" style="color: #ffffff;"></i> demo </span>
                                    <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                </div>
                                <h5 class="card-title text-center text-white">Fashion Trend Now A Days</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="card ms-3">
                            <img src="../../assets/img/best-places.webp" class="card-img" alt="...">
                            <span class="ms-tag-standard ms-tag-principal ms-tag-principal-left ps-3 pe-3">Lifestyle</span>
                            <span class="ms-tag-standard ms-tag-principal ms-tag-principal-center ps-3 pe-3">Stories</span>
                            <span class="ms-tag-standard ms-tag-principal ms-tag-principal-right ps-3 pe-3">Travel</span>
                            <div class="card-img-overlay card-img-overlay-principal">
                                <div class="d-flex text-white justify-content-center">
                                    <span class="card-text me-3"> <i class="fa-solid fa-user" style="color: #ffffff;"></i> demo </span>
                                    <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                </div>
                                <h5 class="card-title text-center text-white">Fashion Trend Now A Days</h5>
                            </div>
                        </div>
                </div>
                <div class="col-3">
                    <div class="row flex-column mb-2">
                        <div class="card">
                            <img src="../../assets/img/music-love.webp" class="card-img" alt="...">
                            <span class="ms-tag-standard ms-first-tag text-danger ps-3 pe-3">Lifestyle</span>
                            <span class="ms-tag-standard ms-second-tag ps-3 pe-3">Culture</span>
                            <div class="card-img-overlay">
                                <div class="d-flex text-white justify-content-center">
                                    <span class="card-text me-4"> <i class="fa-solid fa-user" style="color: #ffffff;"></i> demo </span>
                                    <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                </div>
                                <h5 class="card-title text-center text-white">Fashion Trend Now A Days</h5>
                            </div>
                        </div>
                    </div>
                    <div class="row flex-column">
                        <div class="card">
                            <img src="../../assets/img/visit-france.webp" class="card-img" alt="...">
                            <span class="ms-tag-standard ms-first-tag ps-3 pe-3">Fashion</span>
                            <span class="ms-tag-standard ms-second-tag ps-3 pe-3">Lifestyle</span>
                            <div class="card-img-overlay">
                                <div class="d-flex text-white justify-content-center">
                                    <span class="card-text me-4"> <i class="fa-solid fa-user" style="color: #ffffff;"></i> demo </span>
                                    <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                </div>
                                <h5 class="card-title text-center text-white">Fashion Trend Now A Days</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

    #prossimi-eventi{
        background-color: $main-color-white;

        .col-6 .card{
            display: block;
            width: 95%;
            
        }
        .card{
            border: 1px solid transparent !important;

            .card-img{
                position: relative;
            }

            .card-img-overlay{
                top: 60% !important;
            }  

            .card-img-overlay-principal{
                top: 81% !important;
            } 

            .card-text{
                margin-bottom: 2px !important;
                font-weight: bolder !important;
            }

        }
        
        .ms-tag-standard{
            border: 1px solid transparent;
            border-radius: 10px;
            background-color: $main-color-white;
            position: absolute;
            z-index: 1;
            color: black;
        }
        
        .ms-first-tag{
            top: 15%;
            left: 65%;
            transform: translate(-50%, -50%);
        }

        .ms-second-tag{
            top: 15%;
            left: 35%;
            transform: translate(-50%, -50%);
        }

        .ms-tag-principal{
            top: 8%;
        }

        .ms-tag-principal-center{
            left: 50%;
            transform: translate(-50%, -50%);
        }
        

        .ms-tag-principal-left{
            left: 34%;
            transform: translate(-50%, -50%);
        }

        .ms-tag-principal-right{
            left: 64%;
            transform: translate(-50%, -50%);
        }

        .col-6{
            padding: 0px !important;
        }
        
    }


</style>