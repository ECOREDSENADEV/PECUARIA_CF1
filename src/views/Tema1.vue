<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Sistemas productivos pecuarios  

    #clasificacion.titulo-segundo.color-acento-contenido
      h2 1.1 Clasificación

    .row
      .col.col-12.col-md-7.mb-4
        p En el caso de la producción pecuaria son múltiples los factores que se deben analizar antes de cualquier emprendimiento, por lo que es necesario tomarse el tiempo suficiente para identificar el tipo de explotación, determinar los recursos necesarios y disponibles, conocer el tipo de instalaciones que se requieren y, sobre todo, 
          span.text-success hacer una programación detallada de las actividades que se llevarán a cabo al interior de la unidad pecuaria, con lo cual será posible darle un orden lógico al sistema, conseguir la productividad esperada y contribuir a la sostenibilidad del proyecto productivo.
      .col.col-12.col-md-5
        img(src="@/assets/curso/tema1/clasificacion.jpg")

    #caracteristicas.titulo-segundo.color-acento-contenido
      h2 1.2	Características

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.jpg")
      .col.col-11.mb-4
        p Para conseguir unidades pecuarias organizadas conforme a los parámetros técnicos es necesario implementar procesos acordes a la normatividad aplicable, definiendo los recursos disponibles y conociendo los procesos que conlleva la implementación de sistemas en diversos entornos rurales para controlar el funcionamiento de la unidad pecuaria, a continuación, se verán sus características.


    Separador  

    //- Muestras
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
