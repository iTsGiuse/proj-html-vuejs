<script>
    
    export default {
        name: 'HeaderTop',

        methods: {
            getCurrentTime() {
                const now = new Date(); 
                const hours = now.getHours(); 
                const minutes = now.getMinutes(); 
                const seconds = now.getSeconds();  
                
                const formattedTime = `${hours}:${minutes}`;

                return formattedTime; 
            },

            updateTime() {
                const currentTimeElement = document.getElementById('current-time'); 
                currentTimeElement.textContent = this.getCurrentTime(); 
            }
        },

        mounted() {

            this.updateTime(); 
            
            setInterval(this.updateTime, 1000);
        }
    }

</script>

<template>
    <section id="header-top">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col d-flex align-items-center">
                    <div class="sfondo d-flex align-items-center"> 
                        <span class="p-3">NEWS UPDATES</span>
                    </div>
                    <div class="img me-2">
                        <img src="../../assets/img/default.webp" alt="foto-prova">
                    </div>
                    <div class="text">
                        <span id="current-time" class="me-2"></span>
                        <span class="fst-italic opacity-50">Ciao, benvenuto!</span>
                    </div>
                </div>
                <div class="col d-flex flex-end justify-content-end align-items-center">
                    <div class="text">
                        <span class="me-3"> < </span>
                        <span class="me-5"> > </span>
                    </div>
                    <div class="icon">
                        <i class="fa-brands fa-facebook me-2 p-1"></i>
                        <i class="fa-brands fa-twitter me-2 p-1"></i>
                        <i class="fa-brands fa-instagram me-2 p-1"></i>
                        <i class="fab fa-youtube p-1"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped lang="scss">

    @use '../../style/partials/variables' as *;

   #header-top {
        background-color: $main-color-red;
        height: 50px;
        width: 100%;

        .container, .row, .col{
            height: 100%;
            color: white;
        
            .sfondo{
                background-color: grey;
                height: 100%;
            }

            .img{
                max-height: 100% !important;
                max-width: 10% !important;

                img{
                    width: 100%;
                }
            }

            i{
                border-radius: 10px;
                background-color: white;
                color: $main-color-red;

                &:hover{
                    background-color: $main-color-black;
                    color: $main-color-white;
                }

            }
        }
    }

</style>