<template>
    <div class="start-button">
        Начать
    </div>
</template>

<script>
    export default {
        name: "ButtonBlock3",
        props: {
            
        }
        
    }
</script>

<style scoped>
    .start-button{
        width: 460px;
        height: 72px;
        background: #D44B4B;
        box-shadow: 2px 2px 5px #F0F0F0;
        border-radius: 10px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 30px;

        font-family: LatoFont;
        font-style: normal;
        font-weight: 700;
        font-size: 23px;
        line-height: 28px;
        text-align: center;
        color: #FFFFFF;
        transition: .2s;
    }
    .start-button:hover{
        font-size: 30px;
    }
</style>