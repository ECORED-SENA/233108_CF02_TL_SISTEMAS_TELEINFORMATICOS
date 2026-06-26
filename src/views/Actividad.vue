<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      // Para cuestionario usar: <ActividadController :cuestionario="cuestionario"/>
      // Para parrafo usar: <ActividadController :parrafo="parrafo"/>
      #Actividad                
      <ActividadController :cuestionario="cuestionario"/>

</template>

<script>
import ActividadController from '@ecored-sena/boulder-kit/plugin/components/actividad/ActividadController.vue'

export default {
  name: 'ActividadDidactica',
  components: {
    ActividadController,
  },
  data: () => ({
    cuestionario: {
      tema: 'Ciberseguridad en las organizaciones',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo:</b> apropiar los conceptos más importantes asociados a los sistemas informáticos, de acuerdo a los procesos de ciberseguridad en las organizaciones.',
      barajarPreguntas: false,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto:
            'Aplicar una metodología de ciberseguridad en la organización permite:',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Pérdidas de tiempo productivo y altos costos de implementación.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Estandarizar, optimizar, minimizar el riesgo y generar confianza en sus clientes.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Utilizar documentos ya existentes para aplicarlos a la propia organización.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto:
                'Visibilizar que no es importante, la ciberseguridad es un tema menor.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto:
            'Lo sentimos, su respuesta no es la correcta. <em>Board</em> del <em>software</em> EAGLE.',
        },
        {
          id: 2,
          texto: 'Seleccione un  componente importante de controles de acceso.',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Manipulación.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Antivirus.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Autenticación.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'No hay componente importante.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: 'Las arquitecturas en la nube se caracterizan por:',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Red limitada, pocos recursos disponibles, difícil expansión.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Amplio acceso de red, elasticidad, crecimiento conforme se necesite, pago a la medida.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Pagos anticipado, redes MAN, durabilidad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Todas las opciones son correctas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            'Dentro de los tipos de monitoreo de información, cuál NO es correcto:',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Almacenamiento en la nube.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Almacenamiento definido por <em>software</em>.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Almacenamiento de archivos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Almacenamiento por instinto.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: 'Las etapas para la recolección de datos son:',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Recopilación y almacenamiento.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Recopilación, preparación, entrada, procesamiento, salida/interpretación y almacenamiento de datos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Almacenamiento.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Salida/interpretación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto: 'De las copias de seguridad podemos decir:',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'No son necesarias en las empresas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Sirven para restaurar la información y protegen  la información de la organización.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Se deben realizar cada semana.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: 'La información se puede salvaguardar en copias de seguridad:',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Local.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Local, externa y remota.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'En una memoria.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            'El inventario de activos de información es importante. ya que:',
          imagen: '@/assets/actividad/imagen4.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Se tiene conocimiento del total de equipos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Mantiene actualizada la información valiosa para la empresa.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Se pierde mucho tiempo realizando estas actividades.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: 'Se pude decir sobre el Antivirus que:',
          imagen: '@/assets/actividad/imagen1.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Sirve para autenticarse.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Protege contra amenazas informáticas.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Guardan la información de activos informáticos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            'De la siguiente lista se puede decir que una vulnerabilidad es un:',
          imagen: '@/assets/actividad/imagen2.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Virus informático.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Computador con acceso libre.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Ataque Informático.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto: 'El riesgo de incidentes informáticos aumentan cuando:',
          imagen: '@/assets/actividad/imagen3.png',
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La red es segura y controla los accesos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Los sistemas operativos se encuentran desactualizados y tienen acceso libre para cualquier usuario.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Existen políticas definida de ciberseguridad.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
