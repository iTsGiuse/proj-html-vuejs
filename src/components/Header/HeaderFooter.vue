<script>

    export default {
        name: 'HeaderFooter',
    }

</script>

<template>
    <section id="header-footer">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-2">
                    <i class="fa-solid fa-bars"></i>
                </div>
                <div class="col-8 d-flex justify-content-center">
                    <ul class="mt-2">
                        <li> <a href="#"> <i class="fa-solid fa-house"> HOME </i> </a> </li>
                        <li> <a href="#"> <i class="fa-solid fa-suitcase"> LIFESTYLE <i class="fa-solid fa-chevron-down"></i> </i> </a> </li>
                        <li> <a href="#"> <i class="fa-solid fa-book-open-reader"> STORIES <i class="fa-solid fa-chevron-down"></i> </i> </a> </li>
                        <li> <a href="#"> <i class="fa-solid fa-book"> PAGES <i class="fa-solid fa-chevron-down"></i> </i> </a> </li>
                        <li> <a href="#"> <i class="fa-solid fa-user"> ABOUT US </i> </a> </li>
                    </ul>
                </div>
                <div class="col-2 text-end">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
        </div>
    </section>  
</template>

<style scoped lang="scss">
    .container{
        border-top: 0.1px solid grey;
        border-bottom: 1px solid transparent;
    
        ul{
            list-style: none;
            display: flex;
            gap: 20px;
            cursor: pointer;
            font-size: 18px;
            
            a{
                color: black;
                text-decoration: none;
            }
        }
    }

</style>        