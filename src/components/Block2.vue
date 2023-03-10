<template>
    <div class="container">
        <img width="310" height="342" src="../../public/il1.png" alt="">
        <img width="310" height="342" src="../../public/il2.png" alt="">
        <img width="310" height="342" src="../../public/il3.png" alt="">
    </div>
</template>

<script>
export default {
        name: "TheBlock2",
        props: {
            
        }
    }
</script>

<style scoped>
    .container{
        width: 66%;
        display: flex;
        justify-content: space-between;
        margin: auto;
        margin-top: 132px;
        margin-bottom: 119px;
    }
    img{
        transition: 0.3s;
    }
    img:hover{
        transform: scale(1.2);
    }
</style>