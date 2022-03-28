<template>
    <div class="container">
        <div class="header-content">
            <img src="../assets/images/dc-logo.png" alt="">
            <nav>
                <ul>
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
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexHeader',
}
</script>

<style lang="scss" scoped>
.container {
    width:100vw;
    height: 100px;
    border-bottom:1px solid black;
    margin:0 auto;
    display:flex;
    justify-content:center;
    
    padding:.3rem;
    

    }
.header-content { 
    display: flex;
    width:100%;
    justify-content: space-around;
        img {
            padding:.4rem;
            margin-left:10%;
        }
        
        ul {
            
            margin-top:2rem;
            
        li {
            display:inline-block;
            list-style-type: none;
        }
        
        a {
        text-decoration: none;
        text-transform:uppercase;
        color:gray;
        font-size: .7rem;
        font-weight:700;
        margin-right:1rem;
        }
        a:active, a.active, a:hover{
        color:cornflowerblue;
        border-bottom:5px solid cornflowerblue;
        padding-bottom:37px;
        }
        a:focus{
            color:cornflowerblue;
        }
    }
} 
</style>