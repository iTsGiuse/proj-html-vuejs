<script>

    export default {
        name: 'FooterMain',
        props: ['start', 'info', 'add', 'saveTime'],
    }

</script>

<template>

    <section id="footer-main">
        <div class="container">
            <div class="row">
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">GET STARTED</li>
                        <li class="mt-1" v-for="item in start" :key="item"><a href="#">{{ item }}</a></li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">ABOUT</li>
                        <li class="mt-1" v-for="item in info" :key="item"><a href="#">{{ item }}</a></li>

                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">Features</li>
                        <li class="mt-1" v-for="item in add" :key="item"><a href="#">{{ item }}</a></li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">QUICK LINKS</li>
                        <li class="mt-1" v-for="item in saveTime" :key="item"><a href="#">{{ item }}</a></li>

                   </ul> 
                </div>
                <div class="col-4 mt-5">
                   <label class="text-white fs-5">SUBSCRIBE TO NEWSLETTER</label>
                   <input class="mt-3 d-block" type="text" placeholder="Inserisci la tua email">
                   <button class="ms-btn text-white pt-3 pb-3 ps-5 pe-5 mt-3">SUBSCRIBE</button>
                </div>
            </div>
        </div>

    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

    #footer-main{
        background-color: $main-color-red;

        ul{
            list-style: none;
            cursor: pointer;

            a{
                color: $main-color-white;
                text-decoration: none;

                &:hover{
                    color: $main-color-black !important;
                }
            }
        }

        .ms-btn{
          border: 1px solid transparent;
          border-radius: 10px;
          background-color: $main-color-black;  
          width: 80%;

            &:hover{
                background-color: $main-color-white;
                color: $main-color-red !important;
            }
        }

        input{
            width: 80%;
            height: 30%;
        }

    }

</style>