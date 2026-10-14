# TAS1 - Estructura

## 1. Título

**Creación y Manipulación de Archivos y Directorios con Comandos de Linux**

## 2. Tiempo de duración

1 hora y 30 minutos

## 3. Fundamentos
Linux es un sistema operativo que permite administrar los recursos de un computador mediante diferentes herramientas. Entre estas una de las más importantes es la interfaz de línea de comandos (CLI), que permite ejecutar instrucciones desde la terminal para realizar tareas de administración, organización y manipulación de archivos y directorios.

En Linux, el sistema de archivos se organiza de forma jerárquica, mediante directorios y que permiten almacenar la información de manera ordenada. Para trabajar con esta estructura, existen comandos básicos que facilitan la creación, copia, movimiento y eliminación de archivos según la linea de comando digitada.

El comando mkdir permite crear directorios, mientras que rmdir se utiliza para eliminar directorios vacíos. Por otra lado, touch permite crear archivos vacíos y ls muestra el contenido de un directorio. También se utiliza cd para cambiar de ubicación dentro del sistema de archivos y pwd para conocer la ruta del directorio actual.
<img width="390" height="227" alt="image" src="https://github.com/user-attachments/assets/3910d7a8-abaf-4a6a-ac6f-41d3275242a1" />


Para manipular archivos, el comando cp permite realizar copias, mientras que mv sirve para moverlos o cambiar sus nombres. El comando rm permite eliminar archivos, por lo que debe utilizarse con precaución, ya que normalmente no los envía a una papelera de reciclaje.

Asimismo, los comandos echo y cat son útiles para trabajar con archivos de texto. echo permite mostrar mensajes y escribir contenido mediante operadores de redirección. El operador > escribe contenido y sobrescribe el archivo si ya existe, mientras que >> agrega información al final sin eliminar el contenido anterior. Por su parte, cat permite visualizar el contenido de los archivos y redirigirlo hacia otros.
<img width="285" height="117" alt="image" src="https://github.com/user-attachments/assets/da569852-c268-4b39-9bbf-11d05969a60d" />


El conocimiento de estos comandos es fundamental para comprender el funcionamiento de la terminal y desarrollar habilidades básicas de administración de sistemas. En esta práctica, su aplicación permite crear una estructura de directorios, manipular archivos de texto, realizar copias de seguridad y eliminar elementos, comprendiendo la importancia de organizar correctamente la información mediante comandos de Linux.





## 4. Conocimientos previos

Comandos basicos de linux: mkdir, rm, ls, tree
Creación de repositorios para subirlos a GitHub

## 5. Objetivos a alcanzar

Crear una estructura de directorios con el uso de comandos 

Editar archivos de texto a traves de la terminal GitBash

Eliminar archivos de manera segura, especificando de que tipo

## 6. Equipo necesario

Laptop
Terminal en GItBash

## 7. Material de apoyo

Videos dentro de la plataforma EVA
Apartado en el EVA con la lista de comandos 

## 8. Procedimiento

Paso 1: creacion de los directorios pricipales

<img width="532" height="417" alt="Captura de pantalla 2026-10-09 162644" src="https://github.com/user-attachments/assets/479a881e-5ead-45a8-af32-db54c2dd678b" />

Paso 2: Creación de archivos y modificación de su contenido en el directorio documentos

<img width="612" height="252" alt="image" src="https://github.com/user-attachments/assets/088518e6-7992-4df4-ba2b-d94a1c106b41" />

Paso 3: Copiar y mover los archivos (.txt) hacia otro directorio (scripts) y cambiando su nombre, seguidamente se movio hacia otro directorio (imagenes).

<img width="650" height="712" alt="Captura de pantalla 2026-10-09 162804" src="https://github.com/user-attachments/assets/0ebe6dd5-c501-4268-ade5-2908dd7468c7" />

Paso 4: se crea un archivo de texto (resumen.txt) y con el comando cat y operadores de escritura (>) se vuelca el contenido hacia la ruta especificada, en este caso de (notas.txt) hacia (resumen.txt), tambien se añadio la linea final con echo y (>>) para evitar que se sobreescriba el archivo.

<img width="662" height="252" alt="Captura de pantalla 2026-10-09 162851" src="https://github.com/user-attachments/assets/6e2fc1aa-4a6a-47f5-a17a-6f3091826650" />

Paso 5: se elimino el archivo (backup_notas.txt)  y se regreso al inicio de los directorios para eliminar la carpeta (imagenes) 

<img width="620" height="261" alt="Captura de pantalla 2026-10-09 162928" src="https://github.com/user-attachments/assets/094db2c3-67f8-4c90-960a-fd79a23a1019" />

Paso 6: se volcó todo el contenido en un archivo de texto usando el comando history

<img width="585" height="247" alt="Captura de pantalla 2026-10-09 162953" src="https://github.com/user-attachments/assets/22e25990-7419-429b-a268-b2f3d2f56df0" />


## 9. Resultados esperados

El resultado esperado es la correcta ejercitación de comando y la visualización de estos mismos a través de el archivo resumen con el comando history, comprendiendo así el manejo correcto de comandos en la terminal de linux o en este caso GitBash

## 10. Bibliografía

https://sololinux.es/comandos-de-linux-que-todo-usuario-debe-conocer/

https://www.cdmon.com/es/blog/comandos-basicos-linux
