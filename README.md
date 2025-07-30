# Recado: aplicación móvil distribuida de mensajería geolocalizada 
UNIVERSIDAD NACIONAL DE EDUCACIÓN A DISTANCIA (UNED)<br/>
ESCUELA TÉCNICA SUPERIOR DE INGENIERÍA INFORMÁTICA<br/>
Proyecto de Fin de Grado <br/>
# Objetivo 
El presente proyecto presenta Recado, una aplicación móvil de mensajería geolocalizada desarrollada sobre un sistema distribuido siguiendo un modelo cliente-servidor. Su objetivo principal es permitir el envío de mensajes a personas o entidades cercanas haciendo uso de tecnologías como GPS y mapas interactivos como OpenStreetMap. Además, la aplicación permite escribir mensajes sin destinatario, denominados recados, que permanecen anclados en una ubicación específica, accesibles para otros usuarios que se encuentren en las proximidades. Esta alternativa de comunicación permite una serie de interacciones que 
enriquecen la aplicación. 
# Pantalla principal
<img width="1530" height="690" alt="image" src="https://github.com/user-attachments/assets/cc056017-92a8-4a37-8733-def914c97150" />
# Tecnologías empleadas
El desarrollo se ha realizado utilizando principalmente las siguientes tecnologías: 
Android, Kotlin y Jetpack Compose para el cliente móvil, Flask-RESTful y Python para el servidor y MongoDB como base de datos NoSQL. 
El cliente se comunica con el servidor mediante una API RESTful, empleando tokens JWT para su autenticación. 
Se han realizado pruebas de la API con Postman y validaciones funcionales basadas en escenarios reales de uso, superando satisfactoriamente todos los casos definidos. 
Finalmente, se ha desplegado el servidor en la nube mediante Render, integrando una base de datos de MongoDB Atlas.
# Arquitectura
<img width="1415" height="442" alt="image" src="https://github.com/user-attachments/assets/89071728-e01a-40f8-8e9b-eb1bdfd05b38" />
# Conclusiones
Recado demuestra la viabilidad técnica y funcional de una aplicación de geo-mensajería con un enfoque centrado en la interacción local, útil tanto para usuarios individuales como para negocios y entidades públicas. 
# Palabras clave 
Aplicación móvil, sistema distribuido, cliente, servidor, Android, Kotlin, Jetpack Compose, Python, Flask, API, REST, JWT, MongoDB, geo mensajería, geolocalización, OpenStreetMap, GPS.
# Nota
Para más información me remito a la Memoria del PFG, donde se detalla pormenorizadamente el proceso de instalación, tanto para desarrollo (debug) como para despliegue (deployment).
