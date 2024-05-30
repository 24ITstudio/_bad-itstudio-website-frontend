<template>
    <!-- <div class="element"> -->
    <!-- <div class="slide-wrapper"> -->
    <!-- <div class="slide"> -->
    <!-- <div class="overlap-2"> -->
    <!-- <div>这是Overlap</div>
                    <div>这是OverlapGroup</div> -->
    <!-- <Overlap /> -->
    <!-- <OverlapGroup /> -->
    <!-- </div> -->
    <!-- </div> -->
    <!-- </div> -->
    <!-- </div> -->
    <div class="back">
        <div class="head">
            导航栏组件
        </div>
        <div class="content">
            <div class="back_left">
                <div class="left_board">
                    <div class="board_head">
                        <div class="text_1">
                            留言板
                        </div>
                    </div>
                    <div class="board_content">
                        <textarea class="dotted-textarea" rows="10"></textarea>
                    </div>

                </div>
            </div>
            <div class="back_right">
                留言块
            </div>
        </div>


    </div>
</template>

<script>
// import { defineProps } from "vue";
// import Overlap from "./Overlap.vue";
// import OverlapGroup from "./OverlapGroup.vue";

export default {
    name: "msagPage",
    components: {
        // Overlap,
        // OverlapGroup,
    },
};
</script>
<!-- 单选10 2
不定项 10 3
主观 2 50分 -->

<style>
.back{
    background-color:beige;
    /* width: 1920px; */
    /* height: 1080px; */
    width: 100%;
    height: 100vh;
    background-image: url('../assets/backImg.jpg');
    background-size: 100% 100%;
    position: fixed;
    display: flex;
    flex-direction: column;
}
.content{
    height: 90%;
    margin-top: 2%;
    display: flex;
    flex-direction: row;
}
.back_left{
    background-color: #04132c;
    width: 30%;
    height: 100%;
    /* width: 578px; */
    /* height: 1080px; */
    /* margin-top: px; */
    margin-left: 0%;
    margin-right: 0%;
    /* margin-top: -10%; */
}

.left_board{
    background-color: #d9d9d9;
    width: 50%;
    height: 70%;
    margin-left: 40%;
    margin-top: 20%;
    

    /* width: 351px; */
    /* height: 695px; */
    /* margin-left: 137px; */
    
    /* margin: 150px 90px 235px 137px; */
    /* margin-top: 40px; */
}

.board_head{
    height: 70px;
    line-height: 80px;
}

.text_1{
    margin-left: -100px;
    font-size: 25px;
    font-family: "Microsoft New Tai Lue-Bold", Helvetica;
    font-weight: bold;
}

.board_content{
    display: flex;
        justify-content: center;
        align-items: center;
        /* height: 100vh; */
}

.dotted-textarea {
    width: 100%;
    /* max-width: 600px; */
    /* height: 200px; */
    padding: 10px;
    /* outline: none; */
    border: none;
    resize: none;
    font-size: 16px;
    line-height: 1.5;
    /* 调整行间距 */
    background: repeating-linear-gradient(to bottom,
            transparent,
            transparent 28px,
            #000 28px,
            #000 29px);
    /* 横线样式 */
}


.back_right {
    background-color:#d9d9d91a;
    width: 70%;
    height: 100%;
    /* width: 1342px; */
    /* height: 1080px; */
}





.element {
    background-color: transparent;
    display: flex;
    flex-direction: row;
    justify-content: center;
    width: 100%;
}

.element .slide-wrapper {
    height: 1080px;
    width: 1920px;
    background-color: aqua;
}

.element .slide {
    /* background-image: url(./slide-16-9-2.svg); */
    background-position: 50% 50%;
    background-size: cover;
    height: 1080px;
    overflow: hidden;
    /* background-color: blueviolet; */
}

.element .overlap-2 {
    height: 1080px;
    position: relative;
    width: 1923px;
}

</style>