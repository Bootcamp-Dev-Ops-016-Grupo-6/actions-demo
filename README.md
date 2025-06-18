- ¿Qué ventajas observaste al automatizar pruebas con GitHub Actions?

No era necesario preocuparse de ejecutar las pruebas manualmente, ya que se ejecutaban de forma automatica cada vez que el codigo se subia al repositorio

- ¿Qué diferencia a GitHub Actions de Jenkins u otras herramientas CI? 

La forma de escribir las pipelines que es más amigable con el usuario, pero que causa un ligero retraso comparado a Jenkins, además de integrarse de manera nativa con GitHub

- ¿Qué mejoras podrías agregar a este pipeline?

Se podría agregar un paso para manejar el caché de npm para que no instale las dependencias en cada ejecución

- ¿Qué consideraciones de seguridad aplicarías en proyectos reales?
  
En caso de integrar variables de entorno en el proceso de Github Actions que podrían comprometer la seguridad del sistema, siempre optar por utilizar Secrets para acceder a ellas u algún otra herramienta que permita esconder dichos datos.

Integrar procesos de diagnóstico de vulnerabilidades variados al código, las dependencias y la aplicación en uso que permitan capturar alguna vulnerabilidad que ponga en riesgo el proyecto.  
