<template lang="pug">
.curso-main-container.pb-3
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Sistemas productivos pecuarios  

    #clasificacion.titulo-segundo.color-acento-contenido
      h2 1.1 Clasificación

    .row
      .col.col-12.col-md-7.mb-4
        p En el caso de la producción pecuaria son múltiples los factores que se deben analizar antes de cualquier emprendimiento, por lo que es necesario tomarse el tiempo suficiente para identificar el tipo de explotación, determinar los recursos necesarios y disponibles, conocer el tipo de instalaciones que se requieren y, sobre todo, 
          span.color-texto-uno hacer una programación detallada de las actividades que se llevarán a cabo al interior de la unidad pecuaria, con lo cual será posible darle un orden lógico al sistema, conseguir la productividad esperada y contribuir a la sostenibilidad del proyecto productivo.
      .col.col-12.col-md-5
        img(src="@/assets/curso/tema1/clasificacion.jpg")

    #caracteristicas.titulo-segundo.color-acento-contenido
      h2 1.2	Características

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-11.mb-4
        p Para conseguir unidades pecuarias organizadas conforme a los parámetros técnicos es necesario implementar procesos acordes a la normatividad aplicable, definiendo los recursos disponibles y conociendo los procesos que conlleva la implementación de sistemas en diversos entornos rurales para controlar el funcionamiento de la unidad pecuaria, a continuación, se verán sus características.

    .row.mb-5.justify-content-center
      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1.text-dark Versatilidad
              p.text-dark Es una actividad que se adapta fácilmente a una variedad de condiciones que pueden ser de tipo agroecológico, económico, sociocultural, y tecnológico, entre otras. 
            .img-fluid.tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-versatilidad.png')})`}")
      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1.text-dark Generación de subproductos
              p.text-dark En la actividad pecuaria es común la obtención de subproductos los cuales son empleados tanto al interior de la unidad productiva como fuera de ella. 
            .img-fluid.tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-generacion.png')})`}")
      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1.text-dark Individuos y poblaciones
              p.text-dark Este tipo de explotaciones, dependiendo de la especie animal, se puede hacer un manejo enfocado en los individuos (en el caso de los bovinos o los equinos) o en las poblaciones (como ocurre con las aves, conejos o cuyes). 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-individuos.png')})`}")
    .row.mb-5.justify-content-center
      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1.text-dark Movilidad
              p.text-dark Dependiendo de las condiciones ambientales o de la disponibilidad de alimento, algunas de las explotaciones pecuarias pueden trasladarse de un lugar a otro. Esto se da sobre todo en la producción ganadera, donde es común la migración de animales según las épocas de abundancia o escasez de pasturas.
            .img-fluid.tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-movilidad.png')})`}")
      .col-sm-6.col-xl-4.mb-4
        .tarjeta.tarjeta-slide.arriba.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1.text-dark Alojamiento e infraestructura asociada
              p.text-dark Siempre que se desarrolla un sistema productivo pecuario es necesario asegurar unas instalaciones mínimas para el alojamiento de los animales y una infraestructura complementaria que facilite las labores que demande su manejo.    
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/1_2-alojamiento.png')})`}")
    
    Separador  
    
    #componentes.titulo-segundo.color-acento-contenido
      h2 1.3 Componentes 

    .bloque-texto-g.m-5.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/componentes.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los sistemas productivos pecuarios están integrados por diversos componentes que se deben articular de manera precisa para conseguir los resultados esperados en materia de rendimientos y calidad del producto final. En términos generales, los elementos que componen cualquier sistema productivo pecuario son la especie animal, el alimento, las instalaciones, los equipos y herramientas, las condiciones agroecológicas y el manejo. 
          br

    .tarjeta.p-4.mb-5
      SlyderA.bg01
        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p.pl-1 Entre las especies animales más empleadas en sistemas pecuarios están los ovinos, caprinos, equinos, porcinos, aves y mamíferos pequeños como conejos y cuyes. También se encuentran insectos, reptiles y anélidos, como la lombriz de tierra. 
       
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema1/1_3-animal.png', alt='Especie animal').mr-1
              figcaption Especie animal
        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p.pl-1 Es la fuente de energía que sostiene a los animales que hacen parte del sistema productivo. Puede ser natural, como en el caso de las praderas, o suplementada como se hace en sistemas intensivos avícolas, por ejemplo.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema1/1_3-alimento.png', alt='Alimento')
              figcaption Alimento
        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4.titulo-cuarto Alcance de la medición.
            p Son las construcciones o adecuaciones de infraestructura para el alojamiento de los animales o para facilitar las labores de manejo como ordeño, alimentación.
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema1/1_3-instalaciones.png', alt='Instalaciones')
              figcaption Instalaciones
        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p Son elementos que facilitan el manejo de la explotación pecuaria y que se utilizan para diversas labores. Tipos de equipos: ordeño mecánico, nebulización de medicamentos o ensilaje. Herramientas: fumigadora, tijera, pala, martillo.    
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema1/1_3-equipos.png', alt='Equipos y herramientas')
              figcaption Equipos y herramientas
        .row.justify-content-center
          .col-md-5.mb-4.mb-md-0
            p Corresponde al factor humano y consiste en la forma como se organizan, administran y disponen los componentes del sistema productivo. Igualmente, se relaciona con el desarrollo de las labores necesarias para su sostenimiento. 
          .col-md-6
            figure.p-4
              img(src='@/assets/curso/tema1/1_3-manejo.png', alt='Manejo')
              figcaption Manejo

    Separador  

    #explotaciones.titulo-segundo.color-acento-contenido
      h2 1.4 Principales explotaciones pecuarias

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-11.mb-4
        p Las explotaciones pecuarias son tan diversas como lo son las especies animales, pues son múltiples las iniciativas de crianza y beneficio que se han desarrollado en diferentes latitudes. Incluso algunas de ellas pueden resultar exóticas dependiendo del contexto en el que se desarrollen. No obstante, de acuerdo con su importancia económica y el volumen de la producción, en el ámbito nacional las principales explotaciones pecuarias podrían agruparse en las siguientes categorías:

    ImagenInfograficaB.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/explotaciones-pecuarias.png', alt='Principales Explotaciones Pecuarias')
      .tarjeta.p-3(x="2.4%" y="6%" tooltip="Ganado bovino")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4.text-dark Ganado bovino
            p.text-dark Es tal vez una de las explotaciones pecuarias más difundida en el mundo y se dedica principalmente a la producción de carne y leche. Se efectúa en sistemas intensivos, semiintensivos y extensivos en múltiples condiciones agroecológicas. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-ganado-bovino.png', alt='Ganado Bovino', class="img-fluid rounded-start")
      .tarjeta.p-3(x="2.4%" y="23%" tooltip="Porcinos")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Porcinos
            p La producción porcícola se desarrolla en múltiples climas y altitudes, en sistemas que pueden ser extensivos e intensivos.
            p Estas explotaciones se orientan principalmente a la producción de carne, con destino al consumo directo y a la industria. Igualmente, es común la producción de lechones.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-porcinos.png', alt='Porcinos', class="img-fluid rounded-start")
      .tarjeta.p-3(x="2.4%" y="39%" tooltip="Avícola")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Avícola
            p Esta es una de las industrias más grandes que existen en el mundo, pues es una de las proteínas de origen animal más consumidas. En la industria avícola destacan la producción de huevo, pollo de engorde y pollo de levante.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-avicola.png', alt='Avícola', class="img-fluid rounded-start")
      .tarjeta.p-3(x="2.4%" y="55%" tooltip="Búfalos")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Búfalos
            p La producción de carne y leche de búfalo se desarrolla, principalmente, en zonas de trópico bajo, donde se dan condiciones de alta temperatura. Son una fuente importante de proteína. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-bufalo.png', alt='Búfalos', class="img-fluid rounded-start")
      .tarjeta.p-3(x="2.4%" y="71%" tooltip="Equinos")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Equinos
            p A este grupo pertenecen, principalmente, caballos, asnos y mulares. Estos animales se utilizan a menudo como apoyo en las labores del campo, en el deporte, las exposiciones, la producción de genética, la recreación y la producción de carne. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-equinos.png', alt='Equinos', class="img-fluid rounded-start")
      .tarjeta.p-3(x="2.4%" y="88%" tooltip="Ovinos")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Ovinos
            p Es uno de los sistemas de ganadería más antiguos y conocidos del mundo. Estos animales, por lo general, se destinan para la obtención de carne, especialmente los camuros, y lana, como en el caso de las ovejas. Estos animales poseen un amplio rango de adaptación climática. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-ovinos.png', alt='Ovinos', class="img-fluid rounded-start")
      //- Comienza segunda columna
      .tarjeta.p-3(x="98%" y="6%" tooltip="Caprinos")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Caprinos
            p Junto con los ovinos, los caprinos también pertenecen al grupo de los pequeños rumiantes y son una de las explotaciones pecuarias más populares debido a su gran capacidad adaptativa. En este grupo se destaca la producción de cabras doble propósito. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-caprinos.png', alt='Caprinos', class="img-fluid rounded-start")            
      .tarjeta.p-3(x="98%" y="23%" tooltip="Otras aves")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Otras aves
            p Además del pollo de engorde y la gallina ponedora, existen otras aves que igualmente se consideran de importancia económica debido a su participación en el ámbito comercial. 
            p Entre estas se encuentran pavos, patos, codornices, gansos, palomas y aves ornamentales. Estos animales se encuentran en múltiples rangos de altitud y temperatura, lo cual resulta muy favorable desde el punto de vista técnico. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-otras-aves.png', alt='Otras aves', class="img-fluid rounded-start")            
      .tarjeta.p-3(x="98%" y="39%" tooltip="Otras especies menores")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Otras especies menores
            p Dentro de este grupo de especies menores destacan actividades productivas como la cunicultura y la producción de cuy.
            p Estos animales se constituyen en fuente importante de alimento a muy bajo costo. Además de la carne, su piel también es aprovechable.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-otras-especies-menores.png', alt='Otras especies menores', class="img-fluid rounded-start")            
      .tarjeta.p-3(x="98%" y="55%" tooltip="Peces")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Peces
            p Este es otro de los grandes grupos de especies animales capaces de constituir proyectos productivos con altos niveles de rentabilidad.
            p Este tipo de proteínas tienen una alta demanda en diversos espacios, además que estos montajes se adaptan a diversas condiciones agroecológicas.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-peces.png', alt='Peces', class="img-fluid rounded-start")            
      .tarjeta.p-3(x="98%" y="71%" tooltip="Especies no convencionales")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Especies no convencionales
            p Recientemente, algunas especies animales han empezado a adquirir relevancia en el escenario productivo debido a su potencial alimenticio.
            p Dentro de este grupo destacan reptiles como iguanas, babillas y tortugas hicoteas. También existen explotaciones de caracoles, avestruces, llamas y alpacas.
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-especies-no-convencionales.png', alt='Especies no convencionales', class="img-fluid rounded-start")            
      .tarjeta.p-3(x="98%" y="88%" tooltip="Insectos y anélidos")
        .row.bg-white.p-4.rounded
          .col-md-6
            h4 Insectos y anélidos
            p Existen iniciativas de cría de mariposas con fines ornamentales; explotación apícola para la obtención de miel y polen, larvas de gusano de seda, lombriz roja californiana para la producción de proteína animal o para la transformación de los subproductos de la industria agropecuaria. 
          .col-md-6
            figure
              img(src='@/assets/curso/tema1/1_4-insectos.png', alt='Insectos y anélidos', class="img-fluid rounded-start")            

    ol.lista-ol--cuadro
      li.fw-bold
        .lista-ol--cuadro__vineta
          span.fw-bold 
        | Aplicabilidad de los registros

    p Los registros son muy útiles para evaluar y monitorear la situación ambiental del agroecosistema, entre otras aplicaciones:

    .row.mt-5
      .col-md-5
        figure
          img(src='@/assets/curso/tema1/1_4-aplicabilidad.png', alt='Aplicabilidad de los registros', class="img-fluid rounded-start")            
      .col.p-4
        ul.lista-ul--color
          li 
            i.fas.fa-check
            | Sirven como historial ambiental del agroecosistema.
          li 
            i.fas.fa-check
            | Permite medir el impacto positivo o negativo de las prácticas de manejo ecológico o agroecológico, o el avance del agroecosistema cuando se avanza en un proceso de reconversión o transición
          li 
            i.fas.fa-check
            | Permiten observar cambios bruscos en el agroecosistema y analizar la fuente del problema. Por ejemplo: un descenso en la población de abejas puede indicar alguna fuente de contaminación con agroquímicos.
          li 
            i.fas.fa-check
            | Son documentos válidos tenidos en cuenta en procesos de certificación ecológica o de esquemas de sostenibilidad. 
          li 
            i.fas.fa-check
            | Sirven para comparar el agroecosistema con otros aledaños.
          li 
            i.fas.fa-check
            | Son evidencias útiles para procesos pedagógicos o de investigación. 
          li 
            i.fas.fa-check
            | Son un insumo esencial para graficar y procesar la información ambiental del agroecosistema, y en general del plan de manejo aplicado.

    Separador

    #parametros.titulo-segundo.color-acento-contenido
      h2 1.5 Parámetros productivos

    .row
      .col-md-7
        p Dependiendo de lo que se quiera medir al interior de la explotación pecuaria se pueden identificar y cuantificar cuantos parámetros productivos se consideren necesarios, para lo cual es necesario diseñar y diligenciar registros que permitan hacer un seguimiento detallado del comportamiento de estos importantes indicadores.
        br
        ol.lista-ol--cuadro
          li.fw-bold
            .lista-ol--cuadro__vineta
              span.fw-bold 
            | Parámetros productivos
        p Los parámetros productivos son variables cuantificables y observables que permiten analizar detalladamente el comportamiento de las unidades pecuarias en cualquiera de sus etapas, estos permiten evaluar los rendimientos y, además, facilitar la toma de decisiones administrativas teniendo en cuenta factores técnicos y productivos. Algunos de los parámetros productivos que se pueden medir al interior de las principales explotaciones pecuarias son los siguientes:
      .col-md-5
        figure
          img(src='@/assets/curso/tema1/1_5-parametros-productivos.png', alt='Parámetros productivos', class="img-fluid rounded-start")

    br

    TabsC.color-acento-contenido
      .py-3.py-md-4(titulo="Parámetros productivos bovinos, bufalinos, ovinos y caprinos")
        .row.justify-content-center: .col-md-10: p.fw-bold Parámetros productivos bovinos, bufalinos, ovinos y caprinos
        .row.justify-content-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/1_5-tab-parametros-bovinos.png', alt='Parámetros productivos bovinos, bufalinos, ovinos y caprinos', class="img-fluid rounded-start")      
          .col-md-7
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Especie
                    th Par&aacute;metro productivo
                    th Unidad
                tbody
                  tr
                    td(rowspan='11') Bovinos - bufalinos - ovinos - caprinos
                    td Peso promedio al nacer.
                    td Kg
                  tr
                    td Peso promedio al destete.
                    td Kg
                  tr
                    td Edad promedio al destete.
                    td Meses
                  tr
                    td N&uacute;mero de terneros.
                    td N&uacute;mero de animales
                  tr
                    td N&uacute;mero de terneras.
                    td N&uacute;mero de animales
                  tr
                    td Porcentaje de nacimiento de hembras.
                    td Porcentaje
                  tr
                    td Mortalidad anual de lactantes.
                    td N&uacute;mero de animales
                  tr
                    td Mortalidad anual de adultos.
                    td N&uacute;mero de animales
                  tr
                    td Producci&oacute;n de leche diaria.
                    td Litros
                  tr
                    td N&uacute;mero mensual de partos.
                    td N&uacute;mero de partos
                  tr
                    td Ganancia de peso mensual.
                    td Kilogramos / mes
      .py-3.py-md-4(titulo="Parámetros productivos para aves")
        .row.justify-content-center: .col-md-10: p.fw-bold Parámetros productivos para aves
        .row.justify-content-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/1_5-tab-parametros-aves.png', alt='Parámetros productivos para aves', class="img-fluid rounded-start")      
          .col-md-7
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Especie
                    th Par&aacute;metro productivo
                    th Unidad
                tbody
                  tr
                    td(rowspan='11') Aves
                    td Aves que inician - aves que finalizan.
                    td Número de animales
                  tr
                    td Mortalidad diaria.
                    td Número de animales
                  tr
                    td Mortalidad acumulada.
                    td Porcentaje
                  tr
                    td Peso corporal.
                    td Gramos
                  tr
                    td Longitud del pico.
                    td Milímetros
                  tr
                    td Longitud del tarso.
                    td Centímetros
                  tr
                    td Consumo de alimento diario.
                    td Gramos
                  tr
                    td Conversión de alimento.
                    td Kilogramo / Kilogramo
                  tr
                    td Masa del huevo.
                    td Gramos
                  tr
                    td Huevos día.
                    td Número de huevos
                  tr
                    td Porcentaje de pérdida de huevos.
                    td 
      .py-3.py-md-4(titulo="Parámetros productivos para porcinos")
        .row.justify-content-center: .col-md-10: p.fw-bold Parámetros productivos para porcinos
        .row.justify-content-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/1_5-tab-parametros-porcinos.png', alt='Parámetros productivos para porcinos', class="img-fluid rounded-start")      
          .col-md-7
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Especie
                    th Par&aacute;metro productivo
                    th Unidad
                tbody
                  tr
                    td(rowspan='10') Porcinos
                    td Edad a la primera monta.
                    td Meses
                  tr
                    td Peso corporal.
                    td Kilogramos
                  tr
                    td Conversión de alimento.
                    td Kilogramos
                  tr
                    td Edad al sacrificio.
                    td Días
                  tr
                    td Intervalo destete monta.
                    td Meses
                  tr
                    td Abortos.
                    td Número de abortos
                  tr
                    td Porcentaje de partos.
                    td Porcentaje
                  tr
                    td Lechones nacidos vivos por camada.
                    td Número de lechones
                  tr
                    td Lechones nacidos muertos.
                    td Número de lechones
                  tr
                    td Partos/Cerda/Año.
                    td Número de partos
      .py-3.py-md-4(titulo="Parámetros productivos para especies menores")
        .row.justify-content-center: .col-md-10: p.fw-bold Parámetros productivos para especies menores
        .row.justify-content-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/1_5-tab-parametros-especies-menores.png', alt='Parámetros productivos para especies menores', class="img-fluid rounded-start")      
          .col-md-7
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Especie
                    th Par&aacute;metro productivo
                    th Unidad
                tbody
                  tr
                    td(rowspan='10') Especies menores (conejos - cuyes)
                    td Edad destete.
                    td Días
                  tr
                    td Peso crías al nacer.
                    td Gramos
                  tr
                    td Número de crías al año.
                    td Número de animales
                  tr
                    td Partos al año.
                    td Número de partos
                  tr
                    td Peso.
                    td Kilogramos
                  tr
                    td Camadas/hembra/año.
                    td Número de camadas
                  tr
                    td Peso crías al destete.
                    td Gramos
                  tr
                    td Edad al sacrificio.
                    td Días
                  tr
                    td Madurez sexual machos.
                    td Días
                  tr
                    td Madurez sexual hembras.
                    td Días
      .py-3.py-md-4(titulo="Parámetros productivos para peces")
        .row.justify-content-center: .col-md-10: p.fw-bold Parámetros productivos para peces
        .row.justify-content-center
          .col-md-3
            figure
              img(src='@/assets/curso/tema1/1_5-tab-parametros-peces.png', alt='Parámetros productivos para peces', class="img-fluid rounded-start")      
          .col-md-7
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Especie
                    th Par&aacute;metro productivo
                    th Unidad
                tbody
                  tr
                    td(rowspan='7') Peces
                    td Peso inicial.
                    td Kilogramos
                  tr
                    td Peso final.
                    td Kilogramos
                  tr
                    td Edad al sacrificio
                    td Días
                  tr
                    td Densidad por metro cúbico
                    td Peces / m
                      sup 3
                  tr
                    td Ingesta total individuo.
                    td Gramos
                  tr
                    td Longitud total final individuo
                    td Centímetros
                  tr
                    td Mortalidad.
                    td Porcentaje

    Separador
    #practicas.titulo-segundo.color-acento-contenido
      h2 1.6 Buenas prácticas pecuarias

    .bloque-texto-g.m-5.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/1_6-buenas-practicas.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0: span.color-texto-uno Las buenas prácticas agrícolas y las buenas prácticas pecuarias son acciones encaminadas a la reducción de riesgos de deterioro del medio ambiente y de la contaminación cruzada de los productos agropecuarios; 
        | a través de prácticas de manejo la higiénicas y seguras por parte de los trabajadores, contando con los elementos necesarios para tener procesos productivos donde se conserven los productos inocuos y saludables.
        br

    ol.lista-ol--cuadro
      li.fw-bold
        .lista-ol--cuadro__vineta
          span.fw-bold 
        | Buenas prácticas pecuarias - BPP

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-8
        p Según el Instituto Colombiano Agropecuario, estas se relacionan con las prácticas que se deben llevar a cabo en los sistemas pecuarios para disminuir los riesgos físicos, químicos y biológicos que puedan llegar a afectar la salud de los consumidores.
      .col.col-3.mb-4
        img(src="@/assets/curso/tema1/1_6-logo-ica.png")

    .titulo-quinto.color-acento-contenido
      h4 Principales aspectos de las Buenas Prácticas Pecuarias - BPP

    .row.justify-content-center.mt-5
      .col.col-md-8
        img(src="@/assets/curso/tema1/1_6-buenas-practicas-bbp.png")
   
    br

    TabsB.color-acento-contenido.mt-5
      .py-4.py-md-5(titulo="Principales aspectos de las Buenas Prácticas Pecuarias - BPP" :icono="require('@/assets/curso/tema1/1_6-tab-icon1.svg')")
        .row
          .col-md-7
            h4 Principales aspectos de las Buenas Prácticas Pecuarias - BPP
            p De acuerdo con la FAO, consisten en “la aplicación del conocimiento disponible a la utilización sostenible de los recursos naturales básicos para la producción, en forma benévola, de productos agrícolas alimentarios y no alimentarios inocuos y saludables, a la vez que se procuran la viabilidad económica y la estabilidad social”.
          .col-md-4
            img(src="@/assets/curso/tema1/1_6-tab1-imagen.jpg")
      .py-4.py-md-5(titulo="Marco normativo de las Buenas Prácticas Pecuarias (BPP) – Buenas Prácticas Ganaderas (BPG)" :icono="require('@/assets/curso/tema1/1_6-tab-icon2.svg')")
        .row
          .col-md-7
            h4 Marco normativo de las Buenas Prácticas Pecuarias (BPP) – Buenas Prácticas Ganaderas (BPG)
            p De acuerdo con lo expuesto por el Instituto Colombiano Agropecuario, existe un marco normativo para todos los aspectos relacionados con las buenas prácticas (sean pecuarias o ganaderas) que contribuye a la disminución de los riesgos a la salud asociados con el consumo de alimentos de origen animal.
          .col-md-4
            img(src="@/assets/curso/tema1/1_6-tab2-imagen.jpg")
      .py-4.py-md-5(titulo="Protocolos para acceder a la certificación" :icono="require('@/assets/curso/tema1/1_6-tab-icon3.svg')")
        .row
          .col-md-12
            h4 Protocolos para acceder a la certificación
          .col-md-12
            img(src="@/assets/curso/tema1/1_6-tab3-imagen.svg")

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
