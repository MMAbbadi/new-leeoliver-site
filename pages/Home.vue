<template>
    <div>
        <div class="streams">

            <div id="btnvoltar" class="botao">
                <button class="voltar" @click="">
                    voltar
                </button>
            </div>

            <ul class="lives">
                <li class="livestream">
                    <h3 class="titulo-live">V1</h3>
                    <video controls src=""></video>
                </li>
                <li class="livestream">
                    <h3 class="titulo-live">V2</h3>
                    <video controls src=""></video>
                </li>
                <li class="livestream">
                    <h3 class="titulo-live">V3</h3>
                    <video controls src=""></video>
                </li>
            </ul>

            <div id="btnavancar" class="botao">
                <button class="avancar" @click="">
                    avancar
                </button>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>

ul{
    list-style: none;
}

.streams{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 15px;
}

.lives{
    height: 864px;
    width: 960px;
    position: relative;
}

.livestream{
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    position: absolute;
}

</style>