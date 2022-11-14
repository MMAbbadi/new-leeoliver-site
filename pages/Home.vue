<template>
    <div class="corpo">
        <div class="container">
            <div class="carrossel">
                <button @click="current=current==0 ? 0: current-1"
                class="btn-voltar">
                    <img src="" :alt="voltar">voltar
                </button>
                <ul class="video-conteiner">
                    <li v-for="video in videos" 
                    :key="video.id"> 
                        {{video.el}}
                    </li>
                </ul>
                <button 
                @click="current = current === videos.lenght ? current :current +1"
                class="btn-avancar">
                    <img src="" :alt="voltar">avancar
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
            videos:[{
                id:1,
                el: './assets/videos/video1.mp4',
                nome: 'video1'
            },{
                id:2,
                el: './assets/videos/video2.mp4',
                nome: 'video2'
            },{
                id:3,
                el: './assets/videos/video3.mp4',
                nome: 'video3'
            }
            ],
            current: 0,
        }
    },
}
</script>

<style scoped>
.carrossel{
    display:flex;
    align-items: center;
    justify-content: center;
    gap: 40px;

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
    margin: 50px;
    min-height: 650px;
    justify-items: center;
    align-items: center;
}
</style>