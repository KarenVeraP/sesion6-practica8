# Práctica 8. Creación de Blob Storage
## Creación de la cuenta de almacenamiento
El la barra de búsqueda de  Azure buscamos las cuentas de almavenamiento.

![Práctica 8 - Parte 1](imagenes\p8p1.png)

Configuramos la cuenta de almacenamiento:
- Suscripción
- Grupo de recursos: sesion6
- Nombre de la cuenta de almacenamiento (éste deberá se único): almacen3210
- Región

![Práctica 8 - Parte 2](imagenes\p8p2.png)

Configuraremos la redundancia LRS.

![Práctica 8 - Parte 3](imagenes\p8p3.png)

En el apartado de redes verificamos que esté habilitado el acceso público desde todas las redes y el enrutamiento de red de Microsoft.
Revisamos y creamos la cuenta de almacenamiento.

![Práctica 8 - Parte 4](imagenes\p8p4.png)

## Crear y cargar un Blob Storage
En la cuenta de almaneamiento, en la sección de Almacenamiento de datos buscamos _Contenedores_.

![Práctica 8 - Parte 5](imagenes\p8p5.png)

Configuramos el nuevo contenedor:
- Nombre: blobstorage
- Nivel de acceso público: Contenedor (acceso de lectura anónimo...)

![Práctica 8 - Parte 6](imagenes\p8p6.png)

Una vez creado el contenedor nos metemos a éste, y dentro de el contenedor seleccionamos _Cargar_.

![Práctica 8 - Parte 7](imagenes\p8p7.png)

Cargamos el archivo que queramos.

![Práctica 8 - Parte 8](imagenes\p8p8.png)

Se abrirá la ventana de búsqueda para seleccionar el archivo que queremos cargar, lo seleccionamos y cargamos.

![Práctica 8 - Parte 9](imagenes\p8p9.png)

El archivo se subirá al contenedor.

![Práctica 8 - Parte 10](imagenes\p8p10.png)

Al seleccionar el contenedor se nos abrirá una ventana; en Información general encontraremos un URL el cual, al copiarlo y pegarlo en la barra de búsqueda de nuestro navegador, nos abrirá el archivo que hemos cargado.

![Práctica 8 - Parte 11](imagenes\p8p11.png)

El archivo se encuentra guardado en el Blob Storage y podemos acceder a él con el URL, dada la configuración de nuestro Blob Storage podemos compartir el URL de nuestro archivo.

![Práctica 8 - Parte 12](imagenes\p8p12.png)

Para eliminarlo, se puede hacer desde la ventana que nos aparece al seleccionarlo o haciendo click izquierdo sobre el archivo.

![Práctica 8 - Parte 13](imagenes\p8p13.png)

### Sitio web estático
Podemos hacer un sitio web estático subiendo nuestra página a la cuenta de almacenamiento. Para ello buscamos en la sección de Administración de datos _Sitio web estático_.

![Práctica 8 - Parte 14](imagenes\p8p14.png)

Habilitamos el sitio web estático.

![Práctica 8 - Parte 15](imagenes\p8p15.png)

Le damos un nombre y lo guardamos.

![Práctica 8 - Parte 16](imagenes\p8p16.png)

Se nos creará un contenedor para hospedar el sitio web estático.

![Práctica 8 - Parte 17](imagenes\p8p17.png)

En este contenedor cargamos los archivos que queramos para generar nuestro sitio web estático.

![Práctica 8 - Parte 18](imagenes\p8p18.png)

## Extra
Es esta ocasión únicamente se creó una cuenta de almacenamiento como recurso.

![Práctica 8 - Parte 19](imagenes\p8p19.png)