# ProceSmart
Proyecto ABP 
# Introducción 
En la actualidad, la gestión eficiente de procesos es fundamental tanto en instituciones educativas como en empresas, ya que permite optimizar recursos, reducir tiempos de respuesta y mejorar la organización interna. Sin embargo, muchas organizaciones aún dependen de trámites manuales o sistemas dispersos que dificultan el control y seguimiento de actividades, generando retrasos y baja productividad.
Con este propósito se propone el desarrollo de la aplicación “ProceSmart”, una herramienta digital que facilita la gestión centralizada de procesos, permitiendo registrar, monitorear y dar seguimiento a solicitudes de forma ágil y ordenada. La aplicación busca mejorar la comunicación entre usuarios, ofrecer notificaciones automáticas, generar reportes y asegurar que cada trámite pueda visualizarse en tiempo real, contribuyendo a una administración más eficiente y transparente.

# Análisis de requerimiento 
La aplicación ProceSmart busca optimizar la gestión de procesos internos mediante un sistema digital centralizado. Para cumplir con este objetivo, se identifican las siguientes funcionalidades principales:

1.Gestión de usuarios

2.Registro y autenticación de estudiantes, docentes/empleados y administradores.

3.Asignación de roles con diferentes niveles de acceso.

4.Módulo de solicitudes

5.Creación de solicitudes (ej. certificados, permisos, trámites administrativos).

6.Visualización del estado del trámite (pendiente, en revisión, aprobado, finalizado).

7.Panel de control para consultar el avance de cada proceso en tiempo real.

8.Historial de trámites realizados por el usuario.

9.Notificaciones automáticas

10.Avisos por correo o dentro de la app sobre cambios en el estado del proceso.

# Diagrama de modelo lógico
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/e5f9764c-ca3d-4d97-998d-2f654bbadd79" />

# Descripción de las tablas principales

Usuarios
Propósito: Almacenar toda la información de los usuarios del sistema, incluyendo estudiantes, personal administrativo y administradores.

Relevancia: Es la tabla central, ya que todas las solicitudes, notificaciones y reportes dependen de los usuarios que interactúan con el sistema. Contar con esta tabla permite gestionar accesos, roles y autenticación.

Solicitudes

Propósito: Registrar cada trámite o petición que realiza un usuario, como certificados, permisos o solicitudes internas.

Relevancia: Permite llevar un control detallado de todas las gestiones realizadas por los usuarios, conocer su estado actual y relacionarlas con los procesos asociados.

Procesos

Propósito: Detallar los pasos específicos que cada solicitud debe seguir para completarse.

Relevancia: Facilita el seguimiento de las solicitudes, asegurando que se cumplan todos los pasos necesarios y se pueda monitorear el avance de cada trámite en tiempo real.

Notificaciones

Propósito: Guardar los mensajes enviados a los usuarios sobre cambios de estado en sus solicitudes o procesos.

Relevancia: Mantiene a los usuarios informados de manera automática, mejorando la comunicación interna y reduciendo la necesidad de consultas manuales sobre el estado de los trámites.

Reportes

Propósito: Registrar reportes generados por los administradores para análisis del sistema, eficiencia y tiempos de respuesta.

Relevancia: Permite a los administradores tomar decisiones basadas en datos reales, evaluar la carga de trabajo, tiempos de resolución y desempeño general del sistema.
