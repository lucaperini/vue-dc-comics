<template>
    <div class="comic-element">
        <img :src="comicObject.thumb" :alt="comicObject.series">
        <h4>{{comicObject.series}}</h4>
    </div>
</template>

<script>
export default {
    name: "IndexMainComics",
    props: {'comicObject' : Object},
}
</script>

<style lang="scss" scoped>
.comic-element {
    width:calc((100% / 6) - 1rem);
    display:inline-block;
    padding-bottom:1rem;
    text-align:left;
        
    img {
        width: 120px;
        height: 120px;
        object-fit:cover;
        object-position:center top;
    }
    
    h4  {
        font-size:.6rem;
        margin-top:.5rem;
        text-transform:uppercase;
        vertical-align: middle;
        }
}
</style>