<template>

<div>

        <nuxt-link to= "/Users" >

            <b-form-input type="text" v-model="userInput" list="resultAutocomplete" placeholder="Username search.."></b-form-input>

            <datalist id="resultAutocomplete">

                <option v-for="name in resultAutocomplete" :key="name">{{ name.name }}</option>

            </datalist>

        </nuxt-link>
 
</div>

</template>

<script>
import {mapGetters} from 'vuex'
export default{
    computed:{
         ...mapGetters(['resultAutocomplete']),
         userInput:{
              get(){
                  return this.$store.state.inputBuscador
              },
              set(userInput){
                  return this.$store.commit('SET_BUSCADOR', userInput)
              }
        },
    },
}
</script>