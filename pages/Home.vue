<template>
    <div class="corpo">
        <div class="container">
            <div class="carrossel">
                <button 
                v-show = "current >= 1" 
                @click="current--" 
                class="btn" 
                id="btn-voltar">
                    <img src="~/assets/images/seta.png" alt="voltar">
                </button>
                <ul class="video-conteiner">
                    <li>
                        <iframe  v-show="current === 1" class="video" width="560" height="315" src="https://www.youtube.com/embed/JQKgPmdKutI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </li>
                    <li>
                        <iframe v-show="current === 2" class="video" width="560" height="315" src="https://www.youtube.com/embed/b02DhGmyMfw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </li>
                    <li>
                        <iframe v-show="current === 3" class="video" width="560" height="315" src="https://www.youtube.com/embed/QUM8C6ctCH4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </li>
                </ul>
                <button 
                v-show="current <= 3"
                @click="current++"
                class="btn" id="btn-avancar">
                    <img src="~/assets/images/seta.png" alt="avancar">
                </button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Home',
    data(){
        return{
            current: 1,
        }
    },
    methods:{

    }
}
</script>

<style scoped>
.carrossel{
    padding: 130px 0;
    display:flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
}

#btn-voltar{
    transform: rotateY(180deg);
}
</style>

<style>
*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
}

ul{
    list-style: none;
}

.corpo{    
    min-height: 750px;
    justify-items: center;
    align-items: center;
    background-image: url(~/assets/images/fundo1.jpg);
}
</style>