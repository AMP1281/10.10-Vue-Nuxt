<template>
    <div>
        <h1>Product Details</h1>
        <p>Id:{{post.email}}</p>
    </div>
</template>

<script>

//import axios from 'axios'
export default{

    data(){
        return{
            post:{}
        }
    },

    //async created(){

    //    const res = await axios.get('http://jsonplaceholder.typicode.com/users' + this.$route.params.id)
    //    this.post = res.data;
    //}
}
</script>

<style scoped>

.card{
    border: 1px solid whitesmoke;
    padding: 4rem;
}

</style>
