# Proyecto-Final-Contenedores-

Para el proyecto se debe seguir los parámetros de configuración y entrega, de acuerdo a la siguiente imagen se comienza a trabajar para ejecutar el proyecto.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/10cc4d0a-10f9-44e1-826e-ae43b267e708" /><br><br>

## ***YOLO***

Para la creación de la imagen de YOLO como contenedor en Docker hubo muchos problemas.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/abd4702f-40f0-49bd-ac7f-3a59ca396dad" /><br><br>

Finalmente arranca, pero no se obtiene la imagen para el contenedor, este queda guardado en los archivos de Docker como carpeta, ya que no se pudo implentar como imagen, trae errores en los diferentes scripts que se ejecutaron.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/9bc0ffd6-445e-4dcb-985c-8b3a38813e5b" /><br><br>

Se crean los directorios para YOLO, estos directorios son los que guardan la información de todo lo que se le esta enviando de información “data”.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/46c40e11-deef-4e85-81bc-1f75a2481535" /><br><br>

Se crean archivos de prueba, para revisar como se comporta YOLO.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/de53af5f-e255-4818-ac6d-2fed0f3ef642" /><br><br>

Se crea un contenedor de Roboflow, para que automaticamente reconozca las imágenes, esto gracias a un dataset creado en el mismo Roboflow.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/85b5af46-a5db-42ba-8f83-d278410fda19" /><br><br>

Lo que se realizo en Roboflow fue crear un proyecto, despues de crearlo empezar a subir las imágenes que se requerian, despues de subir las imágenes, debes crear el dataset el cual ve las imágenes y las mueve al mismo tiempo. Esto es lo que debe halar YOLO para que realmente se implemente.
<img width="1163" height="545" alt="image" src="https://github.com/user-attachments/assets/739b7917-0eb5-4e28-a126-826d7ca52a0f" /><br><br>

Despues de varios intentos y scripts enviados se logra implementar YOLO sin ninguna novedad, siempre habia un error ya sea por que no reconocia mi usuario creado en Roboflow o por que la APPI no estaba funcionando, también hubo errores donde escribi mal la carpeta del proyecto de Roboflow y tampoco se ejecutaba.
<p align="center"><img width="621" height="283" alt="image" src="https://github.com/user-attachments/assets/4aeff536-c643-4bc4-981e-cb9045833e16" /><img width="621" height="283" alt="image" src="https://github.com/user-attachments/assets/60cb20d2-2d3d-4771-bd23-f2dce1409e7d" /><img width="621" height="283" alt="image" src="https://github.com/user-attachments/assets/6b670231-cf7a-43eb-bfea-5e0283aa2ed1" /></p><br><br>

Creacion de carpeta para que funcionen YOLO de la mano de Roboflow.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/fc215069-b9c5-4492-94c5-f63d31018757" /><br><br>

Se envia Script para que Roboflow sea verificado.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/949c452b-c426-4fe4-959e-126ff6005f44" /><br><br>

Se envia Script para un entrenamiento, esto también es para que Roboflow responda a la petición.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/4cca0075-f0b1-4d41-b27d-ea883a3a67f4" /><br><br>

Se ejecutan estos comandos para que corran las carpetas de YOLO, worspace que es la que contiene la información de Roboflow creada con mi usuario, también corre la CPU de Roboflow, y por ultimo crea archivos nuevo en la carpeta de Ultralytics Settings v0.0.6 file.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/36156a24-a9ef-4157-8c7e-d90fb4e671cb" /><br><br>

Por ultimo YOLO ejecuta y trae las imágenes, en el resultado nos muestra margen de errores por cada imagen, el peso y cuanto se demora en subir la información de la misma.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/8cf79719-54d1-4517-a68b-454d2ccf4aeb" /><br><br>

## ***CHATBOT***
Se ejecutan los comandos para crear el archivo de YOLO-CHATBOT.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/6c455ccb-d710-4da4-a2a5-e96392e9e73c" /><br><br>

Se ejecuta el comando app.py el cual trae carpetas con audio y escritura esto con el fin de hacer preguntas por medio de texto y voz.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/3e8ed784-7e03-4b2b-84eb-7f1df9511b04" /><br><br>

Se crea la imagen del contenedor, las cuales debe llamar las demás carpetas que se implementaran en el transcurso de la ejecución.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/0f2fa6b8-3b92-4429-bdab-ce118b94c574" /><br><br>

Implementación de Chatbot con YOLO, se crean las carpetas para que pueda funcionar, esto desde un contenedor de Docker.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/e7b8c369-1f4b-4611-b0e1-182c4ab8d0fc" /><br><br>

Se crean las rutas en las mismas carpetas para que pueda ver las fotos y así pueda contestar preguntas acerca de las imágenes que tiene YOLO en el contenedor.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/fa985898-11f5-4898-ac1d-950a1d72cf35" /><br><br>

Finalmente, se puede visualizar el Chatbot creado, se tuvo errores pero responde de acuerdo a las imágenes que se incorporaron en YOLO, este Chatbot se abre localmente por el puerto 7860, esta configuración se realizo desde los comando ejecutados, se puede realizar el cambio del puerto si se desea, este puerto debe estar libre, de lo contrario no funcionara.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/239e7a1a-2308-4fc4-8e61-d598cab82d87" /><br><br>

## ***KUBERNETES***

Para poder trabajar en las modificaciones de la máquina virtual debian 12 se activa el servidor de ssh para poder conectarse por medio de la IP.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/47b7ffb4-44ae-4edb-9aa0-a253f80b7de1" /><br><br>

Verificacion de que el kubernet está funcionando dentro de la máquina virtual.
<img width="1163" height="283" alt="image" src="https://github.com/user-attachments/assets/0acf4d53-48a0-4100-a59f-90544973739b" /><br><br>

Validación de datos claves como lo son la cantidad de Kubernetes, versión, días en uso, IP por la que se tiene acceso y la imagen usada para la configuración.
<img width="921" height="54" alt="image" src="https://github.com/user-attachments/assets/920a8a61-5de1-4bc0-af2f-bfaf5f1db8ea" /><br><br>

verificación de los Pods que se crearon para lograr que tener todas las funcionalidades y configuraciones que fueron necesarias para el proyecto final, en este caso especial se tienen varios pods como lo son los que usan aragonés que funciona como una administrador automático del servidor del juego, supertuxkart la imagen que se guarda dentro de la WM para que funcione como servidor, calico-node que tiene la funcionalidad de red para que cada Pod que se cree se pueda comunicar por medio de una IP,  metrics-server función principal que nos ayuda a tener métricas en tiempo real de la memoria RAM y procesador que se usan por parte de los Pods, para tener un monitoreo de los diferentes servicios que se tienen configurados, se usó una combinación de herramientas para tener métricas en tiempo real telegraf que recolecta la información, influxdb que funciona como una base de datos local, para que la plataforma de grafana logre tener acceso y mostrar la información que se obtiene del sistema.

🔴Agones 
<img width="921" height="107" alt="image" src="https://github.com/user-attachments/assets/654334bf-d903-4d8b-b583-cb9cb01afceb" /><br><br>

🔴Juego
<img width="921" height="31" alt="image" src="https://github.com/user-attachments/assets/55d7c2ff-9743-42ac-badb-01855c59326e" /><br><br>

🔴Bade de datos
<img width="921" height="27" alt="image" src="https://github.com/user-attachments/assets/d8849f5b-96fd-4787-a305-ce8a2721081c" /><br><br>

🔴Plataforma de recolección
<img width="921" height="27" alt="image" src="https://github.com/user-attachments/assets/de15ca15-8c43-4181-b42f-87c56702d6ba" /><br><br>

Resumen
<img width="921" height="416" alt="image" src="https://github.com/user-attachments/assets/7f985a75-15bc-487b-ad26-d2922933c90a" /> 
<img width="921" height="416" alt="image" src="https://github.com/user-attachments/assets/b381d468-8113-4241-8290-f45ba9576ebe" /><br><br>

Fallas que se presentaron en la configuración
1-	para este se intentó como primera opción usar el sistema de monitoreo prometheus que nos ayuda a tener una supervisión de los recursos que se usa dentro del kubernet como lo son uso de CPU, uso de memoria, estado de pods, estado de nodos entro otros, la información recolectada se conecta con grafana plataforma que nos permite crear de manera grafica dashborad para entender de manera sencilla todo lo que pasa de manera interna, se tuvo falla con el exportador de la información que usaba prometheus ya que el servicio se detenía después de uno segundos de iniciar, por lo que se tuvo que usar una herramienta diferente para lograr tener métricas, en la imagen se puede observar como el prometheus presenta fallas en 2 de los 3 servicios al igual se ha intentado reiniciar el servicio para intentar recuperar la funcionalidad lo cual no fue posible, para el acceso se uso la IP y puerto http://192.168.139.135:9090.
<img width="921" height="34" alt="image" src="https://github.com/user-attachments/assets/934de152-e7cd-40ba-8c67-910a9995499f" />
<img width="921" height="252" alt="image" src="https://github.com/user-attachments/assets/20af6c2c-8259-43dd-9545-911f731087ff" />

2-	se intentó usa la plataforma Netdata para la recolección de datos, el cual funciono se logró tener medidas de los recursos del equipo, pero se tiene la limitante que es una plataforma que ya tiene parámetros predeterminados lo que no permite tener un detalle tan especifico como lo pide el proyecto, en este caso se usó la IP y puerto http://192.168.139.135:19999
3-	Fallas en la configuración de las ACL dentro del Router, se intentó realizar la configuración del router usando la red de la universidad con el fin de separar el tráfico del equipo donde está instalado el kubernete y el Doker, la idea era realizar dos VLAN con segmentos y que el ruter hiciera el nate o para que desde el grafana se pudiera tener un tráfico limpio, después de varias pruebas realizadas no fue posible debido a que la red de la universidad tiene muchos bloqueos.
<img width="616" height="674" alt="image" src="https://github.com/user-attachments/assets/204131ed-2cf0-47a9-9aaa-85420fe5ec12" />


configuración de dashboard dentro de grafana 
Se tiene 3 métricas que se recolectan de los kubernetes, tráfico recibido y enviado, máximo y mínimo de la memoria RAM, uso del procesador, para el ingreso por web se usura la IP y el puerto http://192.168.139.135:3000.
<img width="921" height="493" alt="image" src="https://github.com/user-attachments/assets/0daeb689-ceef-4a35-ab35-6562ee7ff235" /><br><br>
Se valida de que se este usando la base de datos que está conectada al kubernete,
<img width="921" height="254" alt="image" src="https://github.com/user-attachments/assets/ea6e55bb-510d-4096-82a0-a83b10ff8018" /><br><br>

Uso del juego dentro del equipo local
De forma inicial se configura una IP con el puerto 192.168.139.135:8080 para que se pueda usar como servidor el kubernete, esto para que se pueda usar como se menciona en el proyecto de conectar varias máquinas para ver la calidad del tráfico UDP, TCP, y la estabilidad que se tiene para la red al tener varios equipos al mismo tiempo, con la finalidad de entender un poco más, de cómo ver tableros de plataforma y entender cuando algo está funcionando bien o cuando no, para poder tomar medidas preventivas y evitar fallas de un sistema. 

Usar la Ip y el puerto seleccionado para el uso del juego como cliente 
<img width="921" height="713" alt="image" src="https://github.com/user-attachments/assets/797628d0-586d-4589-9674-25b704cb26d4" /><br><br>

Usar la Ip y el puerto seleccionado para el uso del juego como cliente.
<p align="center"><img width="921" height="737" alt="image" src="https://github.com/user-attachments/assets/d17a4524-b3b0-42bc-b917-49a5c5c04900" /><img width="921" height="737" alt="image" src="https://github.com/user-attachments/assets/5bc24be8-a2d4-4384-99b6-e119e5447dd1" /><img width="921" height="737" alt="image" src="https://github.com/user-attachments/assets/e4f653e2-9393-4be0-93bf-a8b0e5a0e03a" /><img width="921" height="737  " alt="image" src="https://github.com/user-attachments/assets/93632d55-ed62-4cc4-97b8-b685d06270d8" /><img width="921" height="737" alt="image" src="https://github.com/user-attachments/assets/47633807-1a39-4048-a8df-81a9e4884501" /> <br></p><br><br>







