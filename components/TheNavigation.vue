<template>

    <div>

       
        <b-navbar toggleable="lg" type="dark" variant="dark" class="d-flex flex-row justify-content-around align-items-center"> <!-- toggleable = responsive en md -->

<!--col1-->

            <b-navbar-brand href="#" class="w-25">IT ACADEMY</b-navbar-brand>

                <b-navbar-toggle target="nav-collapse" class=""></b-navbar-toggle> <!--Es el Sandwich button-->

                    <b-collapse id="nav-collapse" is-nav class=""> <!--Dentro del sandwich en md (id)-->

<!--col2--> 

                        <b-navbar-nav class="w-100 d-flex flex-colum justify-content-center align-items-center">

                            <b-nav-item class="mx-2" to="/" exact>Home</b-nav-item> <!--b-nav-item actua como router-link(router link es como a)-->
                            <b-nav-item class="mx-2" to="/users">Users</b-nav-item>
                            <b-nav-item class="mx-2" to="/images">Pictures</b-nav-item>

                        </b-navbar-nav>

                    </b-collapse>

<!--col3-->                    

                    <b-navbar-nav class="w-25 d-flex flex-row justify-content-center">

                        <b-nav-form>

                            <b-input-group class="d-flex flex-row justify-content-center align-items-center">

                                <Autocomplete/>

                            </b-input-group>

                        </b-nav-form>

                    </b-navbar-nav>

        </b-navbar>

    </div>

</template>

<script>
import Autocomplete from './Autocomplete.vue'
export default {
    name: 'TheNavigation',
    components: {
      Autocomplete,
    },
}
</script>

<style scoped>
</style>