# CEIA_computer_vision_I

## Trabajo Práctico 1

Parte 1 (imágenes en /white_patch y /coord_cromaticas):
* Implementar el algoritmo de pasaje a coordenadas cromáticas para librarnos de las variaciones de contraste.
* Implementar el algoritmo White Patch (check qué no hayan puntos blancos en la imagen) para librarnos de las diferencias de color de iluminación.
* Mostrar los resultados obtenidos y analizar las posibles fallas (si es que las hay) en el caso de White patch.
![alt text](img/img_1.png)

Parte 2
* Para las imágenes img1_tp.png y img2_tp.png leerlas con OpenCV en escala de grisas y visualizarlas.
* Elija el número de bins que crea conveniente y grafique su histograma, compare los histogramas entre si. Explicar lo que se observa, si tuviera que entrenar un modelo de clasificación/detección de imágenes, considera que puede ser de utilidad tomar como ‘features’ a los histogramas?
* Para la imagen segmentacion.png analice el histograma de los canales RGB. Segmente algunos de los elementos presentes en la imagen (agua, cielo, tierra) y muestre, aplicando mascaras, las regiones en imágenes separadas.
