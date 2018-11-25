# Tutorial: como utilizar Ultimaker Cura

#### En el siguiente tutorial voy a explicar como utilizar el software de "Slicing" Ultimaker Cura. Este software transforma los archivos de diseño 3d en una secuencia de capas, para poder ser interpretada por la impresora 3d.

### Paso 1: Descarga
    Lo primero que hay que hacer es descargar el software de la página oficial "https://ultimaker.com/en/products/ultimaker-cura-software" antes de descargarlo se puede elegir el sistema operativo para el cual se va a descargar, haciendo click donde dice Windows al lado del boton de descargar.
    
### Paso 2: Instalación
    Una vez descargado hay que instalarlo, abriendo el instalador y seleccionando la ruta deseada para instalar el programa.
    
### Paso 3: Descargar diseños 3d
    Una vez que el programa se haya instalado lo abrimos. Cuando se abra lo vamos a dejar abierto y nos vamos a ir al navegador y a la siguiente pagina "https://www.thingiverse.com/" en ella se podrán descargar diseños 3d para trabajar con Cura. Elegimos el que más nos guste y lo descargamos.
    
### Paso 4: Trabajar con el archivo descargado
    Una vez descargado el archivo recomiendo extraerlo en una carpeta, una vez extraido buscamos la carpeta files uqe contiene los archivos de diseño 3d con formato ".stl".
    Volvemos al Cura y abrimos el archivo, seleccionando el mismo desde la pestaña archivo/abrir archivo, o simplemente lo arrastramos al programa.
    Una vez importado el archivo es hora de posisionarlo y escalarlo, En la parte de arriba del margen izquierdo hay varias opciones: mover, escalar, rotar, espejar y segmentar. Pero voy a explicar la de mover, escalar y rotar.
    
    -Mover: esta opción nos da la posibilidad de posicionar el objeto, estableciendo los valores de posicion de los 3 ejes (las medidas están en milímetros)
    
    -Escalar: esta opción nos permite cambiar las proporciones del objeto, estableciendo las medidas en los 3 ejes (en la herramienta de escalado las medidas son proporcionales entre si, por lo tanto si yo le doy una altura de 50 mm las otras medidas se van a ajustar a esos 50 mm)

    -Rotar: esta opción nos permite girar el objeto a voluntad, cuando se selecciona esta opción aparecen 3 anillos alrededor del objeto, cada uno corresponde a cada uno de los ejes sobre los cuales se gira la el objeto.
    
### Paso 5: Configuración de impresión
    Una vez escalado y posicionado el objeto ahora viene la parte de la configuración de impresión. En el margen derecho de la pantalla esta la configuración, la personalizada y la recomendada, pero nosotros vamos a usar la recomendada.
    Tenemos la altura de capa, el relleno, generar soporte y adherencia de la placa de impresión.
    
    -Altura de capa: como su nombre lo dice es la altura que va a tener cada capa, mientras más alto sea el valor, más rápido será la impresión para cambiar el valor hay que ir a la pestaña de configuración personalizada y modificarlo desde ahí.
    
    -Relleno: es la solidez que va a tener la pieza, mientras más porcentaje de relleno tenga, más solida será el interior del objeto y por lo tanto más tiempo va a tardar en imprimir
    
    -Generar soporte: el soporte de la pieza sirve para que a la hora de imprimir no quede ninguna parte de la pieza al aire con el riesgo de caerse.
    
    -Adherencia a la placa de impresión: agrega una zona plana de una sola capa alrededor del objeto que evita que el mismo se deforme
    
    Una vez terminada la configuración pasamos al sexto y último paso.
    
### Paso 6: Convertir en .gcode
    Una vez configurado todo, hay que convertir el archivo de ".stl" a ".gcode". El archivo .gcode es el formato de archivo que reconoce la impresora 3d.
    Para esto lo que hay que hacer es, click en el botón que dice "Guardar en archivo", elegimos la carpeta y lo guardamos.
    Ahora hay que pasar el archivo a una microSD y poner la misma en la impresora.
    
    