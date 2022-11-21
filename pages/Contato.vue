<template>
    <div class="corpo">
        <div class="container">
            <h1>Me siga nas redes sociais!</h1>
            <h3><a target="_blank" href="https://www.instagram.com/leeoliverttv/">Instagram das Lives</a></h3>
            <h3><a target="_blank" href="https://www.instagram.com/leeoliverp/">Instagram Pessoal</a></h3>
            <h3><a target="_blank" href="https://www.instagram.com/leeoliverfoto/">Instagram das Fotografias</a></h3>
            <h3><a target="_blank" href="https://www.twitch.tv/leeoliver">Canal da TwitchTV</a></h3>
        </div>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
a{
    text-decoration: none;
    color: white;
}
.corpo{
    align-content: center;
    display: flex;
    justify-content: center;
}
.container{
    background-image:url(~/assets/images/fundo3.png);
    color: white;
    display: flex;
    flex-direction: column;
    margin: 70px;
    padding: 30px;
    min-height: 550px;
    min-width: 1280px;
    align-items: center;
    justify-content: center;
}

</style>