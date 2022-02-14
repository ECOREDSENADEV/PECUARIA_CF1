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

    .row.mt-4.justify-content-center.bg-tema2
      .col-md-5
        img(src="@/assets/curso/tema2/2-salud-seguridad.svg")
      .col-md-5
        SlyderF.mb-5(columnas="col-lg-12").bg-slyder-tema2
          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon2.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Código Sustantivo del Trabajo (1951) 
                  p Busca relaciones equitativas entre los trabajadores y los empleadores. Algunos de sus artículos fueron derogados por el Decreto 1295 de 1994 y la Ley 962 de 2005.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Decreto 1072 de 2015 
                  p Recopila diferentes normas de la reglamentación laboral. Define las condiciones para el establecimiento del SGSST.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Decreto Ley 1295 de 1994 
                  p Define la organización y administración del SGSST.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 1401 2007
                  p Hace énfasis en las causas y medidas correctivas para evitar la ocurrencia de accidentes laborales.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Ley 1010 de 2006
                  p Se enfoca en la prevención, corrección y sanción del acoso laboral en todas sus formas.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 2346 de 2007
                  p Establece directivas para el manejo de las evaluaciones médicas ocupacionales y del contenido de historias clínicas ocupacionales.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 0652 de 2012
                  p Define cómo se conforma y funciona el comité de convivencia laboral en entidades públicas y privadas. Modificada parcialmente la Resolución 1356 de 2012.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 2013 de 1986
                  p Reglamenta la organización y funcionamiento de los Comités Paritarios de Seguridad y Salud en el Trabajo en los lugares de trabajo, estableciendo las funciones de este Comité y de cada uno de sus miembros, así como el quorum para sesionar.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 4502 de 2012
                  p Reglamenta procedimientos y requisitos para las licencias de salud ocupacional.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 2646 de 2008
                  p Se orienta hacia las responsabilidades de los diferentes actores sociales en la gestión del riesgo psicosocial en el trabajo.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 1409 de 2012
                  p Regula la protección contra caídas en trabajo en alturas. Es modificada por la Resolución 3368 de 2014.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 1792 de 1990
                  p Establece límites permisibles para la exposición ocupacional al ruido.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 1956 de 2008
                  p Medidas relacionadas con el consumo de cigarrillo y tabaco. También la Circular 0038 de 2010 habla sobre espacios libres de humo y sustancias psicoactivas en la empresa.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Decreto 1474 de 2014
                  p Expide la tabla de enfermedades laborales; así como los agentes de riesgo y grupos de enfermedades.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario Resolución 2400 de 1979
                  p Presenta directivas sobre higiene y seguridad en el trabajo. Define las características que deben cumplir los establecimientos y las normas generales sobre riesgos físicos, químicos y biológicos.

          .tarjeta.white.p-4
            .row.justify-content-center
              .col-10.p-0.text-center
                img.img-slyder-tema2(src='@/assets/curso/tema2/2-slide-icon1.svg' alt='AvatarTop')
                .text-slyder-tema2
                  h4.texto-color-primario La Resolución 0312 de 2019
                  p Especifica los estándares mínimos para empresas, empleadores y contratantes en cuanto a la implementación del SGSST.

    br

    #salud-seguridad.titulo-segundo.color-acento-contenido.mt-5
      h2 2.1 Salud y seguridad en el trabajo

    ImagenInfograficaB.color-acento-botones.mb-5
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/tema2/2_1-infografica.jpg', alt='Salud y seguridad en el trabajo')
        .tarjeta.p-3(x="81%" y="6%" tooltip="Ver más")
          .row.bg-white.p-4.rounded
            .col-md-8
              h4.text-dark Elementos de protección
              p Están definidos por el tipo de actividad a realizar, el tipo de insumos a emplear, el modo de aplicación de los medicamentos y los riesgos asociados con dicha actividad.
              br
              p Deben ofrecer protección al trabajador para desarrollar su actividad.
              .row
                .col-6.p-0
                  ul.lista-ul--color
                    li 
                      i.fas.fa-check
                      | Protección para la cabeza.
                    li 
                      i.fas.fa-check
                      | Protección auditiva.
                    li 
                      i.fas.fa-check
                      | Protección visual.
                    li 
                      i.fas.fa-check
                      | Protección respiratoria.
                .col-6.p-0
                  ul.lista-ul--color
                    li 
                      i.fas.fa-check
                      | Protección para manos.
                    li 
                      i.fas.fa-check
                      | Ropa de protección.
                    li 
                      i.fas.fa-check
                      | Protección para pies.
                    li 
                      i.fas.fa-check
                      | Accesorios: fajas, arneses, mandiles.
            .col-md-4
              figure
                img(src='@/assets/curso/tema2/2_1-elementos-proteccion.jpg', alt='Elementos de protección', class="img-fluid rounded-start")

        .tarjeta.p-3(x="89%" y="45%" tooltip="Ver más")
         .row.bg-white.p-4.rounded
            .col-md-7
              h4.text-dark Dotación a los trabajadores de la granja pecuaria
              p Es obligación de empleado y empleador facilitar y emplear los elementos de protección personal y hacer la respectiva capacitación sobre los riesgos relacionados con su actividad, así como el correcto uso del equipo de protección personal EPP. 
              p Son muchos los accidentes que se pueden evitar mediante el correcto uso de los equipos de protección personal.
            .col-md-5
              figure
                img(src='@/assets/curso/tema2/2_1-dotacion.jpg', alt='Dotación de trabajadores', class="img-fluid rounded-start")

        .tarjeta.p-3(x="80%" y="85%" tooltip="Ver más")
          .row.bg-white.p-4.rounded
            .col-md-7
              h4.text-dark Riesgos laborales
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  span.fw-bold Higiénicos y biológicos: 
                  | patógenos, enfermedades transmisibles.
                li 
                  i.fas.fa-check
                  span.fw-bold Químicos: 
                  | quemaduras, irritación, intoxicación, dermatitis.
                li 
                  i.fas.fa-check
                  p.mb-0
                    span.fw-bold Mecánicos: 
                    | fracturas, cortes, aplastamientos. Causados por manipulación de equipos, herramientas o por ataque de animales.
                li 
                  i.fas.fa-check
                  span.fw-bold Térmicos: 
                  | exposición a altas o bajas temperaturas 
                li 
                  i.fas.fa-check
                  span.fw-bold Eléctricos: 
                  | contacto con cercas eléctricas - equipos eléctricos.
                  
                li 
                  i.fas.fa-check
                  p.mb-0
                    span.fw-bold Por acciones repetitivas: 
                    | ordeño - recolección de huevos - vacunación de animales.
            .col-md-5
              figure
                img(src='@/assets/curso/tema2/2_1-riesgos-laborales.jpg', alt='Riesgos laborales', class="img-fluid rounded-start")



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
          table.mb-4
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
    br

    ol.lista-ol--cuadro
      li.fw-bold
        .lista-ol--cuadro__vineta
          span.fw-bold 
        | Normatividad local

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-11.mb-4
        p Además del marco normativo expuesto anteriormente, para el desarrollo de las explotaciones pecuarias se deben tener en cuenta los aspectos relacionados con la normatividad local, puesto que el desarrollo de cualquier actividad productiva debe estar acorde con lo establecido por las autoridades de planeación. Entre los aspectos que se deben tener en cuenta en este sentido se encuentran los siguientes:

    .row.mb-5
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-sistema-texto(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h4.text-dark Plan de ordenamiento territorial
              p.text-dark.m-0.fs-6 Este tipo de explotaciones, dependiendo de la especie animal, se puede hacer un manejo enfocado en los individuos (como en el caso de los bovinos o los equinos) o en las poblaciones (como ocurre con las aves, conejos o cuyes). 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/2_2-normatividad-local-img1.png')})`, 'background-repeat': 'no-repeat', 'background-size': 'auto'}")
  
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-sistema-texto(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h4.text-dark Usos del suelo
              p.text-dark.m-0.fs-6 Dependiendo de las condiciones ambientales o de la disponibilidad de alimento, algunas de las explotaciones pecuarias pueden trasladarse de un lugar a otro. Esto se da sobre todo en la producción ganadera, donde es común la migración de animales según las épocas de abundancia o escasez de pasturas.     
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/2_2-normatividad-local-img2.png')})`, 'background-repeat': 'no-repeat', 'background-size': 'auto'}")
  
      .col-sm-6.col-xl-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-sistema-texto(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h4.text-dark Zonas de alto riesgo
              p.text-dark.m-0.fs-6 Siempre que se desarrolla un sistema productivo pecuario es necesario asegurar unas instalaciones mínimas para el alojamiento de los animales y una infraestructura complementaria que facilite las labores que demande su manejo.
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/2_2-normatividad-local-img3.png')})`, 'background-repeat': 'no-repeat', 'background-size': 'auto'}")
  




    //- .row.mb-5
    //-   .col.mb-4
    //-     .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
    //-       .indicador--hover(v-if="indicadorTarjetaSlide")
    //-       .tarjeta-slide__contenedor
    //-         .tarjeta-slide__contenido.p-4.p-xl-5
    //-           h1.text-dark Plan de ordenamiento territorial
    //-           p.text-dark Este tipo de explotaciones, dependiendo de la especie animal, se puede hacer un manejo enfocado en los individuos (como en el caso de los bovinos o los equinos) o en las poblaciones (como ocurre con las aves, conejos o cuyes). 
    //-         .img-fluid.tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/2_2-normatividad-local-img1.jpg')})`,'background-repeat': 'no-repeat', 'background-size': 'auto'}")
      
    //-   .col.mb-4
    //-     .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
    //-       .indicador--hover(v-if="indicadorTarjetaSlide")
    //-       .tarjeta-slide__contenedor
    //-         .tarjeta-slide__contenido.p-4.p-xl-5
    //-           h1.text-dark Generación de subproductos
    //-           p.text-dark En la actividad pecuaria es común la obtención de subproductos los cuales son empleados tanto al interior de la unidad productiva como fuera de ella. 
    //-         .img-fluid.tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-generacion.png')})`}")
      
    //-   .col-sm-6.col-xl-4.mb-4
    //-     .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
    //-       .indicador--hover(v-if="indicadorTarjetaSlide")
    //-       .tarjeta-slide__contenedor
    //-         .tarjeta-slide__contenido.p-4.p-xl-5
    //-           h1.text-dark Individuos y poblaciones
    //-           p.text-dark Este tipo de explotaciones, dependiendo de la especie animal, se puede hacer un manejo enfocado en los individuos (en el caso de los bovinos o los equinos) o en las poblaciones (como ocurre con las aves, conejos o cuyes). 
    //-         .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-individuos.png')})`}")

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
