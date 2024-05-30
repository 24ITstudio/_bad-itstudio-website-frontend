<template>
    <div class="body">
        <div class="putIn">
            <div class="head">
                <img src="../assets/Go Back.png" alt="">
                <div class="text" style="display: inline-block;">信息填报</div>
            </div>
            <form action="">
                <div class="name fill">
                    <img src="../assets/User.png" alt="" style="height: 30px;">
                    <input type="text" placeholder="姓名">
                </div>
                <div class="stuId fill">
                    <img src="../assets/Identification Documents.png" alt="" style="height: 30px;">
                    <input type="text" placeholder="学号">
                </div>
                <div class="tele fill">
                    <img src="../assets/Phone iphone.png" alt="" style="height: 30px;">
                    <input type="text" placeholder="电话">
                </div>
                <div class="QQ fill">
                    <img src="../assets/Flutter dash.png" alt="" style="height: 30px;">
                    <input type="text" placeholder="QQ号">
                </div>
                <button>提&nbsp;&nbsp;&nbsp;&nbsp;交</button>
            </form>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}

body {
    margin: 0;
}

input {
    outline: none;
    border: 0;
    background-color: transparent;
}

.body {
    background-color: transparent;
    background-image: url(../assets/background.png);
    background-size: 100%;
    display: flex;
    position: relative;
    height: 100vh;
}

.body .putIn {
    width: 33.9%;
    height: 65.19%;
    background-color: #D9D9D9;
    position: absolute;
    top: 17.4%;
    left: 11.25%;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.putIn .head {
    width: 84.79%;
    height: 55px;
    margin-top: 8.23%;
    display: flex;
    margin-bottom: 9.5%;
}

.putIn .head .text {
    color: var(--2, #04132D);
    font-family: "Microsoft JhengHei UI";
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: 55px;
    height: 55px;
    margin-left: 28px;
}

.putIn form {
    width: 84.79%;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    transform: translateY(-30px);
}

.putIn form .fill {
    background-color: rgba(103, 110, 123, 0.09);
    width: 100%;
    height: 45px;
    margin-bottom: 30px;
    line-height: 45px;
    display: flex;
    align-items: center;
    border-radius: 24px;
    border: 2px solid #808DA5;
}

.putIn form .fill input {
    line-height: 45px;
    color: var(--2, #04132D);
    font-family: "Microsoft JhengHei UI";
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
}

.putIn form .fill input::placeholder {
    color: #808DA5;
}

.putIn form .fill img {
    margin-left: 15px;
    margin-right: 20px;
}

.putIn form button {
    color: #FFF;
    font-family: "Microsoft JhengHei UI";
    font-size: 32px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    height: 50px;
    width: 60%;
    border: none;
    border-radius: 52px;
    background: var(--2, #04132D);
}

.putIn form button:active {
    opacity: 0.7;
}
</style>