# InfraestructuraComputacional-G1N

### Ejercicio Linux

#### Pasos para crear directorios y archivos con los comandos de Linux:

#### Ejercicio 1

##### Pasos para crear directorios y archivos con los comandos de Linux:

- Se creó el directorio abuelo e ingresé en él para crear el siguiente directorio.

![1](https://user-images.githubusercontent.com/63252576/161580198-a691ef0e-5dc9-4dc5-a892-b666fae23809.png)

- Creé la primera estructura y la observo en el árbol.

![2](https://user-images.githubusercontent.com/63252576/161581374-791b2016-3970-4546-9a18-988d0eacefdf.png)

- Edité el archivo del abuelo con el comando “ vi abuelo “  e ingresé los datos correspondientes.

![3](https://user-images.githubusercontent.com/63252576/161581727-8b452b57-9b82-475a-b09d-8762c6a5a0d0.png)

- Uso el comando wq para guardar y salir.

![4](https://user-images.githubusercontent.com/63252576/161582933-f72c7042-377a-4ce8-9df5-e45833a48643.png)

- Se crean los demás archivos dentro de los directorios.

![5](https://user-images.githubusercontent.com/63252576/161582971-aecc46f3-76a6-46ed-8665-9a64d1149fdc.png)

- Se realizan las mismas acciones para el árbol de la abuela creando los directorios y los archivos de cada uno.

![6](https://user-images.githubusercontent.com/63252576/161583014-77239a58-1fa7-4463-93a4-9cdd1319bf89.png)

### Taller 2

#### Ejercicio 1

##### Recuperar la contraseña del usuario root

- Oprimir una tecla para detener el arranque
- Presionar la tecla "e"

![7](https://user-images.githubusercontent.com/63252576/161583019-b327a1b1-ef4b-4109-a884-195faab84383.png)

- Buscar la línea linux y reemplazar la sentencia "rhgb quiet" por "rd break"
- Presionar Ctrl + x

![8](https://user-images.githubusercontent.com/63252576/161583024-642c329c-9d17-4cad-a803-339a53f8ee86.png)

### Uso del comando "mount" para cambiar la contraseña del root
- mount -o rw, remount /sysroot/
- mount 
- chroot/sysroot/
- passwd
- touch /.autorelabel
- Exit x2

![9](https://user-images.githubusercontent.com/63252576/161583025-912fdd52-2e3e-49a8-a061-7cf66f4eb258.png)

- Ingreso al root con la nueva contraseña

![10](https://user-images.githubusercontent.com/63252576/161583028-54108064-031b-424a-8c47-5f2257cf3b85.png)

#### Ejercicio 2
##### Mover archivos en los directorios

- Árbol de directorios

![11](https://user-images.githubusercontent.com/63252576/161583044-725b96f4-68e3-4ac1-85fe-bbd20f9ec889.png)

- Creando los demás directorios

![12](https://user-images.githubusercontent.com/63252576/161583046-97096707-2416-4fda-8153-79683d2059f1.png)

- Moviendo los archivos existentes de cada directorio del bisabuelo a los directorios de la bisabuela

![13](https://user-images.githubusercontent.com/63252576/161583049-8e7d597e-9e51-4263-8528-54322e604735.png)

- Realizando la misma acción con los archivos de la bisabuela

![14](https://user-images.githubusercontent.com/63252576/161583054-6d6e144a-a1d0-4111-8786-3216e2d7a431.png)

- Listo el nuevo árbol de directorios con los archivos intercambiados.

![15](https://user-images.githubusercontent.com/63252576/161589198-9748b279-51f5-431d-a945-b9320d054c29.png)


## Taller Permisos
- Crear dos grupos llamados: profesor, estudiante.

![Screenshot_1](https://user-images.githubusercontent.com/63252576/162847867-2d32bb97-5444-4476-bbcd-2c28a5edb744.png)

-  Crear tres usuarios llamados: diana, claudia y laura.

![Screenshot_2](https://user-images.githubusercontent.com/63252576/162847871-9046bc92-6842-420b-a1e4-8204b6fb9a96.png)

- Conociendo que: diana es un profesor; laura es una estudiante y claudia es un profesor y un estudiante. Adicione todos los usuarios a los grupos correspondientes.

![Screenshot_3](https://user-images.githubusercontent.com/63252576/162847876-24b147a5-9a29-463f-8d92-fd8c7f709f4f.png)

![Screenshot_3 1](https://user-images.githubusercontent.com/63252576/162847875-845dfe03-be12-4272-bcd3-a0ae91c0a077.png)

- Cree dos directorios, uno para profesores (solo los profesores tienen acceso) y otro para estudiantes (profesores y estudiantes tienen acceso). Asegúrese de asignar los permisos.

![Screenshot_4](https://user-images.githubusercontent.com/63252576/162847877-0848be0e-8605-4cc5-ae18-3136799c6fae.png)

![Screenshot_5](https://user-images.githubusercontent.com/63252576/162847878-22ca30ca-810f-4e04-89d9-4a25e87efba7.png)

![Screenshot_9](https://user-images.githubusercontent.com/63252576/162847885-5b3ca507-2ee9-41e4-890c-1c160861ab50.png)

![Screenshot_10](https://user-images.githubusercontent.com/63252576/162847888-fbf1abf5-c073-4d31-9367-222a984574a0.png)

- Verifique los permisos anteriores, usando las cuentas de los usuarios ya creados.

![Screenshot_11](https://user-images.githubusercontent.com/63252576/162847889-965a87b8-84a2-4c97-a8c5-b8d4e9b6c4b2.png)

- Use un editor de texto para crear archivos en los respectivos directorios, usando diferentes usuarios.

![Screenshot_18](https://user-images.githubusercontent.com/63252576/162850024-ee74d0e8-19b4-474b-addf-735390376df1.png) 

- Como super usuario, cambie de dueño los archivos creados (como ejercicio).

![Screenshot_12](https://user-images.githubusercontent.com/63252576/162847890-c188d341-8bc0-44ba-8e1c-8fc3340942de.png)

- Usando diferentes terminales, entre al sistema con los diferentes usuarios: (equivoquese algunas veces por completo):

![Screenshot_13](https://user-images.githubusercontent.com/63252576/162847892-1bc71c52-6940-4333-b3b5-131354422c0e.png)

-  Usando diferentes terminales, entre al sistema con los diferentes usuarios:(equivoquese algunas veces en las claves o en el nombre de usuario):

![Screenshot_14](https://user-images.githubusercontent.com/63252576/162850348-29b6ad75-a001-490d-82a0-527c7e7dc554.png)

- Determine la cantidad de veces que el estudiante laura ingreso al sistema.

![Screenshot_15](https://user-images.githubusercontent.com/63252576/162850355-8d205b86-228a-47bd-8c03-0f4ff68c92f8.png)

- Comprima el contenidos del directorio de los profesores en profesore.tgz y el contenido del directorio de los estudiante en un archivo estudiantes.zip

![Screenshot_16](https://user-images.githubusercontent.com/63252576/162850357-7084e3b1-1fc8-41a1-9129-6d7bbdb6f25c.png)

- Cree un alias para cambiar la clave del usuario diana.

![Screenshot_17](https://user-images.githubusercontent.com/63252576/162850359-7162060c-a867-4437-9f2f-431ecf36c150.png)









