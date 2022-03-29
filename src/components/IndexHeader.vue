<template>
    <div class="container">
        <div class="header-content">
            <img src="../assets/images/dc-logo.png" alt="dc logo">
            <nav>
                <ul>
                    <li v-for="(element, index) in headerNav" :key="index" :class="{active : element.current}"><a :href="element.url">{{ element.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexHeader',
    data: function() {
        return {
            headerNav: [
                {
                    text: "Characters",
                    url: "",
                    current: false,
                },
                {
                    text: "Comics",
                    url: "",
                    current: false
                },
                {
                    text: "Movies",
                    url: "",
                    current: true,
                },
                {
                    text: "Tv",
                    url: "",
                    current: false,
                },
                {
                    text: "Games",
                    url: "",
                    current: false,
                },
                {
                    text: "Collectibles",
                    url: "",
                    current: false,
                },
                {
                    text: "Videos",
                    url: "",
                    current: false,
                },
                {
                    text: "Fans",
                    url: "",
                    current: false,
                },
                {
                    text: "News",
                    url: "",
                    current: false,
                },
                {
                    text: "Shop",
                    url: "",
                    current: false,
                }
            ]
        }
    }
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