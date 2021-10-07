# Efecto_de_Blurring-Multiprocesadores

Programa que realiza el efecto de desenfoque sobre una imagen de gran pixelaje (mayor a 2000 pixeles ya sea en alto o ancho de la imagen).

La dimensión mínima de la mascara para observar el efecto de desenfoque:

  Se presentan 3 códigos:
  -MatrizImagen, que aplica una mascara de 3x3, que se nota el desenfoque pero en imagenes pequeñas
  -MatrizImagen7x7, mascara de 7x7, se nota el desenfoque en imagenes grandes si se hace zoom
  -MatrizImagen9x9, Mascara de 9x9, se nota el desenfoque en imagenes grandes más visiblemente
 
  La opción con la que me quedé y el código que fue aplicado fue la de 9x9, dado que
  se nota mejor el desenfoque que las otras dos.

Número de threads óptimo para desarrollar este proceso en el menor tiempo posible:

  Ocurrió algo interesante, el tiempo mínimo ocurrió con un solo thread.
  Cuando aumentaba el número de threads aumentaba el tiempo de ejecución.
  Esto se puede ver en la imagen "tiempos"

Resultados de las imágenes:
 
  En la carpeta de imagenes se muestran las imagenes originales y las desenfocadas.
  Se puede notar el desenfoque, incluso más si se le aplica zoom a la imagen.
  Estas imagenes desenfocadas fueron hechas con el código que aplica la máscara
  de 9x9.
