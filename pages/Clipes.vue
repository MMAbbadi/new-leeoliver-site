<template>
    <div>
        <div class="corpo">
            <ul class="conteiner">
                <li v-for="video in miniVids" 
                :key="video.id"
                class="element-conteiner">
                    {{video.el}}
                    {{video.nome}}
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            miniVids:[{
                id: 1,
                el:'./assets/videos/video1.mp4',
                nome:'video1',
            },{
                id: 2,
                el:'./assets/videos/video2.mp4',
                nome:'video2'
            },{
                id: 3,
                el:'./assets/videos/video3.mp4',
                nome:'video3'
            },{
                id: 4,
                el:'./assets/videos/video4.mp4',
                nome:'video4'
            },{
                id: 5,
                el:'./assets/videos/video5.mp4',
                nome:'video5'
            },{
                id: 6,
                el:'./assets/videos/video6.mp4',
                nome:'video6'
            },{
                id: 7,
                el:'./assets/videos/video7.mp4',
                nome:'video2'
            },{
                id: 8,
                el:'./assets/videos/video8.mp4',
                nome:'video8'
            },{
                id: 9,
                el:'./assets/videos/video9.mp4',
                nome:'video9'
            }
            ]
        }
    }
}
    
// computed:{
//     videoElement(){
//         return this.$refs.video;
//     }
// }

</script>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.conteiner{
    padding: 50px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    row-gap: 15px;
    justify-items: center;
    align-items: center;
}
.element-conteiner{
    height: 75px;
    width: 175px;
    border: 1px solid;

}
</style>     