<template>

    <div>

      <b-container class="animate__animated animate__fadeIn">

        <h1 class="mt-4 d-flex justify-content-center">

          Home

        </h1>

          <HomeComponente/>

      </b-container>

    </div>

</template>

<script>
import HomeComponente from '@/components/HomeComponente.vue'

export default {

  components: {
      HomeComponente
  },

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



