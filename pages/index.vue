<template>
  <h1>Welcome nuxt</h1>
</template>

<script>
export default {

  //Este objeto ayuda al SEO,añadimos meta información
  head(){
    return{
      title:'Exercici Final amb Nuxt | Home',
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
