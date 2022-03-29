<template>
    <div class="relative">
        <div class="jumbotron">
        <h3>current series</h3>
        </div>
        <div class="container">
            <h2> --Content goes here!--</h2>
        </div>
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
    
    

    h5{
        font-size:.8rem;
        font-weight:700;
        
        
    }
}

.jumbotron{
    width:100%;
    height:400px;
    background-image: url('../assets/images/jumbotron.jpg');
    background-size: cover;

    h3{
        text-transform:uppercase;
        color:white;
        font-size: 1rem;
        font-weight:700;
        padding:.8rem;
        background-color: cornflowerblue;
        position:absolute;
        top:75%;
        left:20%;
    }
    
}

</style>