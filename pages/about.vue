<template>
    <div>
        <h1>About</h1>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Provident ducimus error perspiciatis ad ex a mollitia similique consequuntur rerum et sit voluptas illo tempore corrupti corporis cumque repellendus, explicabo doloremque!</p>
    </div>
</template>

<script>
export default {

  head(){
    return{
      title:'About',
      meta:[
        {
        hid:"description",
        name:"description",
        content:"Nuxt",
        }
      ],
      htmlAttrs:{
        lang:'en'
      }
    }
  }

}

</script>


