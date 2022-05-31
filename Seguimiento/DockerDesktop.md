## Docker Desktop

Herramienta para correr contenedores y para la administración de imágenes. 
Se realiza una aplicación en java para posteriormente realizar un contenedor y almacenarla. En start.spring.io se realiza un pequeño proyecto en java:

![Screenshot_1](https://user-images.githubusercontent.com/63252576/171211217-841f28b4-8500-4080-9f3d-ff822385b0d8.png)

Para el proyecto realiza las importaciones necesarias para poder trabajar con docker, para la realización de esta actividad se realizo un proyecto pequeño
de un 'Hello word' con Spring boot y java.

### Árbol del proyecto

![Screenshot_2](https://user-images.githubusercontent.com/63252576/171212096-f026c0c8-e22e-4a60-9662-09a78b3482d5.png)

Se deben tener instalados java, maven y el docker para la realización del ejercicio.

Se compila la aplicación, generando un archivo .jar:

![Screenshot_3](https://user-images.githubusercontent.com/63252576/171213228-342c7fa4-1b59-4155-a87b-08d92ab3f3fd.png)

![Screenshot_4](https://user-images.githubusercontent.com/63252576/171213488-b8c0ba19-de27-403f-b051-d5a13d436584.png)

#### Ahora procede a la construcción del contenedor

Tomando el compilado que se ha creado:

![Screenshot_4](https://user-images.githubusercontent.com/63252576/171214281-3190b9f5-3748-4123-869e-7e27aa6c803d.png)

El contenedor toma la aplicación y ejecuta el comando del 'ENTRYPOINT', se verifica si funciona

![Screenshot_6](https://user-images.githubusercontent.com/63252576/171215010-d62e0dc4-8277-4f87-8ddd-3e4f1958b805.png)

#### Construcción de una imagen con docker

![Screenshot_7](https://user-images.githubusercontent.com/63252576/171215523-a4a0ff5e-e620-4370-8757-8154aed103a4.png)

- Verificacando que la imagen existe

![Screenshot_8](https://user-images.githubusercontent.com/63252576/171215925-e6b37070-08a5-4d60-915a-f44e324e5bc1.png)

- Ejecutando el contenedor

![Screenshot_9](https://user-images.githubusercontent.com/63252576/171216307-391e9dc1-d931-4386-8cd8-cb05f4517048.png)

- Verificando su ejecución

![Screenshot_10](https://user-images.githubusercontent.com/63252576/171216664-ad0efe2a-a911-4259-a457-7f1c9da0015d.png)

- Imagen en la aplicación de Docker

![Screenshot_11](https://user-images.githubusercontent.com/63252576/171217268-0dd2c8c2-2fd8-4da6-afe5-9bf469349775.png)

Docker desktop permite correr la aplicación desde el navegador utilizando 'localhost:8080' respondiendo desde el contenedor el llamado del navegador, 
permite inspeccionar los elementos del contenedor, sus variables de entorno, el java_home. su codificación, versión, el puerto por el cual se expone la aplicación,
las estadísticas del uso que tiene este contenedor, detener y volver a correr la aplicación y también eliminarla.




