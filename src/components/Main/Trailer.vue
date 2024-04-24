<script>

    export default {
        name: 'Trailer',
    }

</script>

<template>
    <section id="trailer">
        <div class="container mt-5 mb-5">
            <div class="row">
                <div class="col-8">
                    <div class="card">
                        <img class="img-principale" src="../../assets/img/default.webp" alt="">
                        <img class="ms-tag-standard ms-tag-logo-channel" src="../../assets/img/channels4_profile.jpg" alt="">
                        <p class="ms-tag-standard ms-tag-name-video text-white">Overlord Seanson 4 - Official Trailer 3 | AniTv</p>
                        <span class="ms-tag-standard ms-tag-clock text-white"><i class="fa-solid fa-clock"></i></span>
                        <span class="ms-tag-standard ms-tag-clock-text text-white">Guarda più...</span>
                        <span class="ms-tag-standard ms-tag-share text-white"><i class="fa-solid fa-share"></i></span>
                        <span class="ms-tag-standard ms-tag-share-text text-white">Condividi</span>
                        <span class="ms-tag-standard ms-tag-logo-youtube text-danger"><i class="fa-brands fa-youtube"></i></span>
                        <span class="ms-tag-standard ms-tag-platform-text text-white">Guarda su </span>
                        <span class="ms-tag-standard ms-tag-platform text-white"><i class="fa-brands fa-youtube"></i> Youtube</span>
                    </div>
                </div>
                <div class="col-4 overflow-y-scroll">
                    <div class="row border-bottom justify-content-start align-items-center sfondo-grigio">
                        <div class="col-2 text-center text-white fs-1">
                            <span><i class="fa-solid fa-play"></i></span>
                        </div>
                        <div class="col-10 text-white">
                            <h5>Video Playlist</h5>
                            <span>1/7 Videos</span>
                        </div>
                    </div>
                    <div class="card mt-2">
                        <div class="row border-bottom">
                            <div class="col-1 d-flex align-items-center justify-content-center">
                                <span class="quadratino text-white ms-2">1</span>
                            </div>
                            <div class="col-4">
                                <img src="../../assets/img/default.webp" class="img-fluid" alt="...">
                            </div>
                            <div class="col-7">
                                <div class="card-body">
                                    <p class="card-title mt-3">Overlord Seanson 4 - Official Trailer 3 | AniTv</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                        <div class="row border-bottom justify-content-start align-items-center">
                            <div class="col-1 d-flex align-items-center justify-content-center">
                                <span class="quadratino text-white ms-2">2</span>
                            </div>
                            <div class="col-4">
                                <img src="../../assets/img/hqdefault (1).jpg" class="img-fluid" alt="...">
                            </div>
                            <div class="col-7">
                                <div class="card-body">
                                    <p class="card-title mt-3">Rent A Girlfriend Season 2 - Official Trailer | AniTV </p>
                                </div>
                            </div>
                        </div>
                    </div>
             
                    
                    <div class="card">
                        <div class="row border-bottom justify-content-start align-items-center">
                            <div class="col-1 d-flex align-items-center justify-content-center">
                                <span class="quadratino text-white ms-2">3</span>
                            </div>
                            <div class="col-4">
                                <img src="../../assets/img/visit-france.webp" class="img-fluid" alt="...">
                            </div>
                            <div class="col-7">
                                <div class="card-body">
                                    <p class="card-title mt-3">Uncle From Another World - Official Trailer 2 ! AniTV </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                        <div class="row border-bottom justify-content-start align-items-center">
                            <div class="col-1 d-flex align-items-center justify-content-center">
                                <span class="quadratino text-white ms-2">4</span>
                            </div>
                            <div class="col-4">
                                <img src="../../assets/img/travel-alone.webp" class="img-fluid" alt="...">
                            </div>
                            <div class="col-7">
                                <div class="card-body">
                                    <p class="card-title mt-3">Prima Doll - Official Trailer | AniTV </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                        <div class="row border-bottom justify-content-start align-items-center">
                            <div class="col-1 d-flex align-items-center justify-content-center">
                                <span class="quadratino text-white ms-2">5</span>
                            </div>
                            <div class="col-4">
                                <img src="../../assets/img/music-love.webp" class="img-fluid" alt="...">
                            </div>
                            <div class="col-7">
                                <div class="card-body">
                                    <p class="card-title mt-3">Shoot! Goal To The Future - Official Trailer | AniTV</p>
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

    #trailer {
  
        .ms-destra{
            overflow-y: scroll;
        }

        .col-8{
            padding: 0px !important;
        }

        img{
            position: relative;
            filter: brightness(100%)
        }

        img:nth-child(2){
            border-radius: 100%;
        }

        .ms-tag-standard{
            position: absolute;
            border: 1px solid transparent;
            z-index: 1;
        }

        .ms-tag-log-channel{
            border-radius: 100%;
            top: 2%;
            left: 5%;
        }

        .ms-tag-name-video{
            top: 4%;
            left: 9%;
        }

        .ms-tag-clock{
            font-size: 25px;
            top: 1%;
            left: 80%;
        }

        .ms-tag-clock-text{
            top: 7%;
            left: 76%;
        }

        .ms-tag-share{
            font-size: 25px;
            top: 1%;
            left: 93%;
        }

        .ms-tag-share-text{
            top: 7%;
            left: 90%;
        }

        .ms-tag-logo-youtube{
            font-size: 80px;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);

            &:hover{
                font-size: 90px;
            }
        }
        
        .ms-tag-platform-text{
            font-size: 29px;
            top: 90%;
            left: 2%;
        }

        .ms-tag-platform{
            font-size: 30px;
            top: 90%;
            left: 18%;
        }

        .col-4 .row{
            background-color: $main-color-grey;
            height: calc(100% / 5);
        }
       
        .sfondo-grigio{
            background-color: $main-color-black !important;
        }

        h5{
            margin-bottom: 0px !important;
        }

        .col-10, .col-7{
            padding: 0px !important;
        }

        .card{
            border: 0px solid transparent !important;
            background-color: $main-color-black !important;

            .img-fluid{
                border-radius: 10px;
            }

            .card-body{
                padding-left: 0px !important;
            }

        }

        .quadratino{
            cursor: pointer;
            border: 1px solid transparent;
            border-radius: 5px;
            background-color: $main-color-black;
            padding: 6px;
            margin-top: 2px;

            &:hover{
                background-color: $main-color-red;
                color: $main-color-white;
            }
        }

        .border-bottom{
            border-bottom: 1px solid black !important
        }
    }
</style>