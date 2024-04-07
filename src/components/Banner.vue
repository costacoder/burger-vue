<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default{
    name:"Banner"
}
</script>

<style scoped>

    #main-banner{
        background-image: url('/public/img/burger.jpg');
        background-position: 0 70%; /* desloca no eixo Y */
        background-size: cover; /* deixa a imagem aparecendo no máximo possível da área disponível */ 
        height: 80vh;
        display: flex;
        align-items: center; /* alinhamento vertical */
        justify-content: flex-start;        
    }

    #main-banner h1{
        color: #FFF;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
</style>