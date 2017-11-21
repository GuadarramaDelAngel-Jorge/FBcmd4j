# FBcmd4J
Evidencia final del curso - Computaci�n en Java 2017

## Instalaci�n
**Clonar el repositorio**  
```
git clone https://github.com/GuadarramaDelAngel-Jorge/-fbcmd4j.git
```
**Importar a Eclipse**  
1. Dar clic en `File -> Import -> Existing Projects into Workspace`.
2. Se deber� seleccionar la carpeta donde est� el proyecto ya clonado.

**Exportar .jar**  
1. Dirigirse a la barra de herramientas de Eclipse.
2. Dar click en `File -> Export -> Runnable JAR File -> Next`.
3. Seleccionar la clase que tiene el m�todo main de nuestro programa como `Launch configuration`.
4. Dar click en `Browse` para seleccionar la carpeta de destino.
5. Seleccionar (*Extract required libraries into generated JAR*).
6. Dar click en `Finish`.

**Ejecutar .jar**  
1. Abrir la carpeta previamente seleccionada y copiar el archivo JAR a la carpeta `C:\Program Files\Java\jdk1.8.0_144\bin`.
2. Abrir la terminal (*utilizar privilegios de administrador en Windows*).
3. Navegar a la carpeta `fbcmd4j/bin` donde se encuentra el archivo `fbcmd4j.jar`.
4. Ejecutar el comando `java -jar fbcmd4j.jar`.

## Uso
**Configurar tokens**   
1. Seleccionar la opci�n 0 `Configurar tokens`.
2. Escribir identificador de aplicaci�n.
3. Escribir clave secreta de aplicaci�n.

**Obtener el NewsFeed**   
1. Seleccionar la opci�n 1 `NewsFeed`.
2. Escribir 'Si' en caso de querer guardar los posts en un archivo.
	* Escribir el n�mero de posts a guardar.

**Obtener el Wall**   
1. Seleccionar la opci�n 2 `Wall`.
2. Escribir 'Si' en caso de querer guardar los posts en un archivo.
	* Escribir el n�mero de posts a guardar.

**Publicar un Estado**   
1. Seleccionar la opci�n 3 `Publicar Estado`.
2. Escribir el estado deseado.

**Publicar un Link**   
1. Seleccionar la opci�n 4 `Publicar Link`.
2. Escribir el link deseado.

## Cr�ditos

C�digo base desarrollado a lo largo del curso por:
-  Jose Manuel Lopez Lujan, MIT
- **https://github.com/jm66/CS13303**

Desarrollado por:
- Jorge Guadarrama Del Angel

## Licencia
El c�digo est� disponible bajo la licencia **MIT**. Consulte el archivo LICENSE en la ra�z del proyecto para m�s informaci�n.
