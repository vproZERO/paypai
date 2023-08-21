<template>
    <div class="start__box">
        <div class="start__left">
            <h2 class="start__title">Start building with our APIs for absolutely free.</h2>
            <div class=" inputs__box">
                <input type="email" class="form-control start__input" placeholder="Enter email address" >
                <button class="start__btn">Schedule a Demo</button>
            </div>
            <p class="start__text">Have any questions? Contact Us</p>
        </div>
        <div class="start__right">
            <img src="../../imgs/telefon.svg" alt="telefon">
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .start__box{
        padding: 35px 165px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .start__title{
        font-size: 62px;
        width: 546px;
        color: #36536B;
        margin-bottom: 21px;
    }
    .inputs__box{
        width: 445px;
        height: 48px;
        display: flex;
        border-radius: 24px;
        margin-bottom: 16px;
    }
    .start__input{
        border: none;
        padding: 10px 27px 10px 27px;
    }
    .start__btn{
        display: block;
        padding: 14px 26px 16px 24px;
        border:none;
        color: #fff;
        background-color: #BA4270;
        border-radius: 24px;
        width: 273px;
    }
    .start__right{
        width: 363px;
        height: 500px;
    }
    .start__text{
        color: #6C8294;
        margin-left: 27px;
    }
</style>