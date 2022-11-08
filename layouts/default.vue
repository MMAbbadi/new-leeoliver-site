<template>
 <div>
    <header>
        <div class="cabecalho" id="cabecalho" >
            <NuxtLink to="Home">Home</NuxtLink>
            <NuxtLink to="Clipes">Clipes</NuxtLink>
            <div class="logo"><img src="" alt="">LeeOliver.com</div>
            <NuxtLink to="Sobre">Sobre</NuxtLink>
            <NuxtLink to="Contato">Contato e Midias</NuxtLink>
        </div>
    </header>

    <Nuxt />

    <footer  id="rodape">
        <div class="rodape">
            <p>Me siga nas redes sociais e na TwitchTV para saber quando entrar ao vivo!</p>
        </div>
    </footer>
 </div>
    
</template>

<script>
export default {
    
}
</script>

<style>
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
#cabecalho{
    background-color: green;
    justify-content: center;
    align-content: center;
    display: flex;
    height: 50px;
    padding: 11px;
    gap: 15px;
}

#rodape{
    background-color: green;
    height: 55px;
    display: flex;
    align-content: center;
    justify-content: center;
    padding: 11px;
}
</style>