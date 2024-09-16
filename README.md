# Virtual Paint

## Introducción

El programa 'Virtual Paint' es una aplicación que permite a los usuarios dibujar formas geométricas y trazos libres utilizando sus manos como controladores, detectadas a través de una cámara web. Está diseñado para ser intuitivo y fácil de usar, permitiendo a cualquier persona crear dibujos en tiempo real mediante el uso de simples gestos con las manos.

## Requisitos del Sistema

Para poder ejecutar el programa 'Virtual Paint', se deben cumplir los siguientes requisitos mínimos:
- Python 3.x instalado en el sistema.
- Librerías necesarias: OpenCV, MediaPipe, NumPy.
- Una cámara web funcional.
- Un sistema operativo compatible (Windows, MacOS, Linux).

## Instalación

Para instalar las dependencias necesarias, puedes ejecutar los siguientes comandos en la terminal del directorio donde tienes instalado el programa:

1. `pip install opencv-python`
2. `pip install mediapipe`
3. `pip install numpy`

Luego, asegúrate de tener una cámara conectada y simplemente ejecuta el archivo del programa. Es probable que le pida acceso a la cámara y luego el programa se cierre, solo vuelva a ejecutar para que prenda.

## Uso del Programa

El programa 'Virtual Paint' detecta la posición de las manos y permite dibujar utilizando los siguientes modos:
- Trazo libre: Permite dibujar libremente moviendo la mano.
- Línea recta: Traza una línea recta entre dos puntos.
- Rectángulo: Dibuja un rectángulo utilizando los movimientos de la mano.
- Círculo: Dibuja un círculo basado en la distancia entre dos puntos.
- Borrar trazo: Borra partes del dibujo actual.

La herramienta se selecciona automáticamente cuando el usuario mueve la mano con el dedo índice levantado sobre el área de herramientas, ubicada en la parte superior izquierda de la ventana.

## Cómo Seleccionar una Herramienta

Para seleccionar una herramienta, simplemente mueve tu mano con el dedo índice levantado al área superior izquierda, enseguida saldrá un círculo amarillo que indica qué herramienta estás tomando. Mantén tu mano en la herramienta deseada hasta que el programa confirme la selección.

![Selección de herramienta](media/image1.png)

Pon tu mano así para poder seleccionar una de las 5 herramientas disponibles

![Mano libre](media/image2.png)

Si quieres mover tu mano libremente sin seleccionar o dibujar haz esta seña y el programa no hará nada

![Mano para dibujar](media/image3.png)

Cuando ya hayas seleccionado una herramienta haz esta seña y siguiendo los pasos de la siguiente sección empezarás a realizar trazos sobre la cámara.

## Cómo Dibujar

Dependiendo de la herramienta seleccionada y teniendo los dedos arriba como se indica en el paso anterior:
- Para trazo libre, simplemente mueve tu mano y el programa dibujará siguiendo el movimiento.
- Para líneas rectas, mueve la mano desde el punto inicial al punto final (habrá una previsualización para mostrar el trazo).
- Para círculos y rectángulos, selecciona dos puntos que definirán el tamaño y la forma de la figura.
- Para borrar, selecciona la herramienta 'Borrar trazo' y muévete sobre el área a eliminar.

## Salir del Programa

Para salir del programa, simplemente presiona la tecla 'ESC'.

## Utilidad Social del Programa

El programa 'Virtual Paint' puede ser una herramienta muy útil en la sociedad, especialmente en el ámbito educativo y artístico. Puede ser utilizado como una herramienta de enseñanza para niños, facilitando el aprendizaje de conceptos geométricos y fomentando la creatividad. Además, proporciona una experiencia divertida y atractiva para cualquier persona que quiera explorar nuevas formas de expresión artística. En entornos con accesibilidad limitada a herramientas físicas, como escuelas o comunidades con pocos recursos, este programa ofrece una manera sencilla y efectiva de experimentar el arte digital sin la necesidad de equipos especializados.
