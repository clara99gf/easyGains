# easyGains

## Descripción del Proyecto
El proyecto **easyGains** se centra en ayudar a personas que desean mejorar su físico mediante la hipertrofia muscular, que es el aumento del tamaño de las fibras musculares. Muchos usuarios de gimnasio enfrentan el desafío de no saber cómo estructurar un plan de entrenamiento efectivo que se adapte a sus circunstancias individuales.

### Problema Identificado
Los usuarios a menudo se sienten abrumados por la cantidad de información disponible sobre rutinas de entrenamiento, lo que puede llevar a la frustración y a la falta de progreso. Esto se debe a varias razones:

- **Falta de Conocimiento**: Muchos no comprenden conceptos clave como la hipertrofia o el volumen de entrenamiento.
- **Personalización**: No todas las rutinas son adecuadas para todos. Las necesidades de un principiante son diferentes a las de alguien con más experiencia, así como la cantidad de días que cada persona puede dedicar al entrenamiento.

### Necesidades de los Usuarios
Para desarrollar una rutina de entrenamiento eficaz, es crucial considerar:

- **La Disponibilidad de Días**: Determinar cuántos días a la semana puede dedicar cada usuario al entrenamiento.
- **El Nivel de Experiencia**: Adaptar las rutinas a las distintas etapas de entrenamiento: principiantes, intermedios o avanzados.

El objetivo de **easyGains** es proporcionar una solución estructurada que considere estos factores y ofrezca planes de entrenamiento individualizados que maximicen los resultados en función de las situaciones personales.

## Licencia
Este proyecto está bajo la licencia [GNU General Public License v3.0](./LICENSE).

## Configuración del Entorno
Para configurar el entorno de desarrollo de **easyGains**, se han llevado a cabo los siguientes pasos:

- **Creación de Clave SSH**: Se ha generado una clave SSH para establecer una conexión segura con GitHub. Consulta la captura en [creacion_clave.png](./configuracion_entorno/creacion_clave.png).
  
- **Subida de Clave a GitHub**: Después de crear la clave, se ha subido a GitHub utilizando el comando `ssh-add`. Consulta la captura en [subida_clave.png](./configuracion_entorno/subida_clave.png).

- **Configuración de Nombre y Correo**: Se han configurado las variables globales de usuario (nombre y correo electrónico) para que Git pueda asociar correctamente los commits. Consulta la captura en [nombre_correo.png](./configuracion_entorno/nombre_correo.png).

## Documentación Adicional

### Milestones

El desarrollo de **easyGains** está organizado en milestones para lograr avances graduales en la implementación de las funcionalidades clave. Se pueden consultar los detalles de cada milestone en la carpeta `docs/milestones`.

- [Milestone 0 (interno): Estructura Inicial del Proyecto](./docs/milestones/milestone-0.md)
- [Milestone 1: Implementación del Registro de Usuarios](./docs/milestones/milestone-1.md)
- [Milestone 2: Inicio de Sesión de Usuario](./docs/milestones/milestone-2.md)
- [Milestone 3: Recopilación de Datos del Usuario (Parte 1)](./docs/milestones/milestone-3.md)
- [Milestone 4: Recopilación de Datos del Usuario (Parte 2)](./docs/milestones/milestone-4.md)

### Historias de Usuario

Las historias de usuario definen las necesidades de los usuarios y las funcionalidades específicas que el sistema debe proporcionar para cumplir con ellas. Puedes consultar cada historia de usuario en la carpeta `docs/user_stories`.

- [HU001: Rutina Personalizada](./docs/user_stories/HU001.md)
- [HU002: Rutina Flexible](./docs/user_stories/HU002.md)
- [HU003: Ajustar Nivel Entrenamiento](./docs/user_stories/HU003.md)

### User Journeys

Además de las historias de usuario, se han creado algunos **User Journeys** para describir el viaje completo del usuario a través de la aplicación, cubriendo diferentes interacciones y funcionalidades. Estos journeys detallan la frecuencia de uso, el contexto, el dispositivo y los pasos que el usuario debe seguir para lograr sus objetivos. Puedes consultarlos en la carpeta `docs/user_journeys`.

- [Journey: Registro de Usuario](./docs/user_journeys/registro_usuario.md)
- [Journey: Generación de Rutina](./docs/user_journeys/generacion_rutina.md)

