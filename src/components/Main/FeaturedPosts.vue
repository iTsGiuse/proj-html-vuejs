
<script>

    export default {
        name: 'FeaturedPosts',
    }

</script>

<template>

    <section id="featured-posts">
       <div class="container">
        <div class="row mb-2">
            <div class="col">
                <div class="d-flex">   
                    <h3 class="pt-2">FEATURED POSTS</h3>
                </div>
            </div>
            <div class="col">
                <div class="d-flex justify-content-end">
                    <button class="ms-btn p-3 me-3"><i class="fa-solid fa-chevron-left"></i></button>
                    <button class="ms-btn p-3"><i class="fa-solid fa-angle-right"></i></button>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-4">
                <div class="card text-center">
                    <img src="../../assets/img/ideas-anime.webp" class="card-img-top" alt="...">
                    <span class="ms-tag-standard ms-tag-standard-left ps-3 pe-3">Culture</span>
                    <span class="ms-tag-standard ms-tag-standard-right ps-3 pe-3">Stories</span>
                    <div class="card-body">
                        <h5 class="card-titlem mb-0">Live Ideas You Might Be Anime</h5>
                        <p class="small">December 26, 2022</p>
                        <p class="card-text small">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti rem ab blanditiis dolorem </p>
                        <a href="#" class="btn btn-danger pe-5 ps-5">Read more</a>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card text-center">
                    <img src="../../assets/img/visit-france.webp" class="card-img-top" alt="...">
                    <span class="ms-tag-standard ms-tag-standard-left ps-3 pe-3">Lifestyle</span>
                    <span class="ms-tag-standard ms-tag-standard-right ps-3 pe-3">Travel</span>
                    <div class="card-body">
                        <h5 class="card-titlem mb-0">Reasons To Visit France</h5>
                        <p class="small">December 26, 2022</p>
                        <p class="card-text small">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti rem ab blanditiis dolorem </p>
                        <a href="#" class="btn btn-danger pe-5 ps-5">Read more</a>
                    </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card text-center">
                    <img src="../../assets/img/travel-alone.webp" class="card-img-top" alt="...">
                    <span class="ms-tag-standard ms-tag-standard-left ps-3 pe-3">Stories</span>
                    <span class="ms-tag-standard ms-tag-standard-right ps-3 pe-3">Travel</span>
                    <div class="card-body">
                        <h5 class="card-titlem mb-0">Traveling Alone Is Awesome</h5>
                        <p class="small">December 26, 2022</p>
                        <p class="card-text small">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti rem ab blanditiis dolorem </p>
                        <a href="#" class="btn btn-danger pe-5 ps-5">Read more</a>
                    </div>
                </div>
            </div>
        </div>
       </div>
    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

    #featured-posts{

        .col-4:nth-child(1){
            padding-left: 11px !important;
        }
        .col-4{
            padding: 6px !important;
        }

        .ms-btn{
            border: 1px solid transparent;
            border-radius: 100%;
            background-color: $main-color-black;
            color: $main-color-white;
            padding: 5px;

            &:hover{
                background-color: $main-color-red;
            }
        }

       .card-body{
            background-color: $main-color-grey;
       } 

       .btn{
        border-radius: 20px !important;
        border: 1px solid transparent !important;
         
        &:hover{
            background-color: $main-color-black;
            color: $main-color-white !important;
         }
       }

       .card-img-top{
        position: relative;
       }

       .ms-tag-standard{
        position: absolute;
        z-index: 1;
        top: 2%;
        background-color: $main-color-white;
        border: 1px solid transparent;
        border-radius: 10px;
       }

       .ms-tag-standard-left{
        left: 28%;
       }

       .ms-tag-standard-right{
        left: 52%;
       }

       img{
        filter: brightness(100%)
       }
    }

        
</style>