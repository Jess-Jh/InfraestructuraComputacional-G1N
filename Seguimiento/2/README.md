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
