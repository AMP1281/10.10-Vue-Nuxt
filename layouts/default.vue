<template>
    <div>
        <TheNavigation/>
        <div class="content">
            <nuxt/>
        </div>
    </div>
</template>

<script>
import TheNavigation from '../components/TheNavigation'
export default{
    components:{
        TheNavigation
    }
}
</script>


<style>
/* *{
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
} */

</style>