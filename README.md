Descripción
---
Permite generar representaciones procedurales de islas, tanto en dos dimensiones como en tres, en ambos casos pudiendo modificar parametros como tamaño de la isla generada o número de nodos (los nodos actuan como nucleos de las islas, a más nodos, más islas).

El proyecto es creado experimentando con las librerías de Matplotlib, Numpy y TKinter.

Requisitos
---
Requisitos: Matplotlib, Numpy.

Instalación de los requisitos:
```
pip install matplotlib, numpy
```

Método de empleo
---
El archivo options_gui.py actua como main, tras su ejecución se tiene acceso a una interfaz en la que se pueden configurar los parámetros, tamaño determinará que tan grande es la imagen de la isla generada, número de nodos determinará cuando nodos se generan, a más nodos haya más islas podrán llegar a generarse, por último dimensión determina si se generará una isla en 2 dimensiones o en 3 dimensiones. 

Preview
---

Visualización 2D con 1 nodo:

![screenshot](images/2D_1.png)


Visualización 2D con 2 nodos:

![screenshot](images/2D_2.png)


Visualización 2D con 6 nodos:

![screenshot](images/2D_3.png)

Visualización 3D con 1 nodo, 150 de tamaño:

![screenshot](images/3D_1.gif)

Visualización 3D con 1 nodo, 70 de tamaño:

![screenshot](images/3D_2.gif)

Visualización 3D con 3 nodos, 170 de tamaño:

![screenshot](images/3D_3.gif)
