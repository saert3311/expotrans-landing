<template>
  <div>
    <IndexHeader />
    <section class="text-gray-600 body-font">
      <div
        class="
          container
          mx-auto
          flex
          px-5
          pt-24
          pb-10
          items-center
          justify-center
          flex-col
        "
      >
        <img
          class="
            lg:w-2/6
            md:w-3/6
            w-5/6
            mb-10
            object-cover object-center
            rounded
          "
          alt="hero"
          src="/expotrans_logo_placeholder.jpg"
        />
        <div class="text-center lg:w-2/3 w-full">
          <h1
            class="
              title-font
              sm:text-4xl
              text-3xl
              mb-4
              font-medium
              text-gray-900
            "
          >
            24 al 27 de Noviembre del 2022
          </h1>
          <h3 class="text-xl sm:text-2xl font-medium text-gray-900">Parque Simón Bolívar, La Carlota, Estado Miranda</h3>
          <p class="mb-8 leading-relaxed pt-4">
            Un gran evento de encuentro para todo el transporte acuático (Marítimo, Fluvial, y Submarino), Aéreo, Aeroespacial y Terrestre.
          </p>
        </div>
      </div>
    </section>
    <page-footer />
  </div>
</template>

<script>
import IndexHeader from '@/components/Header.vue'
import PageFooter from '@/components/Footer.vue'
export default {
  name: 'IndexPage',
  components: {
    IndexHeader,
    PageFooter
  }
}
</script>
