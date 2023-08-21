<template >
    <div class="d-flex  header__box">
        <a class="header__logo" href="#">
           <img src="../../imgs/logo.svg" alt="logo"> 
        </a>
        <ul class="header__list d-flex ">
            <li class="header__item">Pricing</li>
            <li class="header__item">About</li>
            <li class="header__item">Contact</li>
        </ul>
        <button class="header__btn">Schedule a Demo</button>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .header__box{
        padding: 35px 165px ;
        align-items: flex-start;
        justify-content: space-between;
    }
    .header__list{
        gap: 40px;
    }
    .header__item{
        color: #36536B;
        cursor: pointer;
    }
    .header__btn{
        padding: 15px 25px;
        border: none;
        background-color: #DA6D97;
        color: #FBFCFE;
        border-radius: 24px;
    }
    
</style>