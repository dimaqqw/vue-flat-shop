<template>
    <div class="block3">
        <h2>Пройдите небольшой опрос и узнайте,<br/>как <span>избежать рисков</span> при продаже или<br/>покупке квартиры</h2>
        <div class="quiz">
            <div class="leftside">
                <img src="../../public/quiz.png" alt="quiz"/>
            </div>
            <div class="rightside">
                <p>Время прохождения опроса <b>3 минуты</b></p>
                <div class="start">
                    <h3>Хочу безопасно и легко<br/>продать или купить квартиру</h3>
                    <div class="start-button">
                        Начать
                    </div>
                </div>
                <div class="list">
                    <p>После завершения опроса вы получите PDF<br/>файл c содержащий:</p>
                    <ol>
                        <li>Список документов, необходимых в вашем<br/>конкретном случае.</li>
                        <li>Разъяснение сложных терминов<br/>«на пальцах».</li>
                        <li>Оценку возможных рисков.</li>
                    </ol>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "TheBlock3",
        props: {
            
        }
    }
</script>

<style scoped>
/*      GLOBAL     */
@font-face {
    font-family: "LatoFont"; 
    src: url("../../public/lato_font/latoregular.ttf") format("truetype"); 
    font-style: normal; 
    font-weight: normal; 
    } 
a{
        color: #03073C;
        font-family: LatoFont;
        font-size: 20px;
        font-weight: 400;
        line-height: 24px;
        letter-spacing: 0em;   
    }
h2{
        font-size: 45px;
        line-height: 59px;
        font-family: LatoFont;
        text-align: center;
    }
h2 span{
        border: 1px solid rgba(212, 75, 75, 1);
        border-radius: 20px;
        padding-left: 13px;
        padding-bottom: 10px;
        padding-right: 13px;
        height: 5px;
    }
h3{
    font-family: LatoFont;
    font-style: normal;
    font-weight: 400;
    font-size: 35px;
    line-height: 45px;
    color: #03073C;
    }
p, ol, li{
    font-family: LatoFont;
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 26px;
    color: #475658;
    }
b{
    color: rgba(212, 75, 75, 1);
    }
/*      BLOCK3     */
    div.block3{
        width: 100%;
        height: 1194px;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        margin-bottom: 170px;
    }
/*    QUIZ    */
    div.quiz{
        width: 1040px;
        height: 710px;
        border: 1px solid #F2F2F2;
        box-shadow: 1px 3px 20px rgba(240, 240, 240, 0.8);
        border-radius: 20px;
        display: flex;
    }
/*    LEFTSIDE    */
    .leftside{
        width: 290px;
        height: 100%;
        background: rgba(212, 75, 75, 1);
        border-radius: 20px 0 0 20px;
        display: flex;
        align-items: flex-end;
        justify-content: flex-end;
    }
/*    RIGHTSIDE    */
    .rightside{
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        margin-left: 70px;
    }
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
    }
    .rightside ol{
        margin-top: 20px;
    }
</style>