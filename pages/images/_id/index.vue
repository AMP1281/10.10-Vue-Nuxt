<template>

    <div>

        <b-container class="animate__animated animate__fadeIn">

            <div class="d-flex flex-column justify-content-start align-items-center">

                <ButtonAnterior/>

                <PictureDetalles/>

            </div>

        </b-container>

    </div>

</template>

<script>
import PictureDetalles from '@/components/PictureDetalles.vue'
import ButtonAnterior from '@/components/ButtonAnterior.vue'
export default{
   components: {
      ButtonAnterior,
      PictureDetalles
  },
}
</script>