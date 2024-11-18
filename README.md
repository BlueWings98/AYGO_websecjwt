# Mi Experiencia Construyendo una Aplicación Web Sin Servidor en AWS

En este archivo narro las partes mas importantes de la tarea de desplegar una aplicación serverless en AWS.

## Alojar un Sitio Web Estático

Comencé por alojar el frontend de mi aplicación como un sitio web estático. Utilicé AWS Amplify y me sorprendió lo sencillo que fue desplegar mis archivos HTML, CSS y JavaScript. Sin tener que configurar servidores ni preocuparme por la infraestructura, mi sitio estaba en línea en cuestión de minutos. La facilidad de uso y la integración con otros servicios de AWS hicieron que esta etapa fuera muy fluida.

## Administrar Usuarios

El siguiente paso fue implementar la autenticación de usuarios. Aquí es donde Amazon Cognito demostró su valor. Configuré un grupo de usuarios y personalicé los requisitos de inicio de sesión y registro. Me impresionó lo robusto que es Cognito en términos de seguridad y funcionalidades. Además, la integración con el frontend fue bastante directa gracias a los SDK proporcionados.

## Crear un Backend sin Servidor

Para manejar la lógica de negocio, utilicé AWS Lambda. Fue fascinante escribir funciones que se ejecutan en respuesta a eventos sin preocuparme por la gestión de servidores. La escalabilidad automática y el modelo de pago por uso de Lambda me permitieron centrarme en el código y la funcionalidad, sabiendo que AWS se encargaría del resto.

## Implementar una API RESTful

Con Amazon API Gateway, expuse mis funciones Lambda a través de una API RESTful. La configuración fue intuitiva, y aprecié la capacidad de definir rutas, métodos HTTP y políticas de seguridad de manera granular. Integrar la API con Cognito para la autenticación de usuarios añadió una capa extra de seguridad, asegurando que solo los usuarios autorizados pudieran acceder a ciertas operaciones.

## Eliminación de los Recursos

Al finalizar el proyecto, me aseguré de limpiar todos los recursos que había creado para evitar costos innecesarios. Aunque puede ser fácil olvidarse de este paso, AWS proporciona herramientas y dashboards que facilitan el seguimiento y eliminación de recursos. Esta práctica me recordó la importancia de una gestión responsable en la nube.


## Reflexiones Finales

Yo ya habia tenido experiencias previas con Serverless. Es una forma de programar muy distinta y para aplicaciones sencillas es bastante facil y comodo cuando se sabe lo que se hace. Siento que es como aprender a programar otra vez pues toca aprender a hacer todo desde el principio y sin ayuda hasta las tareas mas sencillas se complican. Me gustaria profundizar en esto en un futuro.

<img width="137" alt="image" src="https://github.com/user-attachments/assets/0139a46f-fe32-4e0a-8432-8431aca01cf6">
