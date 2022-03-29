<template>
<div>
    <footer>
        <div class="footer-top">
            <nav>
                <ul>
                    <h4>Dc Comics </h4>
                    <li v-for="(element, index) in footerNavComics" :key="index"><a href="element.url">{{ element.text }}</a></li>
                        <ul> 
                            <h4>Shop </h4>
                            <li v-for="(element, index) in footerNavShop" :key="index"><a href="element.url">{{ element.text }}</a></li>
                            
                        </ul>
                </ul>
                <ul>
                    <h4>Dc</h4>
                    <li v-for="(element, index) in footerNavDC" :key="index"><a href="element.url">{{ element.text }}</a></li>
                    
                </ul>
                <ul>
                    <h4>Sites</h4>
                    <li v-for="(element, index) in footerNavSites" :key="index"><a href="element.url">{{ element.text }}</a></li>
                    
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
    name:'IndexFooter',
    data: function() {
        return {
            footerNavComics: [
                {
                    text: "Characters",
                    url:"#",

                },
                {
                    text:"Comics",
                    url:"#",

                },
                {
                    text: "Movies",
                    url: "#",

                },
                {
                    text: "TV",
                    url: "#",

                },
                {
                    text: "Games",
                    url: "#",

                },
                {
                    text: "Videos",
                    url: "#",

                },
                {
                    text:"News",
                    url: "#",

                }, 
            ],
            footerNavShop: [
                {
                    text: "Shop DC",
                    url:"#",

                },
                {
                    text:"Shop DC Collectibles",
                    url:"#",

                },
            ],
            footerNavDC: [
                {
                    text: "Terms Of Use",
                    url:"#",

                },
                {
                    text:"Privacy Policy (New)",
                    url:"#",

                },
                {
                    text: "Add Choices",
                    url: "#",

                },
                {
                    text: "Advertising",
                    url: "#",

                },
                {
                    text: "Jobs",
                    url: "#",

                },
                {
                    text: "Subscriptions",
                    url: "#",

                },
                {
                    text:"Talent Workshop",
                    url: "#",

                }, 
                {
                    text: "CPSC Certificates",
                    url: "#",

                },
                {
                    text: "Ratings",
                    url: "#",

                },
                {
                    text: "Shop Help",
                    url: "#",

                },
                {
                    text:"Contact Us",
                    url: "#",

                }, 
            ],
            footerNavSites: [
                {
                    text: "DC",
                    url:"#",

                },
                {
                    text:"MAD Magazine",
                    url:"#",

                },
                {
                    text: "DC Kids",
                    url:"#",

                },
                {
                    text:"DC Universe",
                    url:"#",

                },
                {
                    text:"DC Power Visa",
                    url:"#",

                },
            ],
        }
    }

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
            margin-right:1rem;
            
        }
        a {
            text-decoration:none;
            color: lightgray;
            font-size:.6rem;
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