<template>
    <div class="comic-element">
        <div>
            <img :src="comicObject.thumb" :alt="comicObject.series">
        </div>
        
        <div class="comic-title">
            <h4>{{comicObject.series}}</h4>
        </div>
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
    align-items:center;
        
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
    
    .comic-title {
        display:flex;
        align-self: flex-end;
    }
}
</style>