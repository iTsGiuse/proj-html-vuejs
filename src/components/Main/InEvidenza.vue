<script>

    export default {
        name: 'InEvidenza',
    }

</script>

<template>

    <section id="in-evidenza">
        <div class="ms-container">
            <div class="row pt-3 pb-3 ps-4 pe-4">
                <div class="col-3">
                    <div class="card">
                        <img src="../../assets/img/healthy-foods.webp" class="card-img-top" alt="...">
                        <span class="ms-tag-standard ms-tag-center ps-3 pe-3">Food</span>
                        <button class="ms-btn back ps-2 pe-2"><i class="fa-solid fa-chevron-left"></i></button>
                        <div class="card-body">
                            <h5 class="card-title text-center">The Best Healthy Foods in 2022</h5>
                            <p class="card-text text-center text-secondary">December 26, 2022</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <img src="../../assets/img/winter.webp" class="card-img-top" alt="...">
                        <span class="ms-tag-standard ms-tag-center ps-3 pe-3">Fashion</span>
                        <div class="card-body">
                            <h5 class="card-title text-center">The Best Healthy Foods in 2022</h5>
                            <p class="card-text text-center text-secondary">December 26, 2022</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <img src="../../assets/img/photographers-mistakes.webp" class="card-img-top" alt="...">
                        <span class="ms-tag-standard ms-tag-center ps-3 pe-3">Fashion</span>
                        <div class="card-body">
                            <h5 class="card-title text-center">The Best Healthy Foods in 2022</h5>
                            <p class="card-text text-center text-secondary">December 26, 2022</p>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <img src="../../assets/img/ideas-anime.webp" class="card-img-top" alt="...">
                        <span class="ms-tag-standard ms-first-tag ps-3 pe-3">Culture</span>
                        <span class="ms-tag-standard ms-second-tag ps-3 pe-3">Stories</span>
                        <button class="ms-btn next ps-2 pe-2"><i class="fa-solid fa-angle-right"></i></button>
                        <div class="card-body">
                            <h5 class="card-title text-center">The Best Healthy Foods in 2022</h5>
                            <p class="card-text text-center text-secondary">December 26, 2022</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

    #in-evidenza{
        background-color: $main-color-grey;

        .card-image-top{
            position: relative;
        }

        .ms-tag-standard{
            border: 1px solid transparent;
            border-radius: 10px;
            background-color: $main-color-white;
            position: absolute;
            
        }
        .ms-tag-center{
            z-index: 1;
            top: 5%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .ms-first-tag{
            z-index: 1;
            top: 5%;
            left: 60%;
            transform: translate(-50%, -50%);
        }

        .ms-second-tag{
            z-index: 1;
            top: 5%;
            left: 40%;
            transform: translate(-50%, -50%);
        }

        .ms-btn{
            cursor: pointer;
            border: 1px solid transparent;
            border-radius: 100%;
            position: absolute;
            z-index: 1;
            font-size: 20px;
            color: $main-color-red;
            background-color: $main-color-white;
        }

        .next{
            bottom: 50%;
            right: 0;
            transform: translate(-50%, 50%);
        }
        
        .back{
            bottom: 50%;
            left: 0;
            transform: translate(50%, 50%);
        }

        .card-title{
            margin-bottom: 2px !important;
        }


        
    }


</style>