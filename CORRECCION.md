1. ¿Qué mala práctica identificaste?

El código HTML contenía estilos sin estar vinculados a una hoja de estilos externa, lo cual viola el principio de separación de responsabilidades.

2. ¿Por qué es considerada una mala práctica?

Incluir o depender de estilos no centralizados (o directamente no tenerlos vinculados) impide:

Escalar adecuadamente el proyecto

Reutilizar estilos entre diferentes páginas o componentes

Mantener el código de forma limpia y organizada

Mejorar la experiencia de trabajo en equipo y colaboración


3. ¿Cómo la solucionaste?

Agregué la siguiente línea en la sección <head> del archivo HTML para vincular un archivo de estilos externo:

<link rel="stylesheet" href="index.css">

Luego, se pueden definir todos los estilos necesarios en index.css.

4. ¿Qué beneficios aporta tu solución?

Permite mantener el código más limpio y modular

Facilita la reutilización de estilos en todo el proyecto

Mejora la mantenibilidad y escalabilidad del sistema

Sigue las buenas prácticas de desarrollo web profesional



---