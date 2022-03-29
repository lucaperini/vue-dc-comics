<template>
    <div class="comic-element">
        <img :src="comicObject.thumb" :alt="comicObject.series">
        <h4>{{comicObject.series}}</h4>
    </div>
</template>

<script>
export default {
    name: "IndexMainComics",
    props: ['comicObject'],

}
</script>

<style lang="scss" scoped>
.comic-element {
    width:calc((90% / 6) - 10px);
    display:inline-block;
    
    img {
        width: 100px;
        height: 100px;
        object-fit:cover;
    }
    h4{
        font-size:.7rem;
        margin-top:.5rem;
        }
}
</style>