<template>
    <div>
        
        <h1 class="danger">Post</h1>
        <Post 
        v-for="post of posts"
        :key="post.id"
        :name="post.name" 
        :id="post.id"
        />
    </div>
</template>

<script>
import axios from 'axios'
import Post from '../../components/Post'

export default{
    components:{
        Post
    },
    data(){
        return{
            posts:[]
        }
    },
    async created(){
        
            const res = await axios.get('http://jsonplaceholder.typicode.com/users')
            this.posts = res.data;
        } 
    
}
</script>
