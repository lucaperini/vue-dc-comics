<template>
    <div class="relative">
        <div class=container>
            
                <div class="services-item">
                <img src="../assets/images/buy-comics-digital-comics.png" alt="">
                <p>Digital Comics</p>
                </div> 
                <div class="services-item">
                <img src="../assets/images/buy-comics-merchandise.png" alt="">
                <p>DC Merchandise</p>
                </div>  
                <div class="services-item">
                <img src="../assets/images/buy-comics-subscriptions.png" alt="">
                <p>Subscription</p>
                </div>  
                <div class="services-item">
                <img src="../assets/images/buy-comics-shop-locator.png" alt="">
                <p>Comic Shop Locator</p>
                </div>  
                <div class="services-item">
                <img src="../assets/images/buy-dc-power-visa.svg" alt="">
                <p>DC Power Visa</p>
                </div>
            
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexServices',
}
</script>

<style lang="scss" scoped>
.container {
    display:flex;
    align-items:center;
    justify-content:center;
    background-color: cornflowerblue;
    height:150px;
    width:100vw;
    
}

.services-item {
    display: flex;
    align-items: center;
    justify-content:center;
    width:14%;
    margin:0;
    
    
    img {
        width: 30%;
        display: inline-block;
        padding:.5rem;
    }
    p {
        color:white;
        text-transform:uppercase;
        font-weight:700;
        font-size:.8rem;
    }
}
.items{
    margin-left:50px;
}

</style>