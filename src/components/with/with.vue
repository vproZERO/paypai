<template>
    <div class="with__box">
        <div class="with__left">
            <h2 class="with__title">Who we work with</h2>
            <p class="with__text">Today, millions of people around the world have successfully connected their accounts to apps they love using our API. We provide developers with the tools they need to create easy and accessible experiences for their users. </p>
            <button class="with__btn">About Us</button>
        </div>
        <div class="wiht__right">
            <div class="with__top">
                <a class="with__imgs" href="#">
                    <img src="../../imgs/tesla.svg" alt="tesla">
                </a>
                <a class="with__imgs" href="#">
                    <img src="../../imgs/microsoft.svg" alt="microsoft">
                </a>
                <a class="with__imgs" href="#">
                    <img src="../../imgs/hp.svg" alt="hp">
                </a>
            </div>
            <div class="with__top">
                <a class="with__imgs" href="#">
                    <img src="../../imgs/tesla.svg" alt="tesla">
                </a>
                <a class="with__imgs" href="#">
                    <img src="../../imgs/microsoft.svg" alt="microsoft">
                </a>
                <a class="with__imgs" href="#">
                    <img src="../../imgs/hp.svg" alt="hp">
                </a>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .with__box{
        background-color: #1B262F;
        padding: 50px 165px;
        display: flex;
        align-items: center;
        gap: 131px;
    }
    .with__left{
        width: 445px;
    }
    .with__title{
        color: #FBFCFE;
        font-size: 48px;
        margin-bottom: 24px;
    }
    .with__text{
        color: #FBFCFE;
        margin-bottom: 32px;
        font-size: 15px;
        width: 445px; 
    }
    .with__btn{
        color: #FBFCFE;
        padding: 16px 32px 14px 32px;
        background-color: #1B262F;
        border-radius: 24px;
        border-color: #FBFCFE;
    }
    .with__top{
        display: flex;
        align-items: center;
        gap: 60px;
        margin-bottom: 39px;
    }
    .wiht__right{
        width: 536px;
    }
    .with__imgs{
        max-width: 145px;
    }
</style>