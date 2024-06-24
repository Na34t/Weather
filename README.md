Instrucciones para correr el programa:

Antes de correr el programa primero tenemos que entrar a la carpeta Proyecto01, luego proyecto, src, archivos, imagen_pantalla, a traves de un editor de texto, por ejemplo Visual Studio Code, tenemos que abrir el programa archivo_principal.py y en donde dice ruta cambiarla a la ruta en donde la estes abriendo, es decir, una vez que abras la carpeta imagen_pantalla, escribe en la terminal pwd, esta te dira la ruta de tu archivo, al final agrega   /imagenes.png, otra opcion de encontrar la ruta en Visual Studio Code es con el click derecho pulsar en el archivo imagen.png y buscar una opcion que diga Copy Path, una vez hecho eso pegalo en donde dice ruta sin quitar ' ', de igual manera para el archivo leer_csv.py, tienes que cambiar la ruta pero ahora en la carpeta que dice datos_ciudades, es decir, primero entra a la carpeta Proyecto01, luego proyecto, src, archivos, datos_ciudades y vuelve a repetir el procedimiento anterior para la terminal, despues agrega al final de la ruta /dataset1.csv, si es en Visual Studio Code es con el click derecho pulsar en el archivo dataset1.csv y buscar una opcion que diga Copy Path, una vez hecho eso pegalo en donde dice ruta.
Tambien para el archivo que dice tests, es decir, tenemos que entrar a la carpeta Proyecto01, luego proyecto, src, tests cambia la ruta en donde dice ruta, ruta2 y ruta_bien=ruta2=, para la que dice ruta buscaremos la ruta del archivo_principal.py, para ruta2 buscaremos el mismo archivo, es decir, archivo_principal.py, pero al momento de agregar la ruta al final cambialo a /archivos_principal.py, ya que este te dira que no existe el archivo y para ruta_bien=ruta2= escribe la ruta del archivo_principal.py

URGENTE: Es muy importante que al agregar la ruta nunca se eliminen las comillas, ya que sin ellas no va a funcionar ningun programa

Despues de descargar los archivos que puede ser por git clone o zip nos dirigimos a la carpeta Proyecto01, luego proyecto, src, archivos, archivo_principal.py y seleccionamos la opción abrir en terminal, nos aparecerá ya la dirección donde se encuentran nuestros archivos, ahora para ejecutar escribiremos:

Mac y Linux:python3 archivo_principal.py
Windows:python archivo_principal.py

RECORDATORIO:Revisar el archivo Proyecto_informacion.pdf, en este archivo se encontrarán las instrucciones de cómo instalar python y las distintas librerías que se ocuparán.

Al ejecutar el archivo archivo_principal nos pedirá ingresar el nombre de la ciudad de origen y destino, el nombre se debe de ingresar completo y no abreviado, despues de escribir el nombre se tendrá que presionar enter para que pueda pedir la ciudad de destino. Una vez presionado el enter nos proporcionará los datos pedidos y se terminará el programa. 
AVISO: Los demás archivos no se requieren abrir en terminal ya que el que utiliza la informacion que se escribieron en estos es el archivo_principal.py


Para ver si las pruebas del archivo están bien deberá entrar al archivo Proyecto01, luego proyecto, src, tests, prueba.py y seleccionamos la opción abrir en terminal, nos aparecerá ya la dirección donde se encuentran nuestros archivos, ahora para ejecutar escribiremos:

Mac y Linux:python3 prueba.py
Windows:python prueba.py

Y este indicara cuantas pruebas estan verificando a la informacion e indicara si hay algun error o todo se encuentra bien 

Si se requiere mas informacion o existe algun problema favor de contactarse al correo: natalia.zavala@ciencias.unam.mx
