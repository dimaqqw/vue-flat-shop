<template>
    <div class="header">
        <div class="header-container">
            <div class="logo-container">
                <a href="">
                    <img width="83" height="91" class="logo" src="../../public/Group_257.svg" alt="Лого">
                </a>
            </div>
            <div class="refs">
                <a href="">{{ref1}}</a>
                <a href="">{{ref2}}</a>
                <a href="">
                    <img width="28" height="28" class="call" src="../../public/Vector.svg" alt="Трубка">
                    {{ number }}
                </a>
                <a class="recall" href="">Перезвоните мне</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "TheHeader",
        props: {
            ref1: String,
            ref2: String,
            number: String
        }
    }
</script>

<style scoped>
    div.header{
        width: 100%;
        height: 136px;
    }
    div.header .header-container{
        display: flex;
        width: 73%;
        margin: auto;
        justify-content: space-between;
    }
    .logo-container{
        height: 134px;
        display: flex;
        align-items: center;
    }
    .refs{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
    }
    @font-face {
    font-family: "LatoFont"; 
    src: url("../../public/lato_font/latoregular.ttf") format("truetype"); 
    font-style: normal; 
    font-weight: normal; 
    } 
    a{
        color: #475658;
        display: flex;
        align-items: center;
        font-family: LatoFont;
        font-size: 20px;
        font-weight: 400;
        line-height: 24px;
        letter-spacing: 0em;
        text-align: center;
    }
    .refs .recall{
        color: #121761;
        border: 1px solid #121761;
        border-radius: 10px;
        height: 56px;   
        padding: 10px 55px 13px 55px;
        transition: 0.2s;
    }
    .refs .recall:hover{
        color: #D44B4B;
        border: 1px solid #D44B4B;
    }
    
</style>