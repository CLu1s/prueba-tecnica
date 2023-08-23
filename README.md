# Buscador de bugs del repositorio de React en GitHub

## Objetivo:
Desarrollar una aplicación React que permita a los usuarios buscar y visualizar la lista de bugs del repositorio oficial de React en GitHub utilizando la API de GitHub.

### Requisitos:
1. Tiempo:
   - Tienes 24 horas apartir de que recibes esta prueba para mandar tu solución.

1. Interfaz:
   - Campo de búsqueda para que el usuario introduzca palabras clave.
   - Botón de búsqueda.
   - Lista que muestre los resultados.
   - Cada elemento de la lista debe mostrar al menos el título del bug, la descripción (si está disponible), la fecha en que fue creado y el usuario que lo creó.
   - Paginación: En caso de haber muchos resultados, implementa una paginación para navegar entre ellos.

2. Funcionalidad:
   - La aplicación debe consumir la API de GitHub para obtener la lista de bugs.
   - Los resultados deben filtrarse para mostrar solo los issues etiquetados como "bug".
   - La búsqueda debe activarse al hacer clic en el botón de búsqueda o al presionar "Enter".

3. Características Avanzadas (opcionales pero recomendadas):
   - Implementa un "debounce" en el campo de búsqueda para evitar múltiples llamadas a la API cuando el usuario esté escribiendo rápidamente.
   - Usa "lazy loading" o "infinite scroll" en lugar de paginación clásica.
   - Al hacer clic en un bug, muestra más detalles del mismo en una vista detallada.

### Aspectos a Evaluar:
  - Estructura del proyecto y organización del código.
   - Uso de componentes y su reutilización.
   - Manejo de estados y props.
   - Cómo se gestionan las llamadas a la API y el manejo de errores.
   - Responsividad y diseño de la interfaz (aunque no es el foco principal, es bueno tener en cuenta aspectos básicos de UX/UI).
   - Implementación de características avanzadas si el candidato decide hacerlo.

### Bonus (para candidatos que quieran demostrar habilidades extra):
   - Uso de TypeScript.
   - Implementación de tests usando Jest y React Testing Library.
   - Uso de un estado global como Redux o Context API.
   - Implementación de animaciones o transiciones.

### Instrucciones adicionales:
   - Puede utilizar create-react-app o cualquier otro boilerplate de su preferencia para comenzar.
   - Puede usar cualquier librería adicional que considere útil para la tarea, pero justifique su elección.
   - Priorice la funcionalidad y claridad del código sobre el diseño, pero una interfaz amigable siempre es un plus.


## Instrucciones de Entrega:
### Repositorio en GitHub:
Crea un nuevo repositorio en tu cuenta personal de GitHub para este proyecto.
Asegúrate de que el repositorio sea público para que podamos acceder a él.
Haz commits regulares mientras trabajas en el proyecto para que podamos ver tu progreso y enfoque.

### README:
Incluye un archivo README.md en la raíz de tu repositorio.
En este archivo, proporciona una breve descripción del proyecto.
Detalla cualquier instrucción especial para ejecutar el proyecto, si es necesario.
Si decidiste usar herramientas, librerías o enfoques adicionales, justifica brevemente tus decisiones en este archivo.
Puedes incluir capturas de pantalla o GIFs del proyecto en funcionamiento para ofrecer una vista previa.
### Entrega:

Una vez hayas finalizado el proyecto, asegúrate de hacer push de todos tus cambios al repositorio en GitHub.
Envíanos el enlace directo a tu repositorio.
No es necesario que nos envíes ningún archivo por correo; revisaremos el código y su funcionamiento directamente desde tu repositorio en GitHub.

### Recomendaciones adicionales:
Asegúrate de que el código esté limpio y bien comentado.
Si enfrentaste algún desafío o hiciste alguna decisión técnica importante, no dudes en mencionarlo en el README.md o en los comentarios dentro del código.
Verifica que tu aplicación funcione correctamente antes de enviar el enlace. Es esencial que podamos ejecutarla sin problemas.

¡Esperamos con interés ver tu solución y te deseamos mucho éxito en esta prueba!
