<template>
    <div class="relative">
        <div class="section-footer-social">
            <div>
                <a href="" class="sign-up-btn">Sign Up Now!</a>
            </div>
                <div class="clearfix prova">
                    <div class="title">
                        <h4>Follow US!</h4>
                    </div>
                    <ul>
                        <li><a href=""><img src="../assets/images/footer-twitter.png" alt=""></a></li>
                        <li><a href=""><img src="../assets/images/footer-youtube.png" alt=""></a></li>
                        <li><a href=""><img src="../assets/images/footer-pinterest.png" alt=""></a></li>
                        <li><a href=""><img src="../assets/images/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    
</template>

<script>
export default {
    name: 'IndexFooterSocial',
}
</script>

<style lang="scss" scoped>
.container {
    display:flex;
    align-items:center;
    justify-content:center;
    
    color:white;
    font-size:.8rem;
    font-weight:700;
    height:100px;
    width:100vw;
    position:relative;
}
ul {
    display:flex;
    list-style-type: none;
    li{
    margin-right:1rem;
    }
}

h4{
    margin-top:.5rem;
    font-size:1.2rem;
}
.section-footer-social{
    
    background-color:rgb(48, 48, 48);
    height:100px;
    width:100%;                                 
    display:flex;
    justify-content:space-around;
    
    h4 {
        display:inline-block;
    }
    .sign-up-btn{
        color:rgb(59, 116, 232);
        font-size:1rem;
        font-weight:700;
        padding:.8rem;
        border: 1px solid white;
        text-decoration:none;
        align-items:center;
        text-transform: uppercase;
        vertical-align: middle;
        line-height:6rem;
        margin-left:110px;
        
    }
}

.prova{
    margin-top:2rem;
}

.social {
    
    width:100%;
}
.title {
    float:left;
    margin-right:1.5rem;
    text-transform:uppercase;
    color:rgb(59, 116, 232);
    font-size:1rem;
}
.relative{
    position:relative;
    }
</style>