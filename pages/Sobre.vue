<template>
    <div class="corpo">
        <div class="containe-informa">
            <div class="infos-pessoais">
                <h1>Sobre Mim</h1>
                <h3>Tenho 26 anos e conheci tive acesso ao meu primeiro videogame ao 5 anos, desde então sempre estiveram presentes na minha vida, me divertindo e aprendendo bastante com eles, dentre estes, o ingles.
                Além das lives eu sou formado em fotografia e faço uns jobs aqui e ali quando aparece.
                Espero que me acompanhem e interajam comigo no chat, so peço que mantenham o respeito acima de tudo</h3>
            </div>
            <div class="infos-pc">
                <h1>Config do Setup</h1>
                <ul class="pc">
                    <h3>PC</h3>
                    <li>GA-A320M-S2H</li>
                    <li>Ryzen 5 2400g</li>
                    <li>2x 8Gb HyperX Fury</li>
                    <li>GTX 1650 OC 4G</li>
                    <li>Corsair 400W</li>
                    <li>SSD Kingston A400</li>
                </ul>
                
                <ul class="entrada">
                    <h3>Camera e Mic</h3>
                    <li>Mic ROOK MG100</li>
                    <li>Cam Canon EOS T3 Rebel</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.corpo{
    align-content: center;
    display: flex;
    justify-content: center;
}
.containe-informa{
    color: white;
    display: flex;
    margin: 70px;
    padding: 30px;
    min-height: 550px;
    min-width: 1280px;
    align-items: center;
    justify-content: center;
    background-image: url('~/assets/images/fundo2.jpg');
}
.infos-pessoais{
    width: 500px;
    padding:50px;
}
.infos-pc{
    align-items: right;
    padding:50px;
}
</style>