<template>
    <div class="container">
        <div class="wrapper">
            <div class="text-container">
                <p>Запутались в сложных терминах и документах?</p>
                <h1>Узнайте, какие <span>документы</span><br/>подготовить и что учесть<br/>при <span>продаже и покупке</span><br/>квартиры</h1>
                <a href="">Хочу узнать больше</a>
            </div>    
            <img height="500" src="../../public/flat.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
        name: "TheBlock1",
        props: {
            
        }
    }
</script>

<style scoped>
    .container{
        width: 100%;
        height: 536px;
        background-color: #D44B4B;
    }
    .wrapper{
        position:relative;
        width: 73%;
        height: 100%;
        margin: auto;
        display: flex;
        align-items: center;
    }
    img{
        position: absolute;
        bottom: -2px;
        right: -190px;
    }
    @font-face {
        font-family: "LatoFont"; 
        src: url("../../public/lato_font/latoregular.ttf") format("truetype"); 
        font-style: normal; 
        font-weight: normal; 
    } 
    .text-container{
        font-family: 'LatoFont';
        font-style: normal;
        font-weight: 400;
        height: 80%;
        font-size: 16px;
        line-height: 26px;
        color: #fff;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
    }
    h1{
        font-size: 45px;
        line-height: 59px;  
    }
    h1 span{
        border: 1px solid white;
        border-radius: 20px;
        padding-left: 13px;
        padding-bottom: 10px;
        padding-right: 13px;
        height: 5px;
    }
    a{
        color: grey;
        /* padding: 19.5px 46.5px 24.5px; */
        display: flex;
        width: 400px;
        height: 72px;
        background-color: #fff;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
    }
</style>
