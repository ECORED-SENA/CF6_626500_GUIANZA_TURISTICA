<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Seguridad turística
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Esta es definida como el “estado de confianza, en el que el individuo se sitúa, protegiendo el valor social en torno al turismo y el sistema turístico, asegurando la biodiversidad y su naturaleza” (Olmos, 2021).
          br
          br
          |Una de las necesidades prioritarias que deben atender y satisfacer los prestadores de servicios turísticos es la seguridad, controlando o minimizando los peligros y las condiciones de riesgo derivadas de estos.
    p.mb-5(data-aos='fade-right') Para tener en cuenta...
    div(style='background-color: #ffe6a1').p-5.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-1.col-3.mb-lg-0.mb-3: img(src='@/assets/curso/temas/tema2/37.svg', alt='')
        .col-lg-11 
          p.mb-0 La seguridad turística es la capacidad para dar seguridad en los escenarios físicos, las condiciones necesarias y suficientes para que turistas nacionales y extranjeros, las comunidades receptoras y los actores en general puedan desarrollar actividades turísticas en espacios libres de cualquier riesgo, ya sean estos de tipo físico, material, psicológico o ambiental, los cuales se deben tener presentes al momento de diseñar un evento turístico. 
    Separador
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 4.1 Fases de la seguridad turística
    p.mb-5(data-aos='fade-right') Cuando requiera diseñar un evento o gestionar un proyecto turístico a nivel nacional debe tener en cuenta las fases de la seguridad turística, el siguiente recurso las muestra con los elementos que favorecen la prestación de servicios turísticos de calidad a connacionales y extranjeros.
    h3 Representación de las fases de la seguridad turística
    p.mb-5(data-aos='fade-right') Las fases de ña seguridad turística son tres, las cuales se describen a continuación:
    .row.justify-content-center.mb-5
      .col-lg-9
        TabsA.color-acento-contenido.mb-5
          .tarjeta.p-5(titulo="Identificación y diagnóstico" style='background-color: #ccd3ca')
            h6 Identificación y diagnóstico
            p Los elementos que se deben tener en cuenta en esta fase son:
            ul.lista-ul--color
              li
                i.vineta
                | Problemáticas locales
              li
                i.vineta
                | Condiciones iniciales de seguridad
              li
                i.vineta
                | Partes involucrados
              li
                i.vineta
                | Tipologías del riesgo

              li
                i.vineta
                | Protocolos existentes
              li
                i.vineta
                | Diseño y matriz del riesgo
          .tarjeta.p-5(titulo="Desarrollo de protocolos de seguridad" style='background-color: #ccd3ca')
            h6 Desarrollo de protocolos de seguridad
            p Los elementos que se deben diseñar y aplicar en esta fase son:
            ul.lista-ul--color
              li
                i.vineta
                | Desarrollo del plan de acción
              li
                i.vineta
                | Desarrollo del plan de contingencia
              li
                i.vineta
                |  Diseño de protocolos de seguridad
          .tarjeta.p-5(titulo="Ejecución" style='background-color: #ccd3ca')
            h6 Ejecución
            p Los elementos que se deben ejecutar en esta fase son:
            ul.lista-ul--color
              li
                i.vineta
                | Talleres de socialización 
              li
                i.vineta
                | Capacitación
              li
                i.vineta
                | Acuerdos colectivos de seguridad
              li
                i.vineta
                | Informe
              li
                i.vineta
                | Medición de resultados
      .col-lg-3.col-8: img(src='@/assets/curso/temas/tema4/3.svg', alt='')
    .bg-1.margin-n.p-5.mb-5
      .row.justify-content-center
        .col-lg-6
          p.mb-5(data-aos='fade-right') Con el cumplimiento de las actividades propuestas en las fases los prestadores de servicios turísticos deben buscar los siguientes objetivos:
          ul.lista-ul--color
            li
              i.vineta
              | Coordinar las actuaciones del equipo de trabajo y los grupos de apoyo.
            li
              i.vineta
              | Capacitar, informar y sensibilizar las partes involucradas.
            li
              i.vineta
              | Coordinar las actuaciones de los turistas.
            li
              i.vineta
              | Identificar y de ser necesario complementar los protocolos de seguridad existentes.
            li
              i.vineta
              | Mejorar la competitividad empresarial y el destino.
            li
              i.vineta
              | Diseñar e implementar protocolos en seguridad turística.
        .col-lg-6.col-8: img(src='@/assets/curso/temas/tema4/4.svg', alt='')
    Separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 4.2 Protocolos de seguridad
    p.mb-5(data-aos='fade-right') El protocolo es definido como un conjunto de reglas establecidas por norma, que hacen parte de un proceso en caso de ceremonias, actos oficiales o solemne, es una estructura de planeación que tiene campo de acción en todas las actividades del sector turismo y es un término afianzado por el guía de turismo como parte de su comprensión de las funciones asignadas.  
      br
      br
      |Pueden existir en el turismo tantos protocolos en seguridad como actividades y lugares donde el guía y sus turistas desarrollan las actividades, en el recurso de aprendizaje se mencionan algunos de estos protocolos que se oficializan en este caso desde el Viceministerio de Turismo (Ministerio de Comercio Industria y Turismo & Fontur, 2013).
    h3 Protocolos de seguridad turística
    p.mb-5(data-aos='fade-right') La Organización Mundial de Turismo considera que es responsabilidad de cada país la seguridad de los turistas que llegan a visitar la región, por lo que Colombia, mediante las políticas creadas, la policia de turismo y acuerdos con las entidades que ofrecen estos servicios, tienen protocolos que deben tenerse en cuenta: 
    SlyderF.slyder-100.mb-5(columnas="col-lg-4 col-xl-4")
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/5.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Huracanes
        p.text-center En caso de desastres, emergencias y accidentes.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/6.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Guerras
        p.text-center En situaciones  sociales  o antropológicas.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/7.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Tsunami Indonesia
        p.text-center En instalaciones turísticas.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/8.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center COVID-19
        p.text-center En situaciones de seguridad biosanitaria, salud y sanidad.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/9.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Paros ciudadanos
        p.text-center En situaciones de seguridad en el entorno.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/10.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Información digital
        p.text-center En seguridad de la información.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/11.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Conciertos
        p.text-center En situaciones de seguridad de eventos y aglomeraciones.
      .tarjeta(style='background-color: #ffd667').p-4.h-100
        .row.justify-content-center.mb-3
          .col-11
            img(src='@/assets/curso/temas/tema4/12.jpg' alt='AvatarTop' style='border-radius: 20px')
        h6.text-center Titanic
        p.text-center En situaciones de seguridad vial y de transporte en rutas turísticas.
    p.mb-5(data-aos='fade-right') El Plan Estratégico de Seguridad Turística pretende aplicar desde el ámbito local, regional y nacional los principios y objetivos que velan por la seguridad del turista, resaltando las responsabilidades de los Consejos Regionales de Seguridad Turística que cuentan con una estructura público-privada.
      br
      br
      |En línea con lo anterior se invita a revisar el siguiente documento en el cual encuentra un ejemplo para la elaboración e implementación de protocolos.
    //todo! Añadir documento ----------------------------------------------------------------------------------------------
    .tarjeta.color-primario.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/temas/tema1/40.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              p.mb-0 Elaboración e implementación de protocolos de seguridad turística.
            .col-sm-auto
              .d-block
                a.boton.color-acento-botones.texto-blanco(href="https://www.mincit.gov.co/CMSPages/GetFile.aspx?guid=7e631b5f-d82c-4c49-89e9-27a8248d7a49" target="_blank")
                  span Ir al sitio web
                  i.fas.fa-file-download
    Separador
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 4.3 Planes de emergencia y evacuación de atractivos turísticos
    p.mb-5(data-aos='fade-right') A nivel internacional se han definido normas para la prestación de servicios turísticos de alta calidad, por lo que Colombia al pretender hacer de este sector uno de talla mundial que le permita mayor visibilización  en el exterior y por ende mayores divisas, ha venido diseñando un plan de emergencias y otro de evacuación que le permita satisfacer las exigencias del turista, que es el cliente final.
    .rounded-pill.d-inline-block.p-2(style='background-color: #b7ceac').mb-5
      h4.px-3.mb-0.me-5 Planes de emergencia
    p.mb-5(data-aos='fade-right') Tienen como objetivo proporcionar el conocimiento y los recursos físicos que permitan responder de manera eficiente a la situación de emergencia, disminuyendo el impacto por las amenazas internas y externas, para aclarar el tema se invita a revisar el siguiente recurso de aprendizaje donde encontrará algunos elementos clave al momento de construir uno para el sector turístico:
      br
      br
      | ¿Qué se debe tener en cuenta para el diseño de un plan de emergencia?
    SlyderF.slyder-100.mb-5(columnas="col-lg-4 col-xl-4")
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/13.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Detectar y valorar amenazas que causan emergencias dentro y fuera de un atractivo turístico.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/14.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Determinar el grado de riesgo y vulnerabilidad derivados de las amenazas.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/15.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Establecer medidas preventivas y de protección para los escenarios de riesgos que se han identificado.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/16.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Organizar los recursos que un atractivo turístico tiene, tanto humanos como físicos, para hacer frente a cualquier tipo de emergencia.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/17.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Brindar las herramientas cognitivas y conductuales necesarias, que permitan ejecutar los planes de acción de manera segura para las personas expuestas a peligros.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/18.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Preservar los bienes y activos del atractivo turístico, de los daños que se puedan presentar como consecuencia de las emergencias.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/19.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Garantizar la continuidad de las actividades y servicios.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/20.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Garantizar una mejor respuesta ante las emergencias que se generen.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/21.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Disponer de un esquema de activación con una estructura organizacional ajustada a las necesidades de respuesta de las emergencias.
    .rounded-pill.d-inline-block.p-2(style='background-color: #b7ceac').mb-5
      h4.px-3.mb-0.me-5 Evacuación de atractivos turísticos
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/22.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Un plan de evacuación hace referencia a todas las acciones a realizar para detectar e identificar los peligros y la valoración de los riesgos originados del peligro que puedan amenazar la integridad de los turistas y demás asistentes a las instalaciones del atractivo, para posteriormente comunicar de manera adecuada y oportuna la decisión de abandonar el espacio, facilitando de manera rápida el traslado por rutas confiables a un lugar o punto de encuentro que previamente se haya calificado como seguro.
    p.mb-5(data-aos='fade-right') Las acciones que conforman un plan de evacuación deben estar plasmadas en un documento en el que se detalla el paso a paso a seguir, los roles que deben asumir cada una de las personas bajo la dirección de un coordinador de evacuación (FOPAE, 2014).
      br
      br
      |Por tal razón, se deben tener en cuenta los siguientes elementos al diseñar un plan de evacuación definiendo qué hacer en cada fase, por lo que se motiva a revisar el siguiente recurso de aprendizaje:
    SlyderF.slyder-100.mb-5(columnas="col-lg-4 col-xl-4")
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/23.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Procedimientos antes, durante y después de la evacuación.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/24.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Plano de planta de la edificación señalando ruta de evacuación, salidas al exterior, puntos de encuentro externos.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/25.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Deben estar señalizados hidrantes, equipos contra incendios, alarmas y sus pulsadores, equipos de comunicación.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/26.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Actividades de entrenamiento con fechas de simulacros o simulaciones y la periodicidad de estos.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/27.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Actualización de actividades, considerando modificaciones estructurales, suministros, recursos capacidad de carga entre otras variables.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/28.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p Capacitación a los actores en manejo de multitudes, plan de emergencia, en procedimientos de evacuación (Antes, durante y después), primer respondiente y primeros auxilios.
      .tarjeta-avatar
        img(src='@/assets/curso/temas/tema4/29.svg' alt='AvatarTop')
        .tarjeta.w-100.h-100(style='background-color: #ffd667')
          .p-4
            p El plan de evacuación debe considerar y valorar los peligros y los riesgos externos.
    Separador
    #t_4_4.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 4.4 Responsabilidad civil del guía
    p.mb-5(data-aos='fade-right') De acuerdo con la legislación colombiana para analizar las responsabilidades civiles del guía turístico es necesario mencionar varias normatividades, ya que en el país esta actividad se ha convertido en una profesión que se ha cualificando, por lo que el Estado mediante el Ministerio de Educación con el apoyo de diferentes instituciones de educación superior, entre ellas el SENA han desarrollado programas en esta área, con el fin de formar colombianos que adquieran las competencias para cumplir con el perfil que se requiere.
      br
      br
      |En los siguientes documentos podrá encontrar información que le permitirá ampliar sus conocimientos sobre las funciones y responsabilidades del guía.
    .row.justify-content-center.mb-5
      .col-lg-10
        .tarjeta.color-primario.p-4
          //todo! Añadir documento ----------------------------------------------------------------------------------------------
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
                img(src="@/assets/curso/temas/tema1/40.svg")
            .col-9
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Ley 1558 de 2012
                .col-sm-auto
                  .d-block.mb-4
                    a.boton.color-acento-botones.texto-blanco(href="https://tinyurl.com/y9zkb43d" target="_blank")
                      span Ver documento
                      i.fas.fa-file
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Decreto 1379 de 2021
                .col-sm-auto
                  .d-block.mb-4
                    a.boton.color-acento-botones.texto-blanco(href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=172994" target="_blank")
                      span Ver documento
                      i.fas.fa-file
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Guías de turismo de Colombia. Normatividad
                .col-sm-auto
                  .d-block.mb-4
                    a.boton.color-acento-botones.texto-blanco(href="https://www.mincit.gov.co/minturismo/normatividad-turismo" target="_blank")
                      span Ver documento
                      i.fas.fa-file
    p.mb-5(data-aos='fade-right') Igualmente, en la normativa se destacan las responsabilidades del guía, las cuales se podrán conocer en el siguiente recurso de aprendizaje:
    h3 Responsabilidades civiles del guía 
    .row.justify-content-center.mb-5
      .col-lg-7.mb-lg-0.mb-3
        .tarjeta(style='background-color: #ffe6a1').p-5.bullets-down 
          SlyderA.px-3
            div
              .row.mb-3.align-items-center.justify-content-center
                .col-2
                  figure
                    img(src='@/assets/curso/temas/tema4/30.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Prestar sus servicios en los términos ofrecidos y pactados con el turista o con la empresa que lo contrate, según corresponda.
              .row.mb-3.align-items-center.justify-content-center
                .col-2
                  figure
                    img(src='@/assets/curso/temas/tema4/31.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Prestar sus servicios dando cumplimiento a las políticas del sector turismo y a las normas tributarias y de seguridad social.
              .row.mb-3.align-items-center.justify-content-center
                .col-2
                  figure
                    img(src='@/assets/curso/temas/tema4/32.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Respetar la identidad y diversidad cultural de las comunidades encontradas en las zonas donde se preste el servicio, evitando que los visitantes a su cargo o bajo su orientación causen algún daño o irrespeten las etnias que se encuentren en el territorio. Informar previamente a los usuarios o a las empresas que lo contraten.
            div
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/33.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Prestar el servicio en el idioma en el que sea requerido.
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/34.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Respetar las tarifas, expresando el costo total de los servicios, incluyendo cualquier tipo de tasa, cargo, sobrecargo o tarifa que afecte el precio final. 
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/35.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Informar previamente al turista, viajero o pasajero las condiciones generales del lugar objeto de la visita, los riesgos, el equipamiento que conviene utilizar, así como la conveniencia de ser amparados por pólizas de seguros de accidente.
            div
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/36.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Observar los más altos niveles de calidad, oportunidad y eficiencia.
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/37.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Abstenerse de exigir propinas.
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/38.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Cumplir con las normas de protección del patrimonio cultural de la nación y de preservación del ambiente, evitando que los visitantes a su cargo o bajo su orientación colecten especies animales, vegetales o minerales, o extraigan, dañen o lesionen cualquier objeto de significación cultural o valor económico.
            div
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/39.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Cumplir con las disposiciones legales y reglamentarias en materia de prevención de la Explotación Sexual Comercial de Niños, Niñas y Adolescentes (ESCNNA).
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/40.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Mantener actualizada la información solicitada por el Ministerio de Comercio, Industria y Turismo a través de los canales que disponga el Ministerio para la inscripción o actualización de la tarjeta profesional de guía de turismo.
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/41.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Mantener vigente y actualizada su inscripción en el Registro Nacional de Turismo.
            div
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/42.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Incluir en toda su publicidad el número que corresponde al Registro Nacional de Turismo.
              .row.mb-3.align-items-center.justify-content-center
                .col-md-2.mb-4.mb-md-0.col-3
                  figure
                    img(src='@/assets/curso/temas/tema4/43.svg', alt='Texto que describa la imagen' style='width: 55px')
                .col-10
                  p.mb-0 Las demás obligaciones establecidas en materia de publicidad para los prestadores de servicios turísticos. 
      .col-lg-5: img(src='@/assets/curso/temas/tema4/44.jpg', alt='')
    p #[sup 1] La norma menciona un plan de acción para efectos del guionaje turístico, es un plan de contingencia.



























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

<style lang="sass">
.bloque-derecha
  .bloque-texto-g__img
    left: auto
    right: 0
  .bloque-texto-g
    justify-content: flex-start

.bullets-down
  .slyder-a__tipo-a .slyder-a__bullets
    bottom: -80px !important
  .slyder-a__tipo-a .slyder-a__btn--sigt
    right: -30px !important
  .slyder-a__tipo-a .slyder-a__btn--atrs
    left: -40px !important
  .slyder-a__tipo-a .slyder-a__bullets
    bottom: -20px !important
</style>
