<script>

    export default {
        name: 'FooterMain',
    }

</script>

<template>

    <section id="footer-main">
        <div class="container">
            <div class="row">
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">GET STARTED</li>
                        <li class="mt-1"><a href="#">Resources</a></li>
                        <li class="mt-1"><a href="#">Tutorials</a></li>
                        <li class="mt-1"><a href="#">Examples</a></li>
                        <li class="mt-1"><a href="#">Docs</a></li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">ABOUT</li>
                        <li class="mt-1"><a href="#">Stories</a></li>
                        <li class="mt-1"><a href="#">Community</a></li>
                        <li class="mt-1"><a href="#">Blog</a></li>
                        <li class="mt-1"><a href="#">Brand Assets</a></li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">Features</li>
                        <li class="mt-1"><a href="#">Overview</a></li>
                        <li class="mt-1"><a href="#">Design</a></li>
                        <li class="mt-1"><a href="#">Code</a></li>
                        <li class="mt-1"><a href="#">Collaborate</a></li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4 fs-5">QUICK LINKS</li>
                        <li class="mt-1"><a href="#">Stories</a></li>
                        <li class="mt-1"><a href="#">Community</a></li>
                        <li class="mt-1"><a href="#">Blog</a></li>
                        <li class="mt-1"><a href="#">Brand Assets</a></li>
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