<template >
    <div class=" easy__box">
        <div class="easy__img">
            <img src="../../imgs/easy.svg" alt="easy">
        </div>
        <div class="easy__right">
            <h2 class="easy__title">Easy to implement</h2>
            <p class="easy__text">Our API comes with just a few lines of code. You’ll be up and running in no time. We built our documentation page to integrate payments functionality with ease.</p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .easy__box{
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 35px 165px;
    }
    .easy__img{
        max-width: 445px;
    }
    .easy__title{
        font-size: 48px;
        margin-bottom: 24px;
        color: #36536B;
    }
    .easy__text{
        font-size: 15px;
        width: 415px;
        color: #6C8294;
    }
</style>