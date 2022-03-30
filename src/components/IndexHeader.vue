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
@import "../assets/scss/partials/_variables.scss";

.container {
    width:75%;
    height: 100px;
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
        color:$bgDarkColor;
        font-size: .7rem;
        font-weight:700;
        margin-right:1rem;
        }
        a:active, a.active, a:hover{
        color:$primaryColor;
        border-bottom:5px solid $primaryColor;
        padding-bottom:40px;
        }
        a:focus{
            color: $primaryColor;
        }
    }
} 
</style>