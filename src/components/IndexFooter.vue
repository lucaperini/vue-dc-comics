<template>
<div>
    <footer>
        <div class="footer-top">
            <nav>
                <ul>
                    <h4>Dc Comics </h4>
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li ><a class="active" href="">Movies</a></li>
                    <li><a href="">Tv</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Collectibles</a></li>
                    <li><a href="">videos</a></li>
                <ul> 
                    <h4>Shop </h4>
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                </ul>
                </ul>
                <ul>
                    <h4>Dc</h4>
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li ><a class="active" href="">Movies</a></li>
                    <li><a href="">Tv</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Collectibles</a></li>
                    <li><a href="">videos</a></li>
                    <li><a href="">Fans</a></li>
                    <li><a href="">News</a></li>
                    <li><a href="">Shop</a></li>
                    <li><a href="">Shop</a></li>
                </ul>
                <ul>
                    <h4>Sites</h4>
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li ><a class="active" href="">Movies</a></li>
                    <li><a href="">Tv</a></li>
                    <li><a href="">Games</a></li>
                </ul>
                <div>
                    <img src="../assets/images/dc-logo-bg.png" alt="">
                </div>
            </nav>  
            <!-- <div class="footer-bottom"></div> -->
        </div>
        
    </footer>
</div>
</template>

<script>
export default {
    name:'IndexFooter'

}
</script>

<style lang="scss" scoped>
footer {
    background-image: url('../assets/images/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size:cover;
    width:100vw;
    height:350px;
    display:flex;
    justify-content:space-around;
    padding:.5rem;
    margin:0 auto;
    
    nav {
        display: flex;
        flex-basis:40%;
        margin-left:200px;
        
        
        ul{
            list-style-type: none;
            text-align:left;
            margin-right:2.5rem;
            
        }
        a {
            text-decoration:none;
            color: lightgray;
            font-size:.8rem;
        }
        h4 {
            color:white;
            font-size:1rem;
            text-transform:uppercase;
            font-weight:700;
            margin-bottom:1rem;
            margin-top:1rem;
        }
    }
    
    img {
    width:85%;
    margin-top: -100px;
    margin-left:30px;
    z-index:10;
    }
}

</style>