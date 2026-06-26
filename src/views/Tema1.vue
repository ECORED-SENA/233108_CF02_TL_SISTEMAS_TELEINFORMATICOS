<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span 1
        h1 Seguridad informática en la organización
      p(data-aos="fade-right") Los problemas de seguridad cibernética son cada vez más problemáticos para las empresas de todos los tamaños, el delito cibernético aumentó en un 600 % durante la pandemia de COVID-19 y los costos del delito cibernético están aumentando a un ritmo alarmante. La implementación de un programa eficaz de gestión de riesgos es un componente esencial de la defensa contra los ataques cibernéticos y una prioridad para los directores de seguridad de la información y las organizaciones en general.
      .row.align-items-center.mb-3
        .col-lg-4.mb-3.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img1.png', style="width: 370px", alt='').m-auto
        .col-lg-8(data-aos="fade-left")
          .row.align-items-center.mb-3
            .col-auto
              figure
                img(src='@/assets/curso/temas/t1/img1.svg', style="width: 30px", alt='').m-auto
            .col
              p.mb-0 La gestión de riesgos de seguridad cibernética es el proceso de identificar, analizar y abordar los riesgos de seguridad de TI de una organización para prevenir futuros ataques cibernéticos y dar cuenta de las amenazas cibernéticas en curso.
          .cajon.color-acento-botones.p-4.mb-3
            p.mb-0 Para prevenir el delito cibernético, los profesionales de TI deben desarrollar un marco sólido de seguridad cibernética que se adhiera estrictamente a las pautas, los estándares y las mejores prácticas relevantes. Mantener un programa eficaz de gestión de riesgos de ciberseguridad es complejo pero esencial.
          p.mb-0 Examinar los riesgos y su impacto potencial permite a las organizaciones crear objetivos estratégicos y disminuir el riesgo de ciberamenazas. Cuando un marco de gestión de riesgos se implementa correctamente, permite a las organizaciones comprender mejor la gama completa de riesgos a los que se enfrentan.
      p.mb-0 Cuanto mayor sea el conocimiento de una organización sobre estos riesgos, mejor podrá implementar medidas proactivas.
      Separador
      #t_1_1
      .titulo-segundo.color-acento-botones
        h2 1.1 Privilegios de acceso y seguridad de la información
      .bloque-texto-a.color-primario.p-4.p-md-5.mb-5(data-aos="fade-down")
        .row.m-0.align-items-center.justify-content-between
          .col-lg-8
            .bloque-texto-a__texto.p-4.mb-4.mb-lg-0
              p Los controles de acceso autentican y autorizan a las personas a acceder a la información que pueden ver y usar. El uso indebido de privilegios es una de las principales amenazas de seguridad cibernética en la actualidad, que a menudo resulta en pérdidas costosas e incluso puede paralizar las empresas. También es uno de los vectores de ataque más populares entre los piratas informáticos, porque cuando se lleva a cabo con éxito, brinda acceso gratuito a la parte más vulnerable de una empresa, a menudo sin generar ninguna alarma hasta que el daño ya está hecho. Existen <i>softwares</i> que empoderan a las empresas que buscan adelantarse a este riesgo creciente con un sólido programa de administración de acceso privilegiado que garantice que ninguna vía de acceso privilegiado a los activos de misión crítica quede sin administrar, sin conocer o sin monitorear. De ahí que todo proceso parta de las siguientes preguntas base:
          .col-lg-4
            figure
              img(src='@/assets/curso/temas/t1/img2.svg', style="width: 340px", alt='').m-auto
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-10          
          .titulo-sexto.color-acento-botones.mb-4(data-aos="fade-right")
            p.mb-0 #[b Figura 1]. Preguntas sobre la seguridad de la información  
      figure.mb-5(data-aos="fade-right")
        img(src='@/assets/curso/temas/t1/img3.svg', style="width: 1080px", alt='Figura que menciona las preguntas a tener en cuenta al momento de desear proteger la información.').m-auto
      .row.align-items-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img2.png', style="width: 380px", alt='').m-auto
        .col-lg-8(data-aos="fade-left")
          .cajon.color-acento-botones.p-4.mb-3
            p.mb-0 #[b Lo que sigue es una guía de los conceptos básicos del control de acceso]: qué es, por qué es importante, qué organizaciones lo necesitan más y los desafíos que pueden enfrentar los profesionales de la seguridad.
          .row.align-items-center.mb-3
            .col-auto
              figure
                img(src='@/assets/curso/temas/t1/img1.svg', style="width: 30px", alt='').m-auto
            .col
              p.mb-0 El control de acceso es un método para garantizar que los usuarios son quienes dicen ser y que tienen el acceso adecuado a los datos de la empresa. A un alto nivel, el control de acceso es una restricción selectiva del acceso a los datos. Consta de dos componentes principales: autenticación y autorización.
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-6
          TarjetaAudio.color-primario.mb-3(
            texto="Control de acceso"
            :audio="audio1"
            @audio-hover="mostrarIndicadorTarjetaAudio = false"
          )
            .indicador--click(v-if="mostrarIndicadorTarjetaAudio")
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-10          
          .titulo-sexto.color-acento-botones.mb-4(data-aos="fade-right")
            p.mb-0 #[b Figura 2]. Autenticación y autorización de datos 
      figure.mb-5(data-aos="fade-down")
        img(src='@/assets/curso/temas/t1/img4.svg', style="width: 1080px", alt='Infografía que representa el control de acceso que está compuesto por una autenticación y una autorización. El contenido de esta se relaciona debajo de la imagen.').m-auto
      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img3.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 Cualquier organización cuyos empleados se conecten a Internet (en otras palabras, todas las organizaciones de hoy) necesita cierto nivel de control de acceso. Eso es especialmente cierto en el caso de las empresas con empleados que trabajan fuera de la oficina y requieren acceso a los recursos y servicios de datos de la empresa.
      .row.bg-c1
        .col-12
          .p-5
            figure.mb-5(data-aos="fade-right")
              img(src='@/assets/curso/temas/t1/img6.svg', style="width: 1080px", alt='').m-auto
            .row.justify-content-center
              .col-lg-10.p-4.bg-c2.mb-5(data-aos="fade-right")
                p.text-center.mb-0 #[b Cualquier sistema de control de acceso, ya sea físico o lógico, tiene cinco componentes principales, descritos de esta manera:]
              .col-lg-6(data-aos="fade-left")
                ImagenInfografica.color-acento-botones
                  template(v-slot:imagen)
                    figure
                      img(src='@/assets/curso/temas/t1/img7.svg', alt='')
                  .tarjeta.color-secundario.p-3(x="79.1%" y="59%" numero="1")
                    p.text-white.text-white #[b Autenticación]
                    p.text-white.text-white.mb-0 El acto de probar una afirmación, como la identidad de una persona o usuario de una computadora. Puede implicar la validación de documentos de identidad personal, la verificación de la autenticidad de un sitio web con un certificado digital o la verificación de las credenciales de inicio de sesión con los detalles almacenados.
                  .tarjeta.color-secundario.p-3(x="13%" y="34%" numero="2")
                    p.text-white.text-white #[b Autorización]
                    p.text-white.text-white.mb-0 La función de especificar derechos de acceso o privilegios a los recursos. Por ejemplo, el personal de recursos humanos normalmente está autorizado para acceder a los registros de los empleados y esta política suele formalizarse como reglas de control de acceso en un sistema informático.
                  .tarjeta.color-secundario.p-3(x="95%" y="88%" numero="3")
                    p.text-white.text-white #[b Acceso]
                    p.text-white.text-white.mb-0 Una vez autenticado y autorizado, la persona o computadora puede acceder al recurso.
                  .tarjeta.color-secundario.p-3(x="21%" y="74%" numero="4")
                    p.text-white.text-white #[b Administrar]
                    p.text-white.text-white.mb-0 Administrar un sistema de control de acceso incluye agregar y eliminar la autenticación y autorización de usuarios o sistemas. Algunos sistemas se sincronizarán con G Suite o Azure Active Directory, lo que agilizará el proceso de administración.
                  .tarjeta.color-secundario.p-3(x="95%" y="30%" numero="5")
                    p.text-white.text-white #[b Auditoría]
                    p.text-white.text-white.mb-0 Se utiliza con frecuencia como parte del control de acceso para hacer cumplir el principio de privilegio mínimo. Con el tiempo, los usuarios pueden terminar con un acceso que ya no necesitan, por ejemplo, cuando cambian de rol. Las auditorías periódicas minimizan este riesgo.
      .row.align-items-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img4.png', style="width: 380px", alt='').m-auto
        .col-lg-8(data-aos="fade-left")
          .row.align-items-center.mb-3
            .col-auto
              figure
                img(src='@/assets/curso/temas/t1/img8.svg', style="width: 30px", alt='').m-auto
            .col
              p.mb-0 Otra razón para un fuerte control de acceso es la minería de acceso. La recopilación y venta de descriptores de acceso en la <i>Dark web</i> es un problema creciente.
          p.mb-0 Por ejemplo, nuevos informes en la web describen cómo una <i>botnet</i> de criptominería, Smominru, extrajo no solo criptomonedas, sino también información confidencial, incluidas en direcciones IP internas, información de dominio, nombres de usuario y contraseñas. Los investigadores de este tipo de delitos creen que es altamente plausible que este actor de amenazas vendiera esta información en un mercado de acceso a otros, que luego podrían lanzar sus propios ataques por acceso remoto.
      .row.justify-content-center.mb-5(data-aos="fade-down")
        .col-lg-10
          .row.align-items-center.justify-content-center
            .col-md-8.col-xl-7.bg-c3.p-4
              p.mb-0 Estos mercados de acceso proporcionan una forma rápida y fácil para que los ciberdelincuentes compren acceso a sistemas y organizaciones. Estos sistemas pueden usarse como <i>zombis</i> en ataques a gran escala o como punto de entrada para un ataque dirigido. Un mercado de acceso, Ultimate Anonymity Services (UAS) ofrece 35 000 credenciales con un precio de venta promedio de $6.75 por credencial, por citar ejemplo de precios de este tipo de accesos sin control.
            .col-xl-auto
              figure.fig-p1
                img(src='@/assets/curso/temas/t1/img10.svg', style="width: 50px", alt='').m-auto
            .col-xl-4 
              figure
                img(src='@/assets/curso/temas/t1/img9.svg', style="width: 380px", alt='').m-auto
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img5.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 Los investigadores de estos ciberataques creen que los ciberdelincuentes aumentarán el uso de los mercados de acceso y la minería de acceso porque pueden ser altamente lucrativos para ellos. El riesgo para una organización aumenta si sus credenciales de usuario comprometidas tienen más privilegios de los necesarios.
      .cajon.color-acento-botones.p-4.mb-5(data-aos="fade-left")
        p.mb-0 La mayoría de los profesionales de seguridad entienden cuán crítico es el control de acceso para su organización, pero no todos están de acuerdo en cómo se debe aplicar, debido a los múltiples factores, que se evidencian en el siguiente video:
      figure.mb-5(data-aos="fade-up")
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/EL2s26JfeBo" title="Factores de control" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      .row.bg-c5.mb-5
        .col-lg-6.bg-c4.shadow-sm.p-5.my-4(data-aos="fade-right")
          p.mb-0 Las organizaciones deben determinar el modelo de control de acceso apropiado a adoptar según el tipo y la sensibilidad de los datos que están procesando. Los modelos de acceso más antiguos incluyen control de acceso discrecional (DAC) y control de acceso obligatorio (MAC), el control de acceso basado en roles (RBAC) es el modelo más común en la actualidad, así como el modelo más reciente se conoce como control de acceso basado en atributos (ABAC). Al respecto:
      .row.align-items-center.justify-content-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img7.png', style="width: 340px", alt='Imágen decorativa').m-auto
        .col-10.col-md-8.col-lg-8(data-aos="fade-left")
          .row.align-items-center.bg-c6.mb-4
            .col-lg-auto.p-0
              figure
                img(src='@/assets/curso/temas/t1/img11.svg', style="width: 100px", alt='Imágen decorativa').m-auto
            .col-lg.p-4.p-lg-4
              p.mb-0 #[b Control de acceso discrecional (DAC)]: con los modelos DAC, el propietario de los datos decide el acceso. DAC es un medio para asignar derechos de acceso en función de las reglas que especifican los usuarios.
          .row.align-items-center.bg-c6.mb-4
            .col-lg-auto.p-0
              figure
                img(src='@/assets/curso/temas/t1/img12.svg', style="width: 100px", alt='Imágen decorativa').m-auto
            .col-lg.p-4.p-lg-4
              p.mb-0 #[b Control de acceso obligatorio (MAC)]: MAC se desarrolló utilizando un modelo no discrecional, en el que a las personas se les otorga acceso en función de una autorización de información. MAC es una política en la que los derechos de acceso se asignan con base en las regulaciones de una autoridad central.
          .row.align-items-center.bg-c6.mb-4
            .col-lg-auto.p-0
              figure
                img(src='@/assets/curso/temas/t1/img13.svg', style="width: 100px", alt='Imágen decorativa').m-auto
            .col-lg.p-4.p-lg-4
              p.mb-0 #[b Control de acceso basado en funciones (RBAC)]: RBAC otorga acceso en función de la función de un usuario e implementa principios de seguridad clave, como privilegio mínimo y separación de privilegios. Por lo tanto, alguien que intente acceder a la información solo puede acceder a los datos que se consideren necesarios para su función.
          .row.align-items-center.bg-c6
            .col-lg-auto.p-0
              figure
                img(src='@/assets/curso/temas/t1/img14.svg', style="width: 100px", alt='Imágen decorativa').m-auto
            .col-lg.p-4.p-lg-4
              p.mb-0 #[b Control de acceso basado en atributos (ABAC)]: en ABAC, a cada recurso y usuario se le asigna una serie de atributos, explica Wagner. En este método dinámico, se utiliza una evaluación comparativa de los atributos del usuario, incluida la hora del día, la posición y la ubicación, para tomar una decisión sobre el acceso a un recurso.
      .cajon.color-acento-botones.p-4.mb-5(data-aos="fade-right")
        p.mb-0 Es imperativo que las organizaciones decidan qué modelo es el más apropiado para ellas en función de la sensibilidad de los datos y los requisitos operativos para el acceso a los datos. En particular, las organizaciones que procesan información de identificación personal (PII) u otros tipos de información confidencial, incluida la Ley de Portabilidad y Responsabilidad de Seguros Médicos (HIPAA) o datos de Información no clasificada controlada (CUI), deben hacer del control de acceso una capacidad central en su arquitectura de seguridad, Wagner aconseja.
      .row.align-items-center.mb-5
        .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img8.png', style="width: 480px", alt='Imágen decorativa').m-auto
        .col-lg-7(data-aos="fade-left")
          p Varias tecnologías pueden admitir los diversos modelos de control de acceso. En algunos casos, es posible que varias tecnologías deban trabajar en conjunto para lograr el nivel deseado de control de acceso. La realidad de los datos distribuidos entre los proveedores de servicios en la nube, las aplicaciones y todos aquellos conectados al perímetro de la red tradicional dictan la necesidad de orquestar una solución segura. Existen varios proveedores que brindan acceso privilegiado y soluciones de administración de identidades que se pueden integrar en una construcción tradicional de Active Directory. La autenticación multifactorial puede ser un componente para mejorar aún más la seguridad.
          p.mb-0 Hoy en día, la mayoría de las organizaciones se han vuelto expertas en autenticación, especialmente con el uso creciente de la autenticación multifactorial y la autenticación basada en biometría (como el reconocimiento facial o del iris). En los últimos años, dado que las violaciones de datos de alto perfil han resultado en la venta de credenciales de contraseñas robadas en la web oscura, los profesionales de la seguridad se han tomado más en serio la necesidad de la autenticación de múltiples factores (aunque a menudo, sigue siendo un área en la que los profesionales de la seguridad se equivocan).
      .cajon.color-primario.p-4.mb-4(data-aos="fade-down")
        p.mb-0 Puede ser un desafío determinar y monitorear permanentemente quién obtiene acceso a qué recursos de datos, cómo deberían poder acceder a ellos y bajo qué condiciones se les otorga acceso, para empezar. Pero los protocolos de autorización inconsistentes o débiles pueden crear agujeros de seguridad que deben identificarse y taparse lo más rápido posible.
      .row.bg-c1
        .col-12
          .px-5.pt-5
            figure(data-aos="fade-right")
              img(src='@/assets/curso/temas/t1/img9.png', style="width: 1200px", alt='Imágen decorativa').m-auto
            .row.justify-content-center(data-aos="fade-down")
              .col-lg-10.bg-c7.shadow-sm.p-4
                p.mb-0 Así mismo, independientemente de cómo se defina implementar un control de acceso, este debe ser monitoreado constantemente, tanto en términos de cumplimiento de su política de seguridad corporativa como operativamente, para identificar posibles agujeros de seguridad. Se debe realizar, entonces, periódicamente una revisión de la gobernanza, el riesgo y el cumplimiento. Se necesitan escaneos de vulnerabilidad recurrentes contra cualquier aplicación que ejecute sus funciones de control de acceso y que recopile y monitoree registros en cada acceso para detectar violaciones de la política.
            .cajon.color-acento-botones.p-4(data-aos="fade-left")
              p.mb-0 En los complejos entornos de TI de la actualidad, el control de acceso debe considerarse como una infraestructura tecnológica viva que utiliza las herramientas más sofisticadas, refleja los cambios en el entorno de trabajo, como una mayor movilidad, reconoce los cambios en los dispositivos que usamos y sus riesgos inherentes, y toma en cuenta el creciente movimiento hacia la nube.
      Separador
      #t_1_2
      .titulo-segundo.color-acento-botones
        h2 1.2 Monitoreo del almacenamiento de la información
      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img10.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 La gestión o monitoreo del almacenamiento de la información, también denominada gestión del almacenamiento de datos, implica el seguimiento y la optimización del componente central de los grandes datos que recopila y conserva información digital mediante computadoras y otros dispositivos. La gestión del almacenamiento de datos se refiere al proceso de gestionar los datos de forma más eficaz. Requiere una comprensión adecuada de los dispositivos de almacenamiento y la disponibilidad de varios tipos de datos. La información digital puede incluir protocolos, documentos, preferencias de usuario, libretas de direcciones y más. Los tipos comunes de almacenamiento de datos son el almacenamiento de objetos, el almacenamiento de archivos, el almacenamiento definido por <i>software</i> y el almacenamiento de bloques. Cada uno de estos tipos de almacenamiento se utiliza para diferentes propósitos:
      .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="fade-left")
        SlyderA(tipo="b")
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento en la nube]
                  p.mb-0 El almacenamiento en la nube permite a las organizaciones almacenar datos en la nube, lo que facilita el acceso a los usuarios autorizados a través de Internet. Algunos de los almacenamientos en la nube más utilizados incluyen Google, Microsoft y más.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img11.png', style="width: 300px", alt='Imágen decorativa').m-auto
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento definido por #[i software]]
                  p.mb-0 El almacenamiento definido por <i>software</i> es un enfoque que se utiliza para administrar datos a través de la abstracción. Funciona extrayendo datos del almacenamiento físico organizado para uso en red. También funciona bien con contenedores y microservicios que incluyen datos no estructurados.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img12.png', style="width: 300px", alt='Imágen decorativa').m-auto
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento de archivos]
                  p.mb-0 El almacenamiento de archivos es uno de los enfoques de almacenamiento de datos más comunes utilizados por las organizaciones. Almacena datos en un formato jerárquico como una sola pieza de información. Esto ayuda a los usuarios a acceder a los datos mediante identificadores únicos o rutas, como nombres, ubicaciones y direcciones URL.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img13.png', style="width: 300px", alt='Imágen decorativa').m-auto
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.m1-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento en bloque]
                  p.mb-0 El almacenamiento en bloque divide el almacenamiento en bloques independientes. Cada bloque tiene su propia identidad única que garantiza la seguridad de los datos y brinda la libertad de colocar pequeños fragmentos de información de manera conveniente para una recuperación más rápida. Los bloques son comparativamente más rápidos e ideales para bases de datos de medios enriquecidos. También pueden proporcionar a los usuarios una completa autonomía de configuración.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img14.png', style="width: 300px", alt='Imágen decorativa').m-auto
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento de objetos]
                  p.mb-0 En el almacenamiento de objetos, los datos o archivos se dividen en piezas de información conocidas como objetos. Cada objeto es un repositorio autónomo con un identificador único. Esto ayuda a los usuarios a localizar y acceder a la información incluso en un sistema distribuido.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img15.png', style="width: 300px", alt='Imágen decorativa').m-auto
      .row.align-items-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img16.png', style="width: 350px", alt='Imágen decorativa').m-auto
        .col-lg-8(data-aos="fade-left")
          p La gestión del almacenamiento de datos implica la supervisión de activos de <i>software</i> y <i>hardware</i>, como matrices de almacenamiento, servidores físicos y servicios de almacenamiento en la nube. La gestión del almacenamiento de datos puede implicar la resolución de problemas de rendimiento, como posibles cuellos de botella, y el análisis de la capacidad de almacenamiento en tiempo real para ayudar a mejorar la experiencia del usuario final. Con esta información, los administradores pueden reasignar los recursos de almacenamiento para satisfacer las necesidades de almacenamiento empresarial. El monitoreo del almacenamiento de datos también puede incluir análisis de tráfico, automatización de procesos, gestión de memoria, virtualización de redes, replicación y aprovisionamiento de almacenamiento. Con el uso de un <i>software</i> confiable de administración de almacenamiento de datos, las organizaciones pueden configurar y rastrear más fácilmente el almacenamiento e informar las actividades de almacenamiento relacionadas.
          .cajon.color-acento-botones.p-4
            p.mb-0 Las funcionalidades comunes de la gestión del almacenamiento de datos incluyen:
      .row.justify-content-center.mb-5(data-aos="fade-down")
        .col-md-10.col-lg-4.bg-c11.p-5
          .row
            .col-12.bg-c9
              figure
                img(src='@/assets/curso/temas/t1/img16.svg', style="width: 180px", alt='Imágen decorativa').m-auto
          p #[b Rendimiento y confiabilidad]
          p.mb-0 El objetivo de la administración del almacenamiento de datos es administrar los datos para que estén disponibles para las operaciones comerciales. El acceso fácil y rápido a los datos aumenta el rendimiento, la eficiencia y la productividad de los empleados y mejora la experiencia del usuario final. Para agilizar el proceso, los equipos pueden usar medios y niveles automáticos para optimizar diferentes niveles de almacenamiento.
        .col-md-10.col-lg-4.bg-c10.p-5
          .row
            .col-12.bg-c9
              figure
                img(src='@/assets/curso/temas/t1/img17.svg', style="width: 180px", alt='Imágen decorativa').m-auto
          p.text-white #[b Seguridad y protección de datos]
          p.text-white.mb-0 Al utilizar el almacenamiento en la nube, es importante comprender la importancia de la protección de datos. Proteja los datos críticos para el negocio utilizando soluciones de copia de seguridad de datos, encriptación para datos almacenados y en tránsito, autenticación multifactorial para restringir el acceso no autorizado y más.
        .col-md-10.col-lg-4.bg-c12.p-5
          .row
            .col-12.bg-c9
              figure
                img(src='@/assets/curso/temas/t1/img18.svg', style="width: 160px", alt='Imágen decorativa').m-auto
          p #[b Control y cumplimiento]
          p.mb-0 Aproveche varios niveles de organización en niveles o automática para almacenar los activos de datos más valiosos. Esto ayuda a administrar y almacenar datos y ayuda a las organizaciones a demostrar el cumplimiento de las regulaciones.
      .row.justify-content-center.align-items-center.mb-5
        .col-4.col-lg-2
          .bg-1.p-4
            .row
              .col-9.col-lg-7
                figure(data-aos="fade-right")
                  img(src='@/assets/curso/temas/t1/img43.svg', alt='Imágen decorativa').img43-tm1
        .col-lg-9
          .bg-2.p-4
            .row
              .col-1
              .col-11
                b.mb-0(data-aos="fade-left") Ahora bien, frente a las herramientas para el monitoreo del almacenamiento de datos contribuyen en el apoyo de la asignación de recursos más fácilmente según sea necesario. Estas herramientas también pueden:
      .row.justify-content-center.align-items-center.mb-3
        .titulo-sexto.color-acento-botones.mb-4(data-aos="fade-right")
          p.mb-0 #[b Figura 3]. Herramientas para el monitoreo del almacenamiento
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/temas/t1/img20.svg', style="width: 1250px", alt='Infografía que relaciona las tareas de las herramientas y lo que estas pueden hacer. Los textos de dicha se encuentran debajo de la imagen.').m-auto
        p.mb-5 Cabe resaltar que existen software de administración de datos que están diseñados para ayudar a las organizaciones a monitorear la capacidad actual de almacenamiento de datos a través de un tablero centralizado, para que pueda optimizar más fácilmente las políticas de almacenamiento de datos, administrar el estado del entorno de almacenamiento y abordar aspectos clave del proceso de administración de datos. 
        .cajon.color-acento-botones.p-4(data-aos="fade-down")
          p.mb-0 Además, las herramientas de monitoreo de datos pueden proporcionar información crucial sobre el estado de los dispositivos de almacenamiento, el riesgo de capacidad y la detección de puntos de acceso para garantizar que se tomen las medidas correctas.
      Separador
      #t_1_3
      .titulo-segundo.color-acento-botones
        h2 1.3 Procesos de mejora para el tratamiento de la información
      .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img17.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 La protección de una organización contra los ataques cibernéticos a veces puede parecer un juego interminable de golpes de seguridad. Tan pronto como haya asegurado una debilidad, aparece otra. Esto puede desmoralizar a cualquier organización y hacerle creer que las buenas prácticas de seguridad de la información son imposibles. Sin embargo, hay una solución, pero requiere una forma diferente de pensar. Las organizaciones deben dejar de mirar cada amenaza individual a medida que surge y, en su lugar, construir defensas que estén equipadas para manejar cualquier cosa que los ciberdelincuentes les arrojen. Hacer eso es más simple de lo que parece. Esto se debe a que, por mucho que evolucionen las tácticas de los ciberdelincuentes, tienden a seguir la misma metodología básica. Si sus medidas de seguridad tienen en cuenta las formas en que se le ataca, en lugar de formas específicas de ataque, se defenderá de manera efectiva de una variedad de ataques.
      p.mb-5(data-aos="fade-right") Aprovechar cantidades masivas de datos brinda a las empresas una ventaja competitiva y las ayuda a comprender sus estrategias de ventas/<i>marketing</i> y las necesidades de los consumidores. Sin embargo, no se puede acceder a los datos sin someterse a un procesamiento de datos. Las empresas grandes y pequeñas necesitan comprender la importancia del procesamiento de datos.
      .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img29.png" style="max-width: 60px").m-auto
        .col
          h3 ¿Qué es el procesamiento de datos?
      .row.align.items-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img21.svg', style="width: 380px", alt='Imágen decorativa').m-auto
        .col-lg-8(data-aos="fade-left")
          p El procesamiento de datos ocurre cuando los datos se recopilan y transforman en información utilizable. Por lo general, es un proceso del que un científico de datos es responsable solo o en equipo, y es importante ejecutarlo correctamente para no afectar negativamente el resultado final (datos de salida). El procesamiento de datos primero transforma los datos en su forma original en formatos legibles (gráficos, documentos, etc.). Esto brinda a las computadoras el formato y el contexto que necesitan para interpretar los datos y aprovecharlos para los empleados de toda la organización.
          p.mb-0 Las etapas del procesamiento de datos son:
      .row.bg-c14.mb-5
        .col-12
          .p-5
            .row.justify-content-center
              .col-lg-10
                PasosA.color-primario(tipo="n")(data-aos="fade-down")
                  .row.align-items-center
                    .col-lg-8.mb-4.mb-lg-0
                      p #[b Recopilación de datos]
                      p.mb-0 La recopilación de datos es el primer paso en el procesamiento de datos. Los datos provienen de fuentes disponibles, como lagos de datos y almacenes de datos. Es importante que las fuentes de datos disponibles sean fidedignas y estén bien construidas. Esto asegura que los datos recopilados (y luego utilizados para la información) tengan la mejor calidad posible.
                    .col-lg-4
                      figure
                        img(src='@/assets/curso/temas/t1/img22.svg', style="width: 150px", alt='Imágen decorativa').m-auto
                  .row.align-items-center
                    .col-lg-4.mb-4.mb-lg-0
                      figure
                        img(src='@/assets/curso/temas/t1/img23.svg', style="width: 150px", alt='Imágen decorativa').m-auto
                    .col-lg-8
                      p.txt-p1 #[b Preparación de datos]
                      p.txt-p1.mb-0 Los datos recopilados entran en la etapa de preparación de datos. La preparación de datos, también conocida como “preprocesamiento”, es la etapa en la que se limpian y organizan los datos sin procesar. Esto hace que los datos estén disponibles para etapas posteriores del procesamiento de datos. Durante la preparación, los datos sin procesar se verifican minuciosamente en busca de errores. El propósito de este paso es eliminar datos incorrectos (datos redundantes, incompletos o inexactos) y crear datos de alta calidad para una mejor inteligencia comercial.
                  .row.align-items-center
                    .col-lg-8.mb-4.mb-lg-0
                      p #[b Entrada de datos]
                      p.mb-0 Los datos limpios se introducen en su objetivo (un CRM como Salesforce o un almacén de datos como Redshift) y se interpretan en un lenguaje que pueda procesar. La entrada de datos es la primera etapa en la que los datos sin procesar toman la forma de información utilizable.
                    .col-lg-4
                      figure
                        img(src='@/assets/curso/temas/t1/img24.svg', style="width: 150px", alt='Imágen decorativa').m-auto
                  .row.align-items-center
                    .col-lg-4.mb-4.mb-lg-0
                      figure
                        img(src='@/assets/curso/temas/t1/img25.svg', style="width: 150px", alt='Imágen decorativa').m-auto
                    .col-lg-8
                      p.txt-p1 #[b Procesamiento]
                      p.txt-p1.mb-0 En esta etapa, los datos ingresados en la computadora desde la etapa anterior se procesan para su interpretación. El procesamiento se realiza mediante algoritmos de aprendizaje automático, pero el proceso en sí depende de la fuente de los datos que se procesan (lagos de datos, redes sociales, dispositivos conectados, etc.) y su uso previsto (estudio de patrones publicitarios, diagnósticos médicos de dispositivos conectados, Puede diferir ligeramente según la evaluación de las necesidades del cliente, etc.).
                  .row.align-items-center
                    .col-lg-8.mb-4.mb-lg-0
                      p #[b Salida/interpretación de datos]
                      p.mb-0 Salida/Interpretación es la etapa en la que los datos finalmente se ponen a disposición de los que no son científicos de datos. Los datos se interpretan y se hacen legibles, a menudo en forma de gráficos, videos, imágenes, texto sin formato, etc. Los miembros de la organización podrán autoservicio de datos para sus propios proyectos de análisis de datos.
                    .col-lg-4
                      figure
                        img(src='@/assets/curso/temas/t1/img26.svg', style="width: 150px", alt='Imágen decorativa').m-auto
                  .row.align-items-center
                    .col-lg-4.mb-4.mb-lg-0
                      figure
                        img(src='@/assets/curso/temas/t1/img27.svg', style="width: 150px", alt='Imágen decorativa').m-auto
                    .col-lg-8
                      p.txt-p1 #[b Almacenamiento de datos]
                      p.txt-p1.mb-0 La etapa final del procesamiento de datos es el almacenamiento. Todos los datos procesados se almacenan para uso futuro. Parte de la información se puede usar inmediatamente, pero la mayoría se usará más tarde. Además, se requiere que los datos almacenados correctamente cumplan con las leyes de protección de datos como GDPR. Cuando los datos se almacenan correctamente, los miembros de su organización pueden acceder a ellos rápida y fácilmente según sea necesario.
      .row.justify-content-center.mb-5(data-aos="fade-left")
        .col-lg-10
          .row.align-items-center.justify-content-center
            .col-xl-4 
              figure
                img(src='@/assets/curso/temas/t1/img29.svg', style="width: 380px", alt='Imágen decorativa').m-auto
            .col-xl-auto
              figure.fig-p2
                img(src='@/assets/curso/temas/t1/img28.svg', style="width: 50px", alt='Imágen decorativa').m-auto
            .col-md-8.col-xl-7.bg-c3.p-4
              p.mb-0 La nube jugará un papel clave en el futuro del procesamiento de datos. La tecnología de la nube se basa en las prácticas actuales de procesamiento electrónico de datos para aprovechar esa conveniencia y mejorar la velocidad y la eficiencia. Con velocidades más rápidas y datos de mayor calidad, puede aprovechar más datos y extraer información más valiosa. A medida que los grandes datos se trasladan a la nube, las empresas obtienen importantes beneficios. La tecnología de nube de <i>big data</i> permite a las empresas combinar todas las plataformas en un sistema fácilmente adaptable. A medida que el <i>software</i> cambia y se actualiza (como es común en el mundo de los grandes datos), la tecnología de la nube integra a la perfección elementos antiguos y nuevos.
      .row.align-items-center.mb-3
        .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
          .cajon.color-acento-botones.p-4.mb-3
            p.mb-0 Las grandes empresas no son las únicas que se benefician del procesamiento de datos en la nube. De hecho, las pequeñas y medianas empresas también pueden beneficiarse enormemente entre sí. La plataforma en la nube se puede utilizar a bajo costo y se puede expandir/extender de manera flexible de acuerdo con el crecimiento de la empresa. Esto permite a las empresas ganar escalabilidad sin incurrir en costos significativos.
          p.mb-0 Sumado a esto, se pasa del procesamiento de datos a la analítica. El <i>big data</i> está cambiando la forma en que se hacen negocios, y las empresas de todos los tamaños necesitan estrategias sólidas de procesamiento de datos para obtener una ventaja competitiva. Los seis pasos del procesamiento de datos seguirán siendo los mismos, pero la nube hará avanzar mucho la tecnología, convirtiéndola en el método más económico, moderno y rápido. Una vez que se completa el procesamiento de datos, luego de su recopilación, lo que se espera es la utilización real de los mismos por medio de su análisis; de esta forma, se puede tomar decisiones comerciales más rápidas e inteligentes.
        .col-lg-4(data-aos="fade-left")
          figure
            img(src='@/assets/curso/temas/t1/img18.png', style="width: 340px", alt='Imágen decorativa').m-auto
      p.mb-5(data-aos="fade-right") A medida que las fuentes de datos se expanden y diversifican, el procesamiento de datos debe enfrentar varios desafíos nuevos. El <i>hardware</i> Intel® está reforzado para un procesamiento de datos rápido y rentable y se puede escalar para cumplir con las cargas de trabajo más exigentes.
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img19.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 No existe un enfoque único para el procesamiento de datos; pues diferentes tipos de cargas de trabajo y aplicaciones requieren distintos enfoques para aumentar su rendimiento y rentabilidad. Los métodos de procesamiento de datos son los siguientes:
      .row.justify-content-center.mb-5(data-aos="fade-down")
        .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src="@/assets/curso/temas/t1/img20.png", alt="alt")
            .crd_hover_txt--body
              p.text-center #[b El procesamiento por lotes]
              p.mb-0 El procesamiento por lotes es la clasificación de datos en grupos o lotes, que se procesan a medida que los recursos están disponibles. Durante el procesamiento por lotes, los lotes de datos se procesan en serie uno tras otro. El procesamiento por lotes puede manejar grandes cantidades de datos de manera eficiente, pero generalmente es más adecuado para los datos que no necesitan ser usados de inmediato.
        .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src="@/assets/curso/temas/t1/img21.png", alt="alt")
            .crd_hover_txt--body1
              p.text-center #[b Procesamiento de flujo]
              p.mb-0 El procesamiento de flujo se realiza durante el procesamiento continuo de datos a medida que ingresan en la canalización de datos. Este tipo de procesamiento es mucho más rápido que el procesamiento por lotes, debido a que el análisis se da en pequeñas cantidades de datos. Por lo general, se usa para procesar datos que requieren una ejecución rápida.
        .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
          .crd_hover_txt
            .crd_hover_txt--img
              figure
                img(src="@/assets/curso/temas/t1/img22.png", alt="alt")
            .crd_hover_txt--body
              p.text-center #[b Procesamiento de datos distribuido]
              p.mb-0 A medida que la tecnología de red ha evolucionado, las tareas de procesamiento de datos ya no necesitan completarse dentro del mismo nodo. En el procesamiento de datos distribuidos, varios nodos que se ejecutan en el mismo <i>clúster</i> funcionan en paralelo para procesar cargas de trabajo de datos en una red. El uso del procesamiento de datos distribuido permite que las cargas de trabajo de análisis avanzado se procesen en <i>hardware</i> de bajo costo y bajo consumo.
      .row.align-items-center.mb-5
        .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
          .cajon.color-acento-contenido.p-4.mb-3
            p.mb-0 Según el tipo de datos que se procesen y su uso, varias de estas operaciones estratégicas se pueden realizar en una sola canalización de datos, lo que da como resultado una salida de datos final unificada.
          p.mb-0 El procesamiento de datos, uno de los procesos con mayor uso de recursos en una canalización de datos, está fuertemente influenciado por las optimizaciones de <i>hardware</i> y <i>software</i>. Muchos de los principales proveedores de <i>software</i> hoy en día optimizan sus productos para el <i>hardware</i> Intel®. Así mismo, el ecosistema Intel® de soluciones y socios tecnológicos garantiza que muchas soluciones de <i>software</i> se ejecuten de manera óptima en el <i>hardware</i> Intel®, lo que lo ayuda a aprovechar al máximo su inversión en tecnología. Intel, entonces, ofrece la siguiente amplia cartera de tecnologías de <i>hardware</i> y <i>software</i> para acelerar las cargas de trabajo de procesamiento de datos actuales:
        .col-lg-5(data-aos="fade-down")
          figure
            img(src='@/assets/curso/temas/t1/img23.png', style="width: 450px", alt='Imágen decorativa').m-auto
      .row.align-items-center.mb-5
        .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img30.svg', style="width: 450px", alt='Imágen decorativa').m-auto
        .col-lg-9(data-aos="fade-left")
          TabsA.color-primario
            .tarjeta.color-acento-contenido.p-4(titulo="Procesadores Intel®<br>Xeon")
              p.mb-0 Los procesadores Intel® Xeon ofrecen la flexibilidad para hacer frente a una amplia gama de cargas de trabajo de diversas fuentes, con procesadores Intel® optimizados para tareas como la normalización de datos y la reducción de ruido para el procesamiento de IA.
            .tarjeta.color-acento-contenido.p-4(titulo="SSD Intel Optane")
              p.mb-0 Las SSD Intel® Optane están diseñadas para ofrecer estabilidad y están construidas para optimizar el almacenamiento y el rendimiento de la memoria caché de datos. Ayuda a acelerar la transmisión y el procesamiento de datos en tiempo real mientras mantiene una alta confiabilidad del sistema.
            .tarjeta.color-acento-contenido.p-4(titulo="Tecnologías de código<br>abierto")
              p.mb-0 Intel ofrece una amplia gama de bibliotecas y plataformas de código abierto que aceleran el procesamiento y el análisis de datos. Esto incluye Intel® oneAPI Toolkit, Intel® oneAPI Math Kernel Library (Intel® oneMKL), Intel® oneAPI Data Analytics Library (Intel® oneDAL) y más.
            .tarjeta.color-acento-contenido.p-4(titulo="Seguridad mejorada")
              p.mb-0 La tecnología Intel® QuickAssist (Intel® QAT) permite a los equipos de datos acelerar el rendimiento del cifrado y descifrado y mejorar la seguridad de las aplicaciones de procesamiento de datos.
      .cajon.color-acento-botones.p-4(data-aos="fade-down")
        p.mb-0 Las tecnologías Intel® están diseñadas para permitir que cada organización cree una flexibilidad única y canalizaciones de procesamiento de datos únicas para nuevas fuentes de datos y aplicaciones. La aceleración basada en <i>software</i> y <i>hardware</i> de Intel permite el procesamiento de datos a la velocidad y eficiencia requeridas por las aplicaciones de análisis más avanzadas de la actualidad.
      Separador
      #t_1_4
      .titulo-segundo.color-acento-botones
        h2 1.4. Gestión de las copias de seguridad
      .row.align-items-center.mb-5
        .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img31.svg', style="width: 280px", alt='Imágen decorativa').m-auto
        .col-lg-9(data-aos="fade-left")
          p Para mantener la disponibilidad de los activos de información, dentro de una empresa u organización, es necesario contar con copias de seguridad adecuadas de la información que se posee. El personal de administración de la información debe operar una copia de seguridad que pueda restaurarse rápidamente con el menor impacto posible en el negocio, en caso de una falla de la computadora o de la red o un error de operación del sistema. Para garantizar que los usuarios de una empresa u organización puedan usar sus computadoras personales de manera segura, se deben recomendar copias de seguridad periódicas. En las computadoras cliente, no solo se deben respaldar los archivos de documentos creados con el <i>software</i> de procesamiento de texto y el <i>software</i> de hoja de cálculo, sino también los correos electrónicos, las URL de los sitios web de uso frecuente y varias configuraciones.
          .cajon.color-acento-contenido.p-4
            p.mb-0 Los diversos tipos de información que manejan las empresas deben ser estrictamente protegidos y una forma de protegerla es a través de una copia de seguridad de sus datos. La pérdida de estos dificulta las actividades comerciales. Por ello, es esencial que aquellos que están en condiciones de proteger la información corporativa comprendan los puntos relacionados con la copia de seguridad y su respectiva gestión.
      .row.justify-content-center.align-items-center.mb-5
        .col-4.col-lg-2
          .bg-3.p-4
            .row
              .col-9.col-lg-7
                figure(data-aos="fade-right")
                  img(src='@/assets/curso/temas/t1/img44.svg', alt='Imágen decorativa').img43-tm1
        .col-lg-9
          .bg-4.p-4
            .row
              .col-1
              .col-11
                b.mb-0.text-white(data-aos="fade-left") La gestión de copias de seguridad incluye la eliminación de copias de seguridad innecesarias y la realización de comprobaciones periódicas para garantizar que las copias de seguridad se puedan utilizar. Por ello, se debe tener en cuenta lo siguiente:
      .row.align-items-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img33.svg', style="width: 350px", alt='Imágen decorativa').m-auto
        .col-lg-8(data-aos="fade-left")
          .tarjeta.tarjeta--azul.p-4
            SlyderA(tipo="b")
              .row.justify-content-center.m-1
                .col-12.p-4.bg-c8
                  .row.align-items-center.justify-content-center
                    .col-12
                      p #[b Copias de seguridad]
                      p Las copias de seguridad registradas en el repositorio tienen uno de los siguientes valores de estado:
                      ul.lista-ul.mb-0
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 #[b Uso posible:] esto significa que las copias de seguridad registradas en el repositorio aún existen en disco o cinta.
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 #[b Venció:] esto significa que la copia de seguridad ya no existe en el disco o la cinta y todavía se incluye en el repositorio.
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 #[b Es imposible de usar:] esto significa que las copias de seguridad no se pueden usar temporalmente para las operaciones de recuperación de datos (por ejemplo, porque se almacenan fuera del sitio en cintas o en discos que no están montados actualmente).
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 #[b Innecesarias:] es posible que ya no se requieran copias de seguridad. Las copias de seguridad obsoletas son copias de seguridad que ya no se necesitan para satisfacer los propósitos de recuperación de datos, según la política de retención configurada actualmente.
              .row.justify-content-center.m-1
                .col-12.p-4.bg-c8
                  .row.align-items-center.justify-content-center
                    .col-12
                      p #[b Mantenimiento]
                      p Las tareas de mantenimiento que puede realizar son:
                      ul.lista-ul
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 Ver detalles de la copia de seguridad del repositorio: se realiza una verificación cruzada (si las copias de seguridad enumeradas en el repositorio existen, están disponibles y marque las copias de seguridad no disponibles como caducadas durante la verificación cruzada).
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 Eliminación de registros de copia de seguridad caducados del repositorio.
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 Eliminación de copias de seguridad obsoletas de repositorios y medios de copia de seguridad.
                        li.d-flex
                          i.lista-ul__vineta(style="color: #4ADBD1")
                          |
                          p.mb-0 Verificación de copia de seguridad para garantizar que se pueda utilizar y no esté dañada.
                      p.mb-0 Sin un registro preciso de las copias de seguridad disponibles, es posible que descubra que no existe una copia de seguridad completa de su base de datos cuando necesite realizar una recuperación. Las tareas como la verificación cruzada periódica de las copias de seguridad deben programarse regularmente como parte de su estrategia de copia de seguridad.
      .row.justify-content-center.mb-5(data-aos="fade-left")
        .col-lg-10
          .row.align-items-center.justify-content-center
            .col-md-8.col-xl-7.bg-c3.p-4
              p.mb-0 Cuando se utiliza el área de recuperación rápida para el almacenamiento de copias de seguridad, se eliminan o reducen muchas actividades de mantenimiento. Los archivos de respaldo y otros archivos se eliminan según sea necesario, mediante el mecanismo de administración de almacenamiento automático para cumplir con las demandas de almacenamiento de las operaciones en curso de la base de datos sin violar las políticas de retención. Sin embargo, debe monitorear el uso del espacio en el área de recuperación rápida para asegurarse de que sea lo suficientemente grande para almacenar copias de seguridad y otros archivos relacionados con la recuperación.
            .col-xl-auto
              figure.fig-p1
                img(src='@/assets/curso/temas/t1/img10.svg', style="width: 50px", alt='Imágen decorativa').m-auto
            .col-xl-4 
              figure
                img(src='@/assets/curso/temas/t1/img34.svg', style="width: 380px", alt='Imágen decorativa').m-auto
      .row.align-items-center.mb-5
        .col-lg-3.d-none.d-lg-block(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img35.svg', style="width: 380px", alt='Imágen decorativa').m-auto
        .col-lg-9(data-aos="fade-left")
          .cajon.color-primario.p-4.mb-3
            p.mb-0 El personal de gestión de la información es responsable de realizar copias de seguridad de los datos compartidos almacenados en servidores de bases de datos y servidores de archivos. Para realizar una copia de seguridad, se utiliza la utilidad de copia de seguridad proporcionada con el sistema operativo o el <i>software</i> de copia de seguridad dedicado; usualmente se realizan tarde en la noche o temprano en la mañana cuando los usuarios no están operando.
          p.mb-0 Los datos que los empleados y el personal almacenan en cada cliente también son uno de los activos de información importantes. Por lo tanto, los usuarios dentro de la organización también deben recibir instrucciones para realizar una copia de seguridad de la información almacenada en cada cliente. Al hacerlo, se comprende correctamente la importancia de los activos de información de cada usuario, como el destino de almacenamiento de la copia de seguridad (medios, servidor de copia de seguridad, etc.), el <i>software</i> y el método de copia de seguridad utilizados, la frecuencia de la copia de seguridad, etc. Se debe tener en cuenta que, si el usuario utiliza un medio de almacenamiento externo para la copia de seguridad, existe una gran posibilidad de que se filtre información confidencial o información personal debido a la eliminación de datos. Si se recomiendan medios de almacenamiento externo para la copia de seguridad, también es importante implementar minuciosamente reglas para la gestión de la información, como prohibir la eliminación innecesaria de datos y estipular ubicaciones de almacenamiento, en una política de seguridad de la información.
      .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t1/img24.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 Los datos que manejan las empresas incluyen datos como información de clientes, información relacionada con la contabilidad e información de socios comerciales. En el improbable caso de que estos datos se dañen o se pierdan, la empresa perderá credibilidad social y, además, existe la posibilidad de que se produzca una pérdida de clientes y se deteriore el rendimiento empresarial. La ocurrencia de pérdida económica por recibir una reclamación por daños también es un riesgo que no puede ser ignorado. Proteger sus datos con copias de seguridad es una forma eficaz de evitar la pérdida de datos.
      p.mb-5(data-aos="fade-right") Si ocurre una falla de datos y la información en poder de la empresa se vuelve ilegible, será difícil continuar con las actividades corporativas.
      .row.justify-content-center.mb-5(data-aos="fade-down")
        .col-lg-10
          .cajon.color-acento-contenido.p-4
            p.mb-0 Es necesario conocer la causa de la falla de los datos para poder realizar una copia de seguridad adecuada. A continuación, se presenta un vistazo a las principales causas de esta falla de datos:
      .row.bg-c14.mb-5
        .col-12
          .p-5
            ImagenInfografica.color-acento-botones(data-aos="fade-right")
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/t1/img36.svg', alt='Texto que describa la imagen')
              .tarjeta.color-secundario.p-3(x="21%" y="6%" numero="1")
                p.text-white.mb-0 Una cierta cantidad de error humano es inevitable porque son las personas, como los empleados, quienes realmente manejan los datos. Por ejemplo, el error de un empleado al operar una computadora personal puede hacer que los datos importantes se sobrescriban con otros datos o se eliminen. También es importante proporcionar una formación adecuada a los empleados para que no se produzcan errores operativos. Pero si sucede lo peor, puede restaurar con una copia de seguridad.
              .tarjeta.color-secundario.p-3(x="53%" y="8%" numero="2")
                p.text-white.mb-0 Las empresas están rodeadas de diversas amenazas. Uno de ellos es la existencia de piratas informáticos que atacan los datos corporativos e infectan con virus las redes de las empresas y los terminales individuales. No es exagerado decir que el riesgo de piratear datos corporativos aumenta cada día que pasa. Como empresa, debe ser plenamente consciente del riesgo de piratería y preparar un sistema de defensa.
              .tarjeta.color-secundario.p-3(x="89%" y="6%" numero="3")
                p.text-white.mb-0 Los obstáculos físicos, como fallas en discos duros o daños en los datos, representan una tercera causa de pérdida de datos. Aunque en algunos casos se pueden recuperar, a menudo estos problemas quedan sin resolver, dificultando la continuidad del negocio. Además, el robo de computadoras personales también implica una pérdida física de datos. Para prepararse ante estas situaciones, es crucial contar con copias de seguridad.
      p.mb-5(data-aos="fade-right") Existen tres métodos para hacer una copia de seguridad: guardar en un medio de almacenamiento externo, almacenamiento en línea y almacenamiento en red.
      .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="fade-left")
        SlyderA(tipo="b")
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento externo]
                  p.mb-0 En el primer método de copia de seguridad, que utiliza medios de almacenamiento externos, se utilizan CD, DVD, discos duros, o <i>pendrive</i> como medios de almacenamiento. Dependiendo de la capacidad de almacenamiento, se suele utilizar la memoria <i>flash</i>. La capacidad de los medios de copia de seguridad ha crecido considerablemente. Es necesario tener un medio de almacenamiento adecuado y hacer copias de seguridad regularmente para proteger los datos. Utilizar un dispositivo externo facilita este proceso.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img25.png', style="width: 300px", alt='Imágen decorativa').m-auto
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento en línea]
                  p.mb-0 El almacenamiento en línea se refiere al almacenamiento de datos en Internet. Es común hacer una copia de seguridad de los datos utilizando servicios en la nube. La ventaja del almacenamiento en línea es que puede almacenar grandes cantidades de datos. Otra característica del almacenamiento en línea es que, incluso en este caso, los datos en Internet pueden protegerse sin daños. También es efectivo almacenar datos importantes en una red confiable fuera de la empresa utilizando servicios en la nube.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img26.png', style="width: 300px", alt='Imágen decorativa').m-auto
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-6.mb-4.mb-lg-0
                  p #[b.txt-c1 Almacenamiento externo]
                  p.mb-0 El almacenamiento en red tiene una forma llamada NAS (Network Attached Storage) y debe entenderse que es un servidor de archivos dedicado. Hay muchos discos de gran capacidad, por lo que puede usarse sin preocuparse por el límite de capacidad de almacenamiento. Otra ventaja de utilizar el almacenamiento en red es que se pueden realizar copias de seguridad automáticas a altas horas de la noche o durante los días festivos mediante la configuración por adelantado.
                .col-lg-4
                  figure
                    img(src='@/assets/curso/temas/t1/img27.png', style="width: 300px", alt='Imágen decorativa').m-auto
      p.mb-5(data-aos="fade-right") Por otro lado, hay dos puntos a considerar al decidir cuál de los múltiples métodos de copia de seguridad de datos es mejor para una empresa. Uno es la cantidad de datos que desea respaldar y el otro es el costo.
      .row.bg-c14.mb-5
        .row.justify-content-center.align-items-center.mt-5
          .col-lg-10
            .titulo-sexto.color-acento-botones.mb-4(data-aos="fade-right")
              p.mb-0 #[b Figura 4]. Puntos a considerar en las copias de seguridad
        .col-12
          .p-5
            figure(data-aos="fade-up")
              img(src='@/assets/curso/temas/t1/img37.svg', style="width: 1100px", alt='Infografía que relaciona los dos puntos a considerar dentro de los métodos de copia de seguridad de datos, estos son  la cantidad de datos a respaldar y el presupuesto. Debajo de la imagen se  explica cada uno.').m-auto
      p.mb-5(data-aos="fade-right") De forma adicional, hay algunas notas a tener en cuenta al administrar las copias de seguridad de datos por parte, tanto de la persona a cargo como del gerente de la empresa:
      .row.align-items-center.mb-5
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure
            img(src='@/assets/curso/temas/t1/img38.svg', style="width: 350px", alt='Imágen decorativa').m-auto
        .col-lg-8(data-aos="fade-left")
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul1")
            .row(titulo="Aclarar el propósito de la copia de seguridad")
              .col-12
                p.mb-0.ms-5 Realizar copias de seguridad sin un propósito claro dificulta su eficiencia. Es importante definir el propósito, como proteger la credibilidad de la empresa frente a pérdidas de información. Una vez definido, se puede establecer el rango y la frecuencia adecuados de respaldo. También se puede reducir el tiempo de copia al eliminar datos innecesarios.
            .row(titulo="Tenga cuidado al manipular medios de almacenamiento externos")
              .col-12
                p.mb-0.ms-5 Al hacer copias de seguridad en medios externos como CD o memorias <i>flash</i>, es importante manejarlos con cuidado para evitar pérdidas. Después de respaldar los datos, guárdelos en una caja fuerte ignífuga para protegerlos de robos o incendios. Además, es necesario educar a los empleados sobre no sacar los medios de almacenamiento de la empresa.
            .row(titulo="Indique a los empleados que retrocedan")
              .col-12
                p.mb-0.ms-5 Es importante garantizar que cada empleado realice copias de seguridad adecuadas. Aunque el personal de TI puede respaldar la base de datos compartida, cada empleado debe respaldar sus propios datos en sus computadoras. Se deben proporcionar instrucciones precisas sobre el método y el destino de almacenamiento. Al hacer que los empleados asuman la responsabilidad de las copias de seguridad, se mejora el nivel de seguridad de la empresa en general.
            .row(titulo="La copia de seguridad puede tardar mucho tiempo")
              .col-12
                p.mb-0.ms-5 Si la cantidad de datos a respaldar es grande, llevará tiempo completar la copia de seguridad. Durante la copia de seguridad, es necesario restringir el acceso a dichos datos. Los tiempos de respaldo más prolongados pueden afectar negativamente las operaciones comerciales. Al realizar copias de seguridad de grandes cantidades de datos, es eficaz establecer copias de seguridad automáticas fuera del horario laboral, por la noche o en días festivos.
            .row(titulo="Preparar un sistema de gestión de datos de copia de seguridad")
              .col-12
                p.mb-0.ms-5 Además de realizar copias de seguridad periódicas, es crucial asegurarse de que los datos respaldados sean utilizables en caso de emergencia. Al restaurar los datos, es importante designar a un empleado responsable y tener un sistema de gestión efectivo. Sin embargo, es importante controlar el número de administradores para evitar confusiones sobre quién restauró los datos y cuándo. Construir un sistema adecuado de gestión es fundamental.
            .row(titulo="Gestione copias de seguridad periódicas de los datos de su empresa")
              .col-12
                p.mb-0 Es crucial gestionar correctamente los datos corporativos para proteger su confidencialidad y activos. Se debe realizar copias de seguridad de manera activa para salvaguardar la credibilidad de la empresa. Los datos y programas son activos valiosos, por lo que es necesario hacer copias de seguridad regularmente y administrarlos adecuadamente para evitar pérdidas en caso de daños o accidentes.
      p.mb-5(data-aos="fade-right") Ahora bien, también se debe contemplar las fallas y la recuperación de los datos que se puedan presentar, clasificándolos de la siguiente manera:
      .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="fade-left")
        SlyderA(tipo="b")
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-4.mb-4.mb-lg-0
                  figure
                    img(src='@/assets/curso/temas/t1/img39.svg', style="width: 300px", alt='Imágen decorativa').m-auto
                .col-lg-6
                  p #[b.txt-c1 Fallo de los datos en sí]
                  p.mb-0 La falla más común es la eliminación o sobrescritura de los datos necesarios debido a errores operativos por parte de administradores o usuarios. También puede ocurrir sobrescritura (manipulación) o eliminación debido a una infección de <i>malware</i>. Como contramedida, se hacen copias de los datos de varias generaciones y luego se guardan.
          .row.justify-content-center.m-1
            .col-11.bg-c8.p-4
              .row.align-items-center.justify-content-center
                .col-lg-4.mb-4.mb-lg-0
                  figure
                    img(src='@/assets/curso/temas/t1/img40.svg', style="width: 300px", alt='Imágen decorativa').m-auto
                .col-lg-6
                  p #[b.txt-c1 Obstáculos físicos]
                  p.mb-0 Es una falla del dispositivo (principalmente del disco duro) donde se almacenan los datos, e incluye fallas, daños (choque, terremoto o colisión, incendio, inundación) y robo del propio dispositivo. Como contramedida, los datos deben almacenarse en una ubicación diferente y en un medio diferente.
      p(data-aos="fade-right") A modo genérico se puede decir, entonces, que las operaciones de copia de seguridad se determinan teniendo en cuenta el uso y la importancia de los datos a replicar, así como el costo de recuperación en el improbable caso de falla.
      .cajon.color-acento-botones.p-4.mb-5(data-aos="fade-down")
        p.mb-0 Adicional a esto, para la gestión de la operación, es necesario determinar el tipo de medio de almacenamiento, frecuencia y método, período de almacenamiento y lugar de almacenamiento, entre otros:
      .row.bg-c15
        .col-12
          .p-5
            .row.justify-content-center
              .col-lg-6
                ImagenInfografica.color-acento-botones(data-aos="fade-right")
                  template(v-slot:imagen)
                    figure
                      img(src='@/assets/curso/temas/t1/img42.svg', alt='Texto que describa la imagen')
                  .tarjeta.color-secundario.p-3(x="94%" y="65%" numero="1")
                    p.text-white #[b Tipo de medio de almacenamiento]
                    p.text-white.mb-0 Se selecciona qué medio usar, como cinta, disco externo, CD/DVD, memoria <i>flash</i> (memoria USB), almacenamiento en red, etc. Es deseable considerar múltiples combinaciones también.
                  .tarjeta.color-secundario.p-3(x="41%" y="50%" numero="2")
                    p.text-white #[b Frecuencia (intervalo) y método]
                    p.text-white.mb-0 Intervalo de tiempo de copia de seguridad. Es necesario decidir si hacerlo todos los días, semanalmente, mensualmente, etc. Debe seleccionar si se desea utilizar Copia de seguridad completa, Copia de seguridad diferencial o Copia de seguridad incremental. Se puede lograr una copia de seguridad eficiente mediante el uso de múltiples métodos en combinación con intervalos.
                  .tarjeta.color-secundario.p-3(x="13%" y="74%" numero="3")
                    p.text-white #[b Periodo de almacenamiento]
                    p.text-white.mb-0 Es el período de almacenamiento de datos, que se ve afectado por la gestión de la frecuencia y la generación. Dependiendo del tipo de datos, como datos financieros, datos relacionados con aprobaciones y notificaciones, datos médicos y de seguros, etc., pueden existir períodos legales de conservación.
                  .tarjeta.color-secundario.p-3(x="60%" y="10%" numero="4")
                    p.text-white #[b Ubicación de almacenamiento]
                    p.text-white.mb-0 Dependiendo del propósito de uso, se selecciona el mismo lugar que el sistema, el mismo edificio, un edificio separado, el exterior de corta distancia, el exterior de larga distancia, etc. Las combinaciones de múltiples medidas y rotaciones son el método preferido. La selección y combinación de medios externos y medios de red también es un punto. Las redes externas también facilitan relativamente el uso de ubicaciones remotas.

</template>

<script>
import audio1 from '@/assets/componentes/audios/Cf2_Audio.mp3'
export default {
  name: 'Tema1',
  data: () => ({
    audio1,
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
