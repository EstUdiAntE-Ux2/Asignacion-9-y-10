En el ejercicio 3 de la asignacion 9 se hace uso de un import os, este en python es un import de sistema operativo que permite la interaccion con las carpetas, archivos, procesos y rutas.
os.path.isdir(), el cual es un metodo del import que devuelve una lista de las carpetas y archivos presentes dentro de una direccion de archivos
os.path.join(), es otro metodo del import os que se usa, el cual dentro de este ejercicio y contexto de su uso en el for os.listdir(ruta): es para que cada elemento solo se tenga el nombre del archivo o carpeta pero no se ponga la ruta completa.
El no usar este metodo en el programa haria que python busque fotos en la carpeta donde se ejecute el script y no en la carpeta donde se quiere ver sus contenidos
