# Vinculaci�n de variables clim�ticas a ciclos de cultivo

El presente proyecto desarrollado en `Rproject` tiene el prop�sito de describir el proceso realizado para el procesamiento de variables clim�ticas en ciclos de cultivo, donde la informaci�n fuente son estaciones meteorol�gicas. Este es un paso importante en el an�lisis de agricultura espec�fica por sitio, debido a que el clima desempe�a un rol importante en la explicaci�n de la variaci�n en rendimiento. Los pasos descritos ser�n de utilidad cuando se tiene sitios de inter�s georreferenciados, cuya informaci�n est� dada en un periodo de tiempo y adem�s se quiere evaluar la relaci�n con estaciones meteorol�gicas dentro de la misma localidad que est�n georreferenciadas.

Dentro de la carpeta scripts encontrar� los dos siguientes archivos:

* *Stations_Catalog.R*: En este proceso se organiza los datos clim�ticos en un cat�logo que ser� utilizado en el siguiente script Distances_Process. Tambi�n se calcula la altura de los lotes y estaciones, con base en un RASTER de altura de la localidad de inter�s.
* *Distances_Process*:  En este paso se realiza el proceso de vinculaci�n de estaciones a lotes y se c�lculas los indicadores clim�ticos de inter�s.

El archivo *Merge_Stations_Funs.R*, contiene funciones programadas que son utilizadas en *Distances_Process*
Para utilizar los scripts debe primero tener instalada una versi�n de R-Studio, preferiblemente la 1.1.423 y una versi�n de R mayor a 3.4.3, posteriormente abrir el archivo `Vinculacion_clima_lotes_comerciales.Rproj` y desde esta consola abrir los scripts. Para ejecutar el ejemplo reproducible se debe descomprimir el archivo `chiapas_srtm.zip`, que est� en la carpeta BASIC_FILES.
Para m�s informaci�n detallada del funcionamiento de cada paquete, puede consultar la carpeta CATALOGS, en la cual se extiende la explicaci�n de cada funci�n y adem�s sigue un ejemplo reproducible en Chiapas M�xico.
