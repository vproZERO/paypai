<template>
    <div class="footer__Box">
        <div class="footer__logo">
            <img src="../../imgs/logo2.svg" alt="logo2">
        </div>
        <ul class="footer__list">
            <li class="footer__item">Pricing</li>
            <li class="footer__item">About</li>
            <li class="footer__item">Contact</li>
        </ul>
        <div class="footer__icons">
            <a class="footer__icon" href="#">
                <img src="../../icons/facebook.svg" alt="facebook">
            </a>
            <a class="footer__icon" href="#">
                <img src="../../icons/twitter.svg" alt="twitter">
            </a>
            <a class="footer__icon" href="#">
                <img src="../../icons/in.svg" alt="in">
            </a>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .footer__Box{
        background-color: #1B262F;
        padding: 35px 165px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .footer__list{
        display: flex;
        gap: 40px;
        align-items: center;
    }
    .footer__item{
        color: #FBFCFE;
        font-size: 15px;

    }
    .footer__icons{
        display: flex;
        align-items: center;
        gap: 24px;
    }
</style>