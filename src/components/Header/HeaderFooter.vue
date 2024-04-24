<script>

    export default {
        name: 'HeaderFooter',
        props: ['naviga']
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
                        <li v-for="item in naviga" :key="item"> <a href="#"> <span v-html="item.icon"></span> {{ item.text }} <span v-html="item.menu"></span> </a> </li>
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
    
    @use '../../style/partials/variables' as *;

    .container{
        border-top: 0.1px solid grey;
        border-bottom: 1px solid transparent;
    
        ul{
            list-style: none;
            display: flex;
            gap: 20px;
            cursor: pointer;
            
            a{
                color: black;
                text-decoration: none;

                &:hover{
                    color: $main-color-red !important;
                }
            }
        }
    }

</style>        