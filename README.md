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


