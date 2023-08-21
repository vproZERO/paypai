<template >
    <div class="personal__box">
        <div class="personal__content">
            <div class="personal__img">
                <img src="../../imgs/personal.svg" alt="personal">
            </div>
            <h2 class="personal__title">Personal Finances</h2>
            <p class="personal__text">Consolidate financial data from multiple sources and categorize transactions up to 2 years of history. Analyze reports to reconcile activities in your account. </p>
        </div>
        <div class="personal__content">
            <div class="personal__img">
                <img src="../../imgs/personal2.svg" alt="personal">
            </div>
            <h2 class="personal__title">Banking & Coverage</h2>
            <p class="personal__text">With our platform, you can speed up account onboarding and support ongoing payments for checking, savings, credit card, and brokerage accounts. </p>
        </div>
        <div class="personal__content">
            <div class="personal__img">
                <img src="../../imgs/personal3.svg" alt="personal">
            </div>
            <h2 class="personal__title">Consumer Payments</h2>
            <p class="personal__text">It’s easier to set up secure bank payments with us through a flow designed with the user experience in mind. Customers could instantly authenticate their account. </p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .personal__box{
        padding: 50px 165px;
        display: flex;
        align-items: center;
        gap: 30px;
    }
    .personal__content{
        width: 350px;
    }
    .personal__img{
        margin:0 auto;
        margin-bottom: 32px;
    }
    .personal__img{
        width: 106px;
        height: 106px;
    }
    .personal__title{
        text-align: center;
        font-size: 18px;
        color: #36536B;
        margin-bottom: 16px;
    }
    .personal__text{
        font-size: 15px;
        color:#6C8294;
        width: 315px;
        text-align: center;
    }
</style>