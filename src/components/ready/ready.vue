<template>
    <div class="ready__box">
        <div class="ready__left">
            <h2 class="ready__title">Ready to start?</h2>
        </div>
        <div>
            <div class=" inputs__box">
                <input type="email" class="form-control start__input" placeholder="Enter email address" >
                <button class="start__btn">Schedule a Demo</button>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .ready__box{
        padding: 50px 165px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .ready__title{
        font-size: 48px;
        color: #36536B;
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
</style>