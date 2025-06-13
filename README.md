# Preguntas finales

**¿Qué beneficios concretos viste al automatizar la construcción con Jenkins?**  
Automatizar la construcción con Jenkins permite detectar errores rápidamente, reduce el trabajo manual, asegura la repetibilidad de los procesos y facilita la integración continua, mejorando la eficiencia y la calidad del software.

**¿Qué parte del proceso crees que sería más crítica en un equipo grande?**  
La integración y las pruebas automáticas son críticas, ya que permiten detectar conflictos y errores de manera temprana cuando varios desarrolladores trabajan en paralelo, evitando problemas en etapas avanzadas.

**¿Cómo Jenkins asegura calidad antes de hacer despliegues?**  
Jenkins ejecuta pruebas automáticas y validaciones en cada cambio, asegurando que solo el código que pasa todas las pruebas avance en el pipeline. Esto previene la introducción de errores en producción.

**¿Qué cambiarías en este pipeline para prepararlo para producción?**  
Habría que crar diferentes ramas en el repo , una de ellas *release* para subir los cambios a producción, posteriormente habría qeu crear en Jenkins un nuevo Job relacionando esta rama para ejecutar las acciones de testing y despliegue