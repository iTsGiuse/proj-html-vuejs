
<script>

    export default {
        name: 'ProssimiEventiCarosello',
    }

</script>

<template>

    <section id="prossimi-eventi-carosello">
        <div class="container mt-3">
            <div class="row justify-content-between align-items-center">
                <div class="col-8">
                    <h3>LIFESTYLE & STORIES</h3>
                </div>
                <div class="col-4 d-flex justify-content-end align-items-center"> 
                    <button class="filter me-3 ps-3 pe-3 pt-1 pb-1">ALL</button>
                    <button class="filter me-3 ps-3 pe-3 pt-1 pb-1">LIFESTYLE</button>
                    <button class="filter ps-3 pe-3 pt-1 pb-1">STORIES</button>
                </div>
            </div>
            <div class="row mt-2">
                <div class="col-8">
                    <div class="card">
                        <img src="../../assets/img/success-story.webp" class="card-img" alt="...">
                        <span class="ms-tag-standard ms-tag-standard-principal ps-3 pe-3">Culture</span>
                        <div class="card-img-overlay">
                            <div class="d-flex">
                                <span class="card-text text-white me-3"> <i class="fa-solid fa-user" style="color: #ffffff;"></i> demo </span>
                                <span class="card-text text-white"> <i class="fa-regular fa-calendar-days" style="color: #ffffff;"></i> December 26, 2022 </span>
                            </div>
                            <h5 class="card-title text-white">Last updated 3 mins ago</h5>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="row border-bottom">
                        <div class="card mb-4">
                            <div class="row g-0">
                                <div class="col-4">
                                    <img src="../../assets/img/travel-alone.webp" class="img-fluid" alt="...">
                                    <span class="ms-tag-standard ms-tag-standard-small ps-2 pe-2">Stories</span>
                                </div>
                                <div class="col-8">
                                    <div class="card-body">
                                        <div class="d-flex">
                                            <span class="card-text me-2"> <i class="fa-solid fa-user"></i> demo </span>
                                            <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                        </div>
                                        <p class="card-title">Travelling Alone in Awesome</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row border-bottom mt-3">
                        <div class="card mb-4">
                            <div class="row g-0">
                                <div class="col-4">
                                    <img src="../../assets/img/best-places.webp" class="img-fluid" alt="...">
                                    <span class="ms-tag-standard ms-tag-standard-small ps-2 pe-2">Lifestyle</span>
                                </div>
                                <div class="col-8">
                                    <div class="card-body">
                                        <div class="d-flex">
                                            <span class="card-text me-2"> <i class="fa-solid fa-user"></i> demo </span>
                                            <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                        </div>
                                        <p class="card-title">Travelling Alone in Awesome</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-3">
                        <div class="card mb-4">
                            <div class="row g-0">
                                <div class="col-4">
                                    <img src="../../assets/img/music-love.webp" class="img-fluid" alt="...">
                                    <span class="ms-tag-standard ms-tag-standard-small ps-2 pe-2">Culture</span>
                                </div>
                                <div class="col-8">
                                    <div class="card-body">
                                        <div class="d-flex">
                                            <span class="card-text me-2"> <i class="fa-solid fa-user"></i> demo </span>
                                            <span class="card-text"> <i class="fa-regular fa-calendar-days"></i> December 26, 2022 </span>
                                        </div>
                                        <p class="card-title text-danger">Travelling Alone in Awesome</p>
                                    </div>
                                </div>
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

    #prossimi-eventi-carosello{

        .filter{
            border: 1px solid transparent;
            border-radius: 10px;
            background-color: $main-color-black;
            color: white;
        }

        .card{
            height: 100% !important;
            border: 1px solid transparent !important;

            .card-img, .img-fluid{
                position: relative;
            }
            .card-img{
                height: 368px;
                object-fit: fill;
            }

            .card-img-overlay{
                top: 75% !important;
                left: 1% !important;
            }  

            .card-text{
                margin-bottom: 2px !important;
                font-weight: bolder !important;
            }

            .img-fluid{
                    height: 105% !important;
                }
            
            .ms-tag-standard{
                border-radius: 5px;
                background-color: $main-color-white;
                position: absolute;
                z-index: 1;
            }
            .ms-tag-standard-small{
                top: 15%;
                left: 12%;
                transform: translate(-50%, -50%);
            }
            .ms-tag-standard-principal{
                top: 5%;
                left: 7%;
                transform: translate(-50%, -50%);
            }

        }
    }
</style>