# PROYECTO FINAL

## Objetivos

Poner en práctica todos los contenidos del curso. Es decir:
- Construir una aplicación web, responsive que se pueda visualizar de forma correcta en cualquier dispositivo.
- La aplicación web debe implementar funcionalidades nativas de los dispositivos móviles.
- La aplicación debe poder compilarse como una aplicación nativa.
- La aplicación debe conectarse a una API pública para la obtención de datos.

## Requerimientos Generales

- Arranca mostrando un splash screen personalizado. 
- Contiene un crud del perfil de usuario (imagen incluida)
- Conecta a una API pública de información:
    - Obtiene un listado general y detalles en función de parámetros específicos
- Incorpora alguna utilidad del móvil: Geoposicionamiento, envío de mail, escáner, etc.
- Vistas de la aplicación:
    - Splash Screen
    - Login
    - Register
    - Perfil Usuario
    - Lista General
    - Detalle
    - Vista(s) Libres
  
## Requerimientos funcionales:

    - Usuarios únicos se relacionan con la información de la API (votar, favoritos,compartido, editada y almacenada, etc.)
    - La información relativa al usuario debe conservarse aunque la aplicación se cierre (no es necesario conservarla si la aplicación se desinstala)

## Requerimientos técnicos:

La navegación es fluida y no bloqueante. Se muestran spinners de carga (o carga progresiva) 
- Se estable navegación principal por pestañas o menú
- La navegación secundaria puede ser gestual (recomendada) o mediante interacción con elementos 

## Valoración

Se valorará la aplicación en los siguientes aspectos:
- Arquitectura de la aplicación, patrones de programación y código Limpio
- Estilos y animaciones
- Originalidad

### Temas

Los temas serán libres siempre que se ciñan a la estructura de aplicación propuesta.
Algunos ejemplos:

- Big Food: Escaneamos las etiquetas de los alimentos del super y obtenemos la composición nutricional y otros datos disponibles.
- Album fotográficos: Realizamos un álbum personalizado de imágenes de distintos proveedores (pixabay, unsplash, etc.). Marcamos como favoritas o clasificamos por temáticas.
- Smart Library: En tiempos de Covid. Consultamos los libros disponibles en la biblioteca. Arrastramos con el dedo a la cesta y seleccionamos día y hora que pasaremos a recogerlos. La app envía un mail a la biblioteca y ellos preparan el pedido y nos avisan de que está disponible.
- Weather Report: Conectamos a la API de weather.com y obtenemos temperaturas de todo el mundo. Guardamos histórico, realizamos itinerarios por distintos destinos, etc.
- Travelling Museums: Consultamos fondos de museos.

## Entrega

- Se tiene que entregar la siguiente documentación:
  - Documento proyecto
    - Tema elegido
    - Justificación
    - Miembro/miembros del equipo
  - Diseño y Navegación de la aplicación
  - Kanban de Historias de Usuario (se revisará diariamente)
  - Presentaciones diarias de avance.
  - Repositorio del código (se valorará que se despliegue con a algún sistema de CI)
  - URL del hosting utilizado (firebase, netlify, cdmon, otros)
  - apk de la aplicacion.