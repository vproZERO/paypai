<template>
    <div class="simple__box">
        <div class="simple__left">
            <h2 class="simple__title">Simple UI & UX</h2>
            <p class="simple__text">Our pre-built form is easy to integrate in your app or website’s checkout flow and designed to optimize conversion. </p>
        </div>
        <div class="simple__right">
            <div class="simple__img">
                <img src="../../imgs/simple.svg" alt="simple">
            </div>
            <div class="simple__img">
                <img src="../../imgs/simple2.svg" alt="simple">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .simple__box{
        padding: 0px 165px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .simple__title{
        font-size: 48px;
        margin-bottom: 24px;
        color: #36536B;
    }
    .simple__text{
        font-size: 15px;
        width: 430px;
        color: #6C8294;
    }
    .simple__img{
        width: 313px;
        height: 500px;
    }
    .simple__right{
        display: flex;
    }
</style>