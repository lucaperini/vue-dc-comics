<template>
    <div class="test">
        <div class=container>
            <h2> --Content goes here!--</h2>
        </div>
        <div class="section-nav-services"></div>
    </div>
</template>

<script>
export default {
    name: 'IndexMain',
}
</script>

<style lang="scss" scoped>
.container {
    display:flex;
    align-items:center;
    justify-content:center;
    background-color:black;
    color:white;
    font-size:.8rem;
    font-weight:700;
    height:100px;
    width:100vw;
    position:relative;
    

    h5{
        font-size:.8rem;
        font-weight:700;
        
        
    }
}
.section-nav-services{
    
background-color: cornflowerblue;
    height:150px;
    
}
.test {position:relative;}
</style>