<template>
    
</template>

<script>
export default {
    name:'VideoAutoPlay',

    data(){
        const video = ref ('video')
        const playVideo = () => {
            video.value.play();
        };
        const stopVideo = () => {
            video.value.pause();
            video.value.currentTime = 0;
        };
    }
}
</script>