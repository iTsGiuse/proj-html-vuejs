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
                        <li class="mb-4">GET STARTED</li>
                        <li class="mt-1">Resources</li>
                        <li class="mt-1">Tutorials</li>
                        <li class="mt-1">Examples</li>
                        <li class="mt-1">Docs</li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4">ABOUT</li>
                        <li class="mt-1">Stories</li>
                        <li class="mt-1">Community</li>
                        <li class="mt-1">Blog</li>
                        <li class="mt-1">Brand Assets</li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4">Features</li>
                        <li class="mt-1">Overview</li>
                        <li class="mt-1">Design</li>
                        <li class="mt-1">Code</li>
                        <li class="mt-1">Collaborate</li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <ul class="text-white">
                        <li class="mb-4">QUICK LINKS</li>
                        <li class="mt-1">Stories</li>
                        <li class="mt-1">Community</li>
                        <li class="mt-1">Blog</li>
                        <li class="mt-1">Brand Assets</li>
                   </ul> 
                </div>
                <div class="col-2 mt-5">
                   <label class="text-white fs-5">SUBSCRIBE TO NEWSLETTER</label>
                   <input class="mt-3" type="text" placeholder="Inserisci la tua email">
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
        }

        .ms-btn{
          border: 1px solid transparent;
          border-radius: 10px;
          background-color: $main-color-black;  
        }
    }

   

</style>