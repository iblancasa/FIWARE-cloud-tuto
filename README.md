FIWARE-cloud-tuto
=================

Tutorial para utilizar el servicio cloud de FIWARE


Antes de empezar, cabe decir que el proceso requiere de mucha paciencia ya que (al menos cuando se escribe esta página) la página web tiene muchos problemas técnicos y deja de funcionar correctamente.

![Inicio FIWARE LAB](images/creacioncloud/0.jpg)
*Este es un ejemplo de lo que pasa*


Una vez hayamos accedido a [FIWARE LAB](https://account.lab.fi-ware.org/), obtendremos esta página

![Inicio FIWARE LAB](images/creacioncloud/1.jpg)

Deberemos registrarnos, rellenando el siguiente formulario

![Registro](images/creacioncloud/2.jpg)

Cuando rellenemos el formulario, se enviará un email a la dirección de correo electrónico que se ha indicado en el formulario. Una vez confirmada nuestra cuenta (pulsando sobre un enlace que tiene el mail), nos llevará a esta página

![Inicio como conectado](images/creacioncloud/3.jpg)

En la barra superior, disponemos de varias opciones. Pulsaremos sobre "Cloud", que nos llevará a la siguiente vista

<font color="red">**IMPORTANTE: ¡¡NO LANCES UNA NUEVA INSTANCIA!!**</font>
Antes hay que hacer algunas cosas.

![Cloud](images/creacioncloud/4.jpg)


Pulsamos sobre "Security" y tendremos la siguiente vista

![Security](images/creacioncloud/5.jpg)

Accederemos a la pestaña "Security groups". Crearemos un nuevo grupo de seguridad haciendo click en "Create Security Group". Aparecerá un formulario como el siguiente (que rellenaremos con el nombre que querramos darle al grupo y una breve descripción)

![Security Group formulario](images/creacioncloud/6.jpg)

Una vez creado, haremos click derecho sobre él y pulsaremos la opción "Edit rules". Aparecerá una ventana como la siguiente


Crearemos una nueva regla cuyos valores serán:

+ IP Protocol: TCP
+ From port: 22
+ To port: 22
+ Source group: CIDR
+ CIDR: 0.0.0.0/0

Una vez relleno, pulsaremos sobre "Add rule" y veremos como se crea una nueva regla. Podremos cerrar el formulario. Ahora nos dirigiremos a la pestaña "Keypairs". Pulsaremos sobre "Create Keypair" y aparecerá un formulario como el que se muestra a continuación (en el que escribiremos un nombre para nuestro keypair).

![Crear keypair](images/creacioncloud/7.jpg)
