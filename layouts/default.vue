<template>
    <div>
        <Navigation/>
        <div class="content">
            <nuxt/>
        </div>
    </div>
</template>

<script>
import Navigation from '../components/Navigation'
export default{
    components:{
        Navigation
    }
}
</script>


<style>
*{
    box-sizing: border-box;
    color: whitesmoke;
    text-decoration: none;
}

body{
    background:#2d3436;
    color:whitesmoke;
    font-family: Arial, Helvetica, sans-serif;
}

.content{
    padding: 2rem
}

</style>