<template lang="pug">
.curso-main-container.pb-3
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Planificación de la unidad productiva

    .row.mb-5
      .col-md-7    
        p Como en todo proyecto productivo, el proceso de planificación es una de las etapas fundamentales, pues en ella se define el área a ocupar, el número de animales a alojar, los recursos necesarios, la cantidad de alimento requerido, los materiales a emplear y la cantidad de personal necesaria para adelantar las distintas labores. El éxito o el fracaso del proyecto pecuario, depende en buena medida del análisis detallado de cada uno de los siguientes aspectos. 
      .col-md-5
        picture
          img(src='@/assets/curso/tema3/3_img.png', alt='Planificación de la unidad productiva', class="img-fluid")

    .tarjeta.p-4.mb-5
      SlyderA.bg01
        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p.p-2 En cualquier explotación pecuaria, sin importar la especie, es necesario contar con instalaciones que atiendan las necesidades básicas de los animales; refugio, agua y alimento.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_instalaciones1.png', alt='Instalaciones pecuarias').mr-1
              figcaption Instalaciones pecuarias

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p.p-2 El tipo de instalaciones a emplear, así como el área a construir, dependen principalmente del número de animales a alojar, de las condiciones agroecológicas de la zona, de la disponibilidad de recursos y del tipo de explotación que se desee implementar.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_instalaciones2.png', alt='Instalaciones pecuarias').mr-1
              figcaption Instalaciones pecuarias

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p.p-2 Principales instalaciones pecuarias:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                | Cerramiento.
              li 
                i.fas.fa-check
                | Manejo.
              li 
                i.fas.fa-check
                | Alimentación.
              li 
                i.fas.fa-check
                | Alojamiento.
              li 
                i.fas.fa-check
                | Cuidados especiales.
              li 
                i.fas.fa-check
                | Almacenamiento.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_instalaciones3.png', alt='Instalaciones pecuarias').mr-1
              figcaption Instalaciones pecuarias

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.p-2 Cerramiento
            p.p-2 Tienen el propósito de contener los animales en un área determinada: cercas, espalderas, cercas vivas, enmallados y muros. 
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_cerramiento.png', alt='Cerramiento').mr-1
              figcaption Cerramiento

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.p-2 Manejo
            p.p-2 Se construyen para facilitar las labores de manejo de los animales: corrales, embarcaderos, apretaderos, parideras, casetas de ordeño y apriscos.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_manejo.png', alt='Manejo').mr-1
              figcaption Manejo

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.p-2 Alimentación
            p.p-2 Facilitan la dispensación del agua, el alimento y los suplementos a los animales: comederos y bebederos.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_alimentacion.png', alt='Alimentación').mr-1
              figcaption Alimentación

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.p-2 Alojamiento
            p.p-2 Permiten contener a los animales durante su ciclo productivo y resguardarlos de los depredadores. Especialmente se utilizan para especies menores: jaulas, galpones, porquerizas y camas.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_alojamiento.png', alt='Alojamiento').mr-1
              figcaption Alojamiento

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.p-2 Cuidados especiales
            p.p-2 Son instalaciones que facilitan el cuidado de los animales en situaciones especiales, enfermos o durante la cría: pesebreras y establos.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_cuidados_especiales.png', alt='Cuidados especiales').mr-1
              figcaption Cuidados especiales

        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.p-2 Almacenamiento
            p.p-2 Almacenamiento de materias primas, insumos, medicamentos, alimentos y productos: bodegas, almacenes y graneros.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema3/3_slyder_almacenamiento.png', alt='Almacenamiento').mr-1
              figcaption Almacenamiento

    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Instalaciones pecuarias 

    .bloque-texto-g.m-5.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/3_1-img.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El diseño de las instalaciones pecuarias depende de diversos factores, pero básicamente está en función de la especie animal, los factores agroecológicos de la zona y la disponibilidad de materiales.
          br
    br

    #t_3_1_1.titulo-segundo.color-acento-contenido.mt-4
      h2 3.1.1 Diseños y características 

    p El diseño de las instalaciones pecuarias depende de diversos factores, pero básicamente está en función de la especie animal, los factores agroecológicos de la zona y la disponibilidad de materiales. Igualmente, antes de establecer cualquier instalación es importante considerar, entre otros, los siguientes factores:

    .row
      .col-md-7
        ul.lista-ul--color
          li 
            i.fas.fa-check
            | Ubicación en zonas alejadas de centros urbanos o vías principales afectadas por el ruido.
          li 
            i.fas.fa-check
            | En zonas cálidas se recomienda orientar las instalaciones en sentido oriente occidente con el fin de conseguir la mayor cantidad de sombra posible.
          li 
            i.fas.fa-check
            | Áreas de fácil acceso para revisar el estado de los animales.
          li 
            i.fas.fa-check
            | En lo posible garantizar el acceso a servicios básicos como agua y electricidad.
          li 
            i.fas.fa-check
            | Lugares donde se facilite el ingreso del alimento.
          li 
            i.fas.fa-check
            | Sitios que garanticen la seguridad de los animales y del personal operativo.
          li 
            i.fas.fa-check
            | Definir si es una explotación intensiva, semiintensiva o extensiva. 
      .col-md-5
        img(src='@/assets/curso/tema3/3_1_1-img.png', alt='Diseños y características')

    p.mt-5 Dentro de los principales diseños de instalaciones pecuarias se tienen los siguientes:        

    .tarjeta.bg-tema3.p-4.mb-5
      //- LineaTiempoC debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- text-small se usa para que los títulos sean mas pequeños
      LineaTiempoC.color-acento-contenido(text-small)
        .row(titulo="Corrales").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Corrales
            p Permiten el alojamiento de los animales durante el desarrollo de tareas cotidianas como vacunación, palpación, desparasitación y marcado. Cuentan con una zona denominada apretadero, la cual facilita estas labores. Tienen una zona techada con comederos y bebederos por lo que funcionan como caseta de ordeño.
            img(src='@/assets/curso/tema3/3_linea_corrales1.png', alt='Corrales')
          .col-md-5
            p.mt-4.pt-1 Este diseño de corral es adecuado únicamente para el manejo animal, pues solo está dotado de apretadero y embarcadero. Carece de cubierta, por lo que evidentemente está diseñado para que los animales no permanezcan allí durante mucho tiempo
            img.mt-5(src='@/assets/curso/tema3/3_linea_corrales2.png', alt='Corrales')

        .row(titulo="Establos").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Establos
            p El establo debe proporcionar protección al animal frente a la intemperie y se constituye en un espacio de refugio en donde además se puede alimentar y beber. Deben tener pisos blandos, generalmente de tierra para permitir el drenaje de la orina.
          .col-md-5
            img(src='@/assets/curso/tema3/3_linea_establos.png', alt='Establos')

        .row(titulo="Pesebreras").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Pesebreras 
            p Estas permiten un alojamiento adecuado a los animales en momentos de especial cuidado. Además de la cubierta cuentan con un encerramiento que los protege de los elementos. En su interior se cuenta con implementos para el cuidado de los animales, agua y alimento.
          .col-md-5
            img(src='@/assets/curso/tema3/3_linea_pesebreras.png', alt='Pesebreras')

        .row(titulo="Porquerizas").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Porquerizas
            p El uso de determinados diseños de porquerizas depende del tipo de explotación, principalmente. En el caso de pequeñas explotaciones se pueden emplear modelos en los cuales se tiene un área para el cerdo reproductor, jaulas de maternidad y una zona de levante o engorde, tal como se presenta en la imagen.
            img(src='@/assets/curso/tema3/3_linea_porquerizas1.png', alt='Porquerizas')
          .col-md-5
            p.mt-4.pt-1 En explotaciones intensivas, especialmente las que se dedican a la producción de carne, las instalaciones maximizan el uso de las áreas, por lo que los animales disponen de menos espacio para movilizarse.
            img.mt-5(src='@/assets/curso/tema3/3_linea_porquerizas2.png', alt='Porquerizas')

</template>

<script>
export default {
  name: 'Tema3',
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
