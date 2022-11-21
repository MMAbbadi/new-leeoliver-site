<template>
 <div>
    <header>
        <div class="cabecalho" id="cabecalho" >
            <NuxtLink to="Home">Home</NuxtLink>
            <NuxtLink to="Clipes">Clipes</NuxtLink>
            <div class="logo">
                <h3>
                    <img id="logo" src="~/assets/images/logo.png" alt="logo"/>
                    <NuxtLink to="Home">
                        LeeOliver.com
                    </NuxtLink>
                </h3>
            </div>
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

<style scoped>
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
a{
    text-decoration: none;
    color: white;
}
#cabecalho{
    background-color: #290338;
    background-image: linear-gradient(transparent 50%, black);
    justify-content: center;
    align-content: center;
    display: flex;
    height: 50px;
    padding: 11px;
    gap: 15px;
}

#rodape{
    background-color: #290338;
    background-image: linear-gradient(black 30%,transparent 60%);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 11px;
    height: 169px;
    width: 100%;
}
#logo{
    height: 33px;
    border-radius: 20px;
}
.logo{
    align-content: center;
    justify-content: center;
    gap: 5px;
}
</style>