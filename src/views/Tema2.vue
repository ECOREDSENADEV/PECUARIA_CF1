<template lang="pug">
.curso-main-container.pb-3
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Aspectos normativos 

    .bloque-texto-g.m-5.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/2-aspectos-normativos.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los aspectos normativos relacionados con la producción pecuaria son aquellos que regulan la forma en la que se deben desarrollar 
          span.color-texto-uno las actividades productivas desde el punto de vista legal para controlar el funcionamiento de la unidad pecuaria.
        br

    ol.lista-ol--cuadro
      li.fw-bold
        .lista-ol--cuadro__vineta
          span.fw-bold 
        | Salud y seguridad en el trabajo
    .row
      .col-md-7    
        p Uno de los aspectos que ha cobrado mayor relevancia en los últimos años es el de la salud y la seguridad en el trabajo, pues, en este sentido, desde el Estado se han dado las directrices para la implementación de actividades enfocadas en la planificación, la gestión, la identificación y la prevención de los riesgos que puedan afectar la salud y la seguridad de los trabajadores en sus espacios de trabajo.

        p Así, el Sistema de Gestión de Seguridad y Salud en el Trabajo (SGSST) es de obligatorio cumplimiento para cualquier empleador, sea público o privado.
      .col-md-5
        picture
          img(src='@/assets/curso/tema2/2-salud-seguridad.png', alt='Salud y seguridad en el trabajo', class="img-fluid")

    #salud-seguridad.titulo-segundo.color-acento-contenido
      h2 2.1 Salud y seguridad en el trabajo

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-11.mb-4
        p Principales aspectos que se deben tener en cuenta respecto a la gestión integral de la salud y la seguridad en el trabajo. Parte del trabajo relacionado con la salud y la seguridad en el trabajo se relaciona con la identificación de los riesgos que conlleva cada una de las actividades realizadas. Es así como se definen diferentes tipos de riesgos, dependiendo de sus causas.

    Separador

    #manejo-ambiental.titulo-segundo.color-acento-contenido
      h2 2.2 Manejo ambiental

    .row
      .col-md-7    
        p 
          span.color-texto-uno Uno de los principios de la nueva forma de desarrollar explotaciones pecuarias es la protección de los recursos naturales y la sostenibilidad ambiental, por lo que este es un tema transversal a todas las actividades que tienen lugar en la unidad productiva.
          | Dentro del manejo ambiental existen elementos fundamentales sobre los cuales se desarrolla todo el ejercicio, por lo que dentro de la planificación de las actividades es importante definir cómo se abordarán y qué recursos serán necesarios para poderlos implementar. Afortunadamente, respecto al tema ambiental existe una normativa aplicable que ordena estas actividades y las integra al sistema productivo.
      .col-md-5
        picture
          img(src='@/assets/curso/tema2/2_2-manejo-ambiental.png', alt='Manejo ambiental', class="img-fluid")

      .row.mt-5.justify-content-center: .col-md-10
        .titulo-sexto.color-acento-botones.py-0
          h5 Tabla 1
          p Marco normativo aspectos ambientales
        .tabla-a.mt-1.color-acento-contenido 
          table
            thead
              tr
                th NORMA
                th ALCANCE
            tbody
              tr
                td Resoluci&oacute;n 1476 septiembre 10 de 1976 ICA
                td Reglamenta la Resoluci&oacute;n 261 de 1975, sobre el control de la salmonelosis en las aves de corral.
              tr
                td  Resoluci&oacute;n 1056 del 17 de abril de 1996 ICA
                td Control t&eacute;cnico de los insumos pecuario y se derogan las Resoluciones 710 de 1981, 2218 de 1980 y 444 de 1993.
              tr
                td Resoluci&oacute;n 1698 del 27 de junio de 2000 ICA   
                td Disposiciones sobre productores de alimentos para animales con destino al autoconsumo.
              tr
                td Resoluci&oacute;n 150 del 21 de enero de 2003 ICA
                td Adopta el reglamento t&eacute;cnico de fertilizantes y acondicionadores de suelos para Colombia.
              tr
                td Resoluci&oacute;n 968 del 10 de marzo de 2010 ICA
                td Modifica la Resoluci&oacute;n 150 de 2003.
              tr
                td Ley 1255 del 28 de noviembre de 2008 ICA
                td Creaci&oacute;n de un programa que preserve el estado sanitariode pa&iacute;s libre de influenza aviar, as&iacute; como el control y erradicaci&oacute;n de laenfermedad Newcastle en el territorio nacional.
              tr
                td Resoluci&oacute;n 587 del 27 de diciembre de 1973 ICA
                td Medidas para el control de la enfermedad de Mark en lasaves de corral.
              tr
                td Resoluci&oacute;n 1937 del 22 de julio de 2003 ICA
                td Medidas sanitarias para la prevenci&oacute;n y control de laenfermedad Newcastle en el territorio nacional.
              tr
                td Resoluci&oacute;n 375 del 27 de febrero de 2004 ICA
                td Disposiciones sobre Registro y Control de los Bioinsumos yExtractos Vegetales de uso agr&iacute;cola en Colombia.
              tr
                td Resoluci&oacute;n 2896 del 10 de octubre de 2005 ICA
                td Disposiciones sanitarias para la construcci&oacute;n de nuevasgranjas av&iacute;colas en el territorio nacional.
              tr
                td Resoluci&oacute;n 3654 del 28 de septiembre de 2009 ICA
                td Adopci&oacute;n del programa para el control y erradicaci&oacute;n de laenfermedad Newcastle en el territorio nacional.
              tr
                td Resoluci&oacute;n 1183 del 25 de marzo de 2010 ICA
                td Condiciones de Bioseguridad que se deben cumplir las granjasav&iacute;colas comerciales en el pa&iacute;s para su certificaci&oacute;n.
              tr
                td Resoluci&oacute;n 4287 del 21 de noviembre de 2007 del Ministeriode la Protecci&oacute;n Social
                td Reglamento t&eacute;cnico sobre los requisitos sanitarios y deinocuidad de la carne y productos c&aacute;rnicos comestibles de las aves de corral.
              tr
                td Decreto 1500 del 4 de mayo de 2007 del Ministerio de laProtecci&oacute;n Social
                td Creaci&oacute;n del Sistema Oficial de Inspecci&oacute;n, Vigilancia yControl de la Carne, Productos C&aacute;rnicos Comestibles y Derivados C&aacute;rnicosDestinados para el Consumo Humano - requisitos sanitarios y de inocuidad enla producci&oacute;n primaria.
              tr
                td Resoluci&oacute;n 2101 del 27 de julio de 2007 ICA
                td Programas de seguridad alimentaria con fines comercialesde autoconsumo o cualquier programa enfocado hacia la distribuci&oacute;n de aves.
              tr
                td Resoluci&oacute;n 2833 del 29 de octubre de 2007 ICA
                td Modifica la Resoluci&oacute;n 2101 de 2007.
              tr
                td Decreto 3100 del 30 de octubre de 2003 del Ministerio delMedio Ambiente Vivienda y Desarrollo Territorial
                td Reglamenta la tasa retributiva por la utilizaci&oacute;n directadel agua como receptor de los vertimientos puntuales y se toman otrasdeterminaciones.
              tr
                td Decreto 1713 del 6 de agosto de 2002 del Ministerio delMedio Ambiente Vivienda y Desarrollo Territorial
                td Reglamenta la Ley 142 de 1994, la Ley 632 de 2000 y la Ley689 del 2001, en relaci&oacute;n con la prestaci&oacute;n del servicio p&uacute;blico de aseo, yel Decreto Ley 2811 de 1974, la Ley 99 de 1993 en relaci&oacute;n con la Gesti&oacute;nIntegral de Residuos S&oacute;lidos.
              tr
                td Ley 55 del 2 de julio de 1993 del Ministerio del Trabajo ySeguridad Social
                td Por medio de la cual se aprueba en &ldquo;Convenio #170 y larecomendaci&oacute;n n&uacute;mero 177 sobre la seguridad en la utilizaci&oacute;n de productosqu&iacute;micos en el trabajo&rdquo; adoptados por la 77 reuni&oacute;n de la conferencia generalde la OIT.
              tr
                td Decreto 1594 de 1984 del Ministerio de Agricultura
                td Reglamenta parcialmente el t&iacute;tulo I de la ley 9 de 1979,as&iacute; como el cap&iacute;tulo II del t&iacute;tulo VI - parte III - libro II y el t&iacute;tulo IIIde la parte III - libro I &ndash; del Decreto 2811 de 1974 en cuanto a usos delagua y residuos l&iacute;quidos.
              tr
                td Decreto 3172 de 2003 del Ministerio de Ambiente, Vivienday Desarrollo Territorial
                td Reglamenta el art&iacute;culo 158-2 del Estatuto Tributario. &rdquo;Elcontribuyente deber&aacute; acreditar el cumplimiento de los siguientes requisitoscuando la Direcci&oacute;n de Impuestos y Aduanas Nacionales, DIAN los exija porinversiones en control y mejoramiento del medio ambiente.
              tr
                td Decreto 1753 de 1994 del Ministerio del Medio Ambiente
                td Reglamenta parcialmente los t&iacute;tulos VIll y Xll de la Ley99 de 1993 sobre licencias ambientales.
              tr
                td Ley 99 de 1993 del Congreso de la Rep&uacute;blica
                td Por la cual se crea el Ministerio del Medio Ambiente, sereordena el sector p&uacute;blico encargado de la gesti&oacute;n y conservaci&oacute;n del medioambiente y los recursos naturales renovables, se organiza el Sistema NacionalAmbiental, SINA.
              tr
                td Decreto 1900 de 2006 del Ministerio de Ambiente, Vivienday Desarrollo Territorial
                td Reglamenta el par&aacute;grafo del art&iacute;culo 43 de la Ley 99 de993. Todo proyecto que involucre en su ejecuci&oacute;n el uso del agua tomadadirectamente de fuentes naturales y que est&eacute; sujeto a la obtenci&oacute;n delicencia ambiental, deber&aacute; destinar el 1% del total de la inversi&oacute;n para larecuperaci&oacute;n, conservaci&oacute;n, preservaci&oacute;n y vigilancia de la cuencahidrogr&aacute;fica que alimenta la respectiva fuente h&iacute;drica; de conformidad con elpar&aacute;grafo del art&iacute;culo 43 de la Ley 99 de 1993.
              tr
                td Resoluci&oacute;n 1023 de 2005 del Ministerio de Ambiente yDesarrollo Territorial
                td Por la cual se adoptan gu&iacute;as ambientales como instrumentode autogesti&oacute;n y autorregulaci&oacute;n.
              tr
                td Decreto 1299 de 2008 del Ministerio de Ambiente yDesarrollo Territorial
                td Por el cual se reglamenta el departamento de gesti&oacute;nambiental de las empresas a nivel industrial y se dictan otras disposiciones.      

</template>

<script>
export default {
  name: 'Tema2',
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
