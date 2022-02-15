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

        .row(titulo="Jaulas").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Jaulas 
            p En la producción de especies menores bajo sistemas intensivos, principalmente de carne, se emplean jaulas como la de la imagen. En ellas se restringe la movilidad del animal y se le proporciona agua y alimento.
            p En sistemas extensivos se emplean jaulas itinerantes que se pueden desplazar de un lugar a otro dependiendo de la disponibilidad de alimento, permitiendo al animal la posibilidad de pastorear.
          .col-md-5
            img(src='@/assets/curso/tema3/3_linea_jaulas.png', alt='Jaulas')

        .row(titulo="Apriscos").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Apriscos 
            p Estos se construyen elevados del suelo, aproximadamente a 80 cm, en un sistema que se denomina tarima. Con este sistema se evita que los animales entren en contacto con las excretas, además que facilita el aseo de las instalaciones. Igualmente, el sitio de ordeño también se debe ubicar sobre una tarima, lo cual facilita la labor del operario.
          .col-md-5
            img(src='@/assets/curso/tema3/3_linea_apriscos.png', alt='Apriscos')

        .row(titulo="Galpones").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Galpones para aves 
            p La producción de aves de corral se puede realizar de forma extensiva, semiintensiva e intensiva. Dependiendo del tipo de explotación así mismo se debe escoger el diseño del galpón. En la fotografía se observa un montaje semiintensivo el cual tiene unos requerimientos mínimos, como son el encerramiento y la cubierta. 
            p Por otro lado, en las explotaciones intensivas la demanda de insumos, recursos, equipos y mano de obra es mucho mayor, pues por unidad de área se tiene una mayor cantidad de animales, los que demandan gran cantidad de alimentos, medicinas y agua, entre otras cosas. Generalmente este tipo de estructuras utilizan una cubierta a dos aguas, con cortinas laterales para el manejo de la temperatura, y un piso cubierto con un material blando, principalmente, cascarilla de arroz.
          .col-md-5
            img(src='@/assets/curso/tema3/3_linea_galpones.png', alt='Galpones')

        .row(titulo="Estanques").justify-content-center
          .col-md-5.mb-4.mb-md-0
            h4 Estanques para peces 
            p En la actualidad existen múltiples diseños los cuales se acomodan a las necesidades de los productores y la disponibilidad de recursos. Estos pueden ser cavados directamente en el suelo o construidos con materiales que permitan almacenar el agua necesaria para la explotación, como es el caso de los estanques de geomembrana que se aprecian en la fotografía.
          .col-md-5
            img(src='@/assets/curso/tema3/3_linea_estanques.png', alt='Estanques para peces')    

    #caracteristicas.titulo-segundo.color-acento-contenido
      h2 3.1.2 Áreas mínimas

    .row
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-11.mb-4
        p Cada una de las especies pecuarias tiene unos requerimientos mínimos de espacio en los cuales puede desarrollarse normalmente y satisfacer sus necesidades básicas. Con base en este requerimiento, por animal, es posible estimar el área a construir para alojar a los animales en buenas condiciones, de acuerdo con lo recomendado para cumplir con las Buenas Prácticas Pecuarias - BPP. 

    TabsA.color-acento-botones.mb-5
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.p-4.bg-tema3(titulo="Ganado bovino - bufalino")
        h4 Áreas mínimas ganado bovino - bufalino
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr.text-center
                th Categoria
                th Área de descanso por animal adulto
                th Área de alimentación por animal adulto
                th Ancho de plaza comedero por animal adulto
            tbody.bg-white
              tr.text-center
                td.fw-bold Ganado bovino – bufalino
                td 5 m
                  sup 2
                td 2,5 m
                  sup 2
                td 0,8 m
        .row
          .col-xl-3.mb-4
            figure
              img(src='@/assets/curso/tema3/3_1_2-tab1.png', alt='Ganado bovino - bufalino')
          .col-xl-9
            p El área de la pradera se estima mediante la medición de la cantidad de forraje disponible por metro cuadrado de potrero. Para esto es importante saber que un animal adulto, en el caso de bovinos, puede consumir hasta el 10 % de su peso en alimento al día. Es decir que si una vaca pesa 350 kilogramos, en un día consumirá 35 kilogramos de forraje. Si por cada metro cuadrado se tienen, por ejemplo, 2,8 kilogramos de forraje, para saber qué área de pastoreo requiere el animal basta con dividir los kilogramos que debe consumir el animal entre los kilogramos que produce un metro cuadrado. 

      .tarjeta.p-4.bg-tema3(titulo="Equinos")
        h4 Áreas mínimas equinos
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr.text-center
                th Categoria
                th Área pesebrera por adulto
                th Ancho de plaza adulto
            tbody.bg-white
              tr.text-center
                td.fw-bold Caballos – mulares (pesado)
                td 11,5 m
                  sup 2
                td 0,9 m - 1 m
              tr.text-center
                td.fw-bold Asnos (semipesado)
                td 8,5 m
                  sup 2
                  | - 10 m
                  sup 2
                td 0,9 m
        p El ancho de plaza indica el espacio que ocupa un equino en el comedero teniendo en cuenta su longitud transversal. 

      .tarjeta.p-4.bg-tema3(titulo="Porcinos")
        h4 Áreas mínimas para porcinos
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr.text-center
                th Categoria
                th Área porqueriza por animal
            tbody.bg-white
              tr.text-center
                td.fw-bold Lechones
                td 0,25 m
                  sup 2
              tr.text-center
                td.fw-bold Adultos jóvenes
                td 0,5 m
                  sup 2
              tr.text-center
                td.fw-bold Adultos
                td 1 m
                  sup 2
              tr.text-center
                td.fw-bold Jaula para cerdas de cría
                td 0,9 m
                  sup 2
                  |  (ancho 0,45 m x largo 2,20 m)

        p En las explotaciones semitecnificadas, el espacio para la cerda de cría con sus lechones puede ser de 7 m
          sup 2
          | , donde el 60%, aproximadamente, del área es para la cerda y el restante 40% es para las crías. 


      .tarjeta.p-4.bg-tema3(titulo="Caprinos")
        h4 Áreas mínimas para caprinos
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr.text-center
                th Categoria
                th Área cubierta
                th Área descubierta
            tbody.bg-white
              tr.text-center
                td.fw-bold Recién nacidos (0 a 3 meses)
                td 1 m
                  sup 2
                td 1 m
                  sup 2
              tr.text-center
                td.fw-bold Destetos (4 a 8 meses)
                td 1,5 m
                  sup 2
                td 2 m
                  sup 2
              tr.text-center
                td.fw-bold Adultos
                td 2 m
                  sup 2
                td 2,5 m
                  sup 2
              tr.text-center
                td.fw-bold Gestantes
                td 2,5 m
                  sup 2
                td 2,5 m
                  sup 2
              tr.text-center
                td.fw-bold Machos
                td 3 m
                  sup 2
                td 3 m
                  sup 2

      .tarjeta.p-4.bg-tema3(titulo="Ovinos")
        h4 Áreas mínimas para ovinos
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr.text-center
                th Categoria
                th Área
            tbody.bg-white
              tr.text-center
                td.fw-bold Ovejas
                td 1,5 – 2 m
                  sup 2
              tr.text-center
                td.fw-bold Crías (3 a 4 animales)
                td 1 m
                  sup 2
              tr.text-center
                td.fw-bold Corderas (2 a 3 animales)
                td 1 m
                  sup 2
              tr.text-center
                td.fw-bold Machos
                td 4 – 6 m
                  sup 2

      .tarjeta.p-4.bg-tema3(titulo="Especies menores")
        h4 Áreas mínimas para especies menores
        .tabla-a.color-acento-contenido.mb-5 
          table.mt-1
            thead
              tr.text-center
                th
                th Categoria
                th Animales por metro cuadrado galpón/ jaula
                th Animales por metrocuadrado pastoreo
            tbody.bg-white
              tr.text-center
                td(rowspan='4').fw-bold Gallinas, pollos y codornices
                td.fw-bold Gallina ponedora
                td 6
                td 3,4
              tr.text-center
                td.fw-bold Pollo de engorde
                td 8 - 12
                td No aplica
              tr.text-center
                td.fw-bold Codornices de postura
                td 64
                td No aplica
              tr.text-center
                td.fw-bold Codornices de engorde
                td 100
                td No aplica

        .tabla-a.color-acento-contenido.mb-5 
          table.mt-1
            thead
              tr.text-center
                th
                th Categoria
                th Dimensiones de la jaula
                th Número de animales
            tbody.bg-white
              tr.text-center
                td(rowspan='4').fw-bold Conejos
                td.fw-bold Conejos levante
                td 0,75 m x 0,5 m x 0,4 m
                td 5
              tr.text-center
                td.fw-bold Coneja con sus crías (incluido nidal)
                td 0,75 m x 0,5 m x 0,4 m
                td 9
              tr.text-center
                td.fw-bold Machos reproductores
                td 0,75 m x 0,5 m x 0,4 m
                td No aplica
     
        .tabla-a.color-acento-contenido.mb-5 
          table.mt-1
            thead
              tr.text-center
                th
                th Categoria
                th Dimensiones de la jaula
                th Número de animales
            tbody.bg-white
              tr.text-center
                td(rowspan='2').fw-bold Cuyes
                td.fw-bold Cuyes empadre y maternidad
                td 1 x 1,5 m
                td 10 hembras /1 macho
              tr.text-center
                td.fw-bold  Recría 
                td 1 x 0,7 m
                td 10 machos

      .tarjeta.p-4.bg-tema3(titulo="Peces")
        h4 Áreas mínimas para peces
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr.text-center
                th Especie
                th Densidad final. Aproximado de peces por m
                  sup 2
            tbody.bg-white
              tr.text-center
                td.fw-bold Cachama blanca
                td 4
              tr.text-center
                td.fw-bold Mojarra roja
                td 15
              tr.text-center
                td.fw-bold Tilapia
                td 4 - 15

    #caracteristicas.titulo-segundo.color-acento-contenido
      h2 3.1.3 Dimensiones

    .row.mb-4
      .col.col-12.col-md-7.mb-4
        p Las dimensiones de las instalaciones para la cría de especies pecuarias dependen del número de animales que se desee alojar. Puesto que existe información detallada sobre las densidades que se manejan en las diversas explotaciones, sean intensivas, semiintensivas y extensivas, es fácil calcular qué área construida se requiere para asegurar el bienestar animal. 
        p Para el cálculo de áreas solamente se debe conocer el área que ocupa un solo ejemplar, por lo que es importante definir con cuántos animales se iniciará la explotación. 
        p A continuación, se presentan algunos ejemplos.
      .col.col-12.col-md-5
        img(src="@/assets/curso/tema3/3.1.3-img.png")
    br
    .row.border.border-primary
      .col.col-12.col-md-6.p-3
        h4 Corral para ganado bovino.
        p Área por animal adulto: 5 m
          sup 2 
          | - número de animales: 10 – ancho de plaza comedero: 0,8 m

        p Con base en estos datos, en primer lugar, se estima el área total del corral:

        ul.lista-ul--color
          li 
            i.fas.fa-check
            | 5 m²/ animal x 10 animales = 50 m². Es decir que para alojar a los 10 animales se debe construir un corral de por lo menos 50 metros cuadrados. 

        p En segundo lugar, se calcula el espacio del comedero:

        ul.lista-ul--color
          li 
            i.fas.fa-check
            | 0,8 m ancho de plaza/ animal x 10 animales = 8 metros. Esto indica que la longitud del comedero debe ser de por lo menos 8 metros lineales.

        p En tercer lugar, se distribuye el área del corral, de acuerdo con los datos obtenidos en los anteriores pasos.
      .col.col-12.col-md-6.p-0
        img(src="@/assets/curso/tema3/3_1_3-corral-bovino.jpg")

    br
    .row.mt-4
      .col.col-1
        img(src="@/assets/curso/tema1/caracteristicas.png")
      .col.col-11.mb-4
        p En este caso se obtiene un corral de 50 metros cuadrados efectivos con dos comederos de 4 metros de largo cada uno y un bebedero. Este tipo de corrales, para alojamiento temporal, generalmente son cubiertos por lo que con esta estimación también es posible identificar la necesidad de materiales para esta estructura.

    br
    .row.justify-content-md-center.border-primary.mb-4
      .col.col-lg-5.p-3
        h4 Galpón para pollos de engorde.
        p En el caso de los pollos de engorde se estima que en sistemas intensivos se pueden tener hasta 12 animales por metro cuadrado, por lo que, por ejemplo, para un montaje de 100 pollos las dimensiones de la instalación serían conforme a los siguientes parámetros:

        ul.lista-ul--color
          li 
            i.fas.fa-check
            | Número de animales por metro cuadrado: 12
          li 
            i.fas.fa-check
            | Número de animales para la explotación: 100

        p Primero se determina el área necesaria para los 100 pollos. Esto se logra dividiendo el número total de animales a alojar por el número de animales que se alojan por metro cuadrado.

        ul.lista-ul--color
          li 
            i.fas.fa-check
            | 100 animales por alojar ÷ 12 animales/ m² = 8,3 m². Es decir que el área que necesaria para alojar 100 pollos es de 8,3 metros cuadrados. 

        p En tercer lugar, se distribuye el área del corral, de acuerdo con los datos obtenidos en los anteriores pasos.
      .col.col-lg-5.p-0
        img(src="@/assets/curso/tema3/3_1_3-pollos-engorde.jpg")

    p.mb-5 Para estimar la densidad de animales por unidad de área, es importante conocer las diferentes unidades de área, longitud y volumen empleadas en la agricultura, con el fin de hacer las respectivas conversiones. A continuación, se presentan las más empleadas.

    .titulo-quinto.color-acento-contenido
      h4 Principales unidades empleadas en actividades pecuarias

    .row
      .col.col-4
        img(src="@/assets/curso/tema3/3_1_3-principales-unidades.png")
      .col.col-8
        TabsC.color-acento-contenido
          .py-3.py-md-4(titulo="Unidades de longitud")
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Unidad
                    th Equivalencia en metros
                tbody
                  tr
                    td Metro
                    td 1
                  tr
                    td Kilómetro
                    td 1.000
                  tr
                    td Decámetro 
                    td 10
                  tr
                    td Decímetro 
                    td 0,1
                  tr
                    td Centímetro 
                    td 0,01
                  tr
                    td Milímetro
                    td 0,001
                  tr
                    td Milla
                    td 1.609,34
                  tr
                    td Pie
                    td 0,3048
                  tr
                    td Yarda
                    td 0,9144
                  tr
                    td Pulgada
                    td 0,0254
          .py-3.py-md-4(titulo="Unidades de Área")
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Unidad
                    th Equivalencia en m
                      sup 2
                tbody
                  tr
                    td Hectarea
                    td 10.000
                  tr
                    td Acre
                    td 4.046,86
                  tr
                    td Pie
                      sup 2
                    td 0,092
                  tr
                    td Pulgada
                      sup 2
                    td 0,00064516
                  tr
                    td Yarda
                      sup 2
                    td 0,83
                  tr
                    td Km
                      sup 2
                    td 1.000.000
                  tr
                    td Fanegada
                    td 6.400
          .py-3.py-md-4(titulo="Unidades de volumen")
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th Unidad
                    th Equivalencia en Litros
                tbody
                  tr
                    td Metro
                      sup 3
                    td 1.000
                  tr
                    td Galón EEUU
                    td 3,78
                  tr
                    td Pinta EEUU 
                    td 0,47
                  tr
                    td Onza líquida 
                    td 0,029
                  tr
                    td Mililitro 
                    td 0,001
                  tr
                    td Pie
                      sup 3
                    td 28,31
                  tr
                    td Pulgada
                      sup 3
                    td 0,016
                  tr
                    td Galón imperial
                    td 4,54
                  tr
                    td Pinta imperial
                    td 0,56
                  tr
                    td Onza líquida imperial
                    td 0,028

    .row.mt-5.justify-content-center
      .col-lg-10
        .cajon.color-primario.p-4.mb-4
          p Las instalaciones para el alojamiento, manejo, protección y alimentación de las especies pecuarias deben proporcionar, entre otras cosas, lo siguiente:

          ul.lista-ul--color
            li 
              i.fas.fa-check
              | Protección frente a los elementos: lluvia, frío, viento, sol, calor, humedad.
            li 
              i.fas.fa-check
              | Un piso seco, firme, bien drenado y no resbaladizo que sea resistente a la orina y los excrementos
            li 
              i.fas.fa-check
              | Protección frente a depredadores.
            li 
              i.fas.fa-check
              | Espacio para desplazarse y ejercitarse
            li 
              i.fas.fa-check
              | Dependiendo del sistema, es ideal disponer de una zona de pastoreo

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
