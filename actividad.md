Taller: Diseño Arquitectónico con Microservicios
Curso : Arquitectura de Software
Enunciado

Se desea desarrollar un sistema para la gestión de artículos académicos de estudiantes universitarios. El sistema permitirá el envío de artículos, su proceso de revisión por parte de editores, la publicación de estos y la administración general del sistema.

A partir de los requisitos funcionales suministrados, los estudiantes deberán proponer una arquitectura basada en microservicios, justificando sus decisiones de diseño y evidenciando la interacción entre los componentes del sistema.

🎯 Objetivo

Diseñar e implementar parcialmente un sistema basado en arquitectura de microservicios, aplicando principios de desacoplamiento, cohesión y comunicación entre servicios.

Actividades a desarrollar
1. Análisis y agrupación
Analizar los 20 requisitos funcionales.
Agruparlos en microservicios coherentes (mínimo 5 microservicios).
Justificar la agrupación basada en responsabilidades.
2. Diseño arquitectónico
Proponer una arquitectura de microservicios que incluya:
Identificación de servicios
Responsabilidades de cada servicio
Relación entre servicios
Definir el estilo de comunicación (REST, mensajería, etc.).
Considerar principios como:
Bajo acoplamiento
Alta cohesión
Independencia de despliegue
Diagrama de bloques que indique el enfoque de manejo de microservicios
3. Diagrama de despliegue
Elaborar un diagrama de despliegue UML que incluya:
Microservicios
Bases de datos (una por servicio o compartida, justificar)
Clientes (web/móvil)
Infraestructura (contenedores, servidores, etc.)
4. Prototipo funcional
Implementar al menos 2 microservicios funcionales.
Cada microservicio debe:
Tener su propia lógica de negocio
Estar conectado a una base de datos
Implementar comunicación entre microservicios:
Ejemplo: REST (HTTP), JSON
. 
Requisitos Funcionales 
RF1. El sistema debe permitir consultar artículos publicados.
RF2. El sistema debe permitir el registro de estudiantes, editores y administradores.
RF3. El sistema debe permitir a los editores rechazar artículos.
RF4. El sistema debe permitir al administrador generar reportes (artículos enviados, aprobados, rechazados).
RF5. El sistema debe permitir editar artículos antes de ser revisados.
RF6. El sistema debe permitir a los estudiantes enviar artículos.
RF7. El sistema debe permitir consultar el estado del artículo (en revisión, aprobado, rechazado, publicado).
RF8. El sistema debe permitir el inicio de sesión de los usuarios registrados.
RF9. El sistema debe permitir al administrador gestionar (crear, editar, eliminar) usuarios.
RF10. El sistema debe permitir filtrar artículos por autor, fecha o estado.
RF11. El sistema debe permitir adjuntar archivos (PDF, DOCX) al artículo.
RF12. El sistema debe permitir a los editores visualizar los artículos pendientes de revisión.
RF13. El sistema debe permitir al administrador configurar parámetros generales del sistema.
RF14. El sistema debe permitir solicitar correcciones al estudiante.
RF15. El sistema debe permitir a los editores aprobar artículos.
RF16. El sistema debe permitir eliminar artículos enviados por el estudiante.
RF17. El sistema debe permitir recuperar contraseña.
RF18. El sistema debe permitir al administrador configurar categorías de artículos.
RF19. El sistema debe permitir publicar artículos aprobados.
RF20. El sistema debe permitir a los editores agregar comentarios de revisión.

