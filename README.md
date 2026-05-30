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




