# Prácticas FSI
## Búquedas

Se desarrollan dos tipos de búsqueda a partir del código proporcionado:
- Búsqueda de ramificación por acotación: se ordena la lista abierta a partir del coste del camino acumulado. Para ello creamos un nuevo método en utils.py llamado babg. Copiamos el método FIFOQueue y en extend ordenamos por el coste del camino acumulado.
- Búsqueda de ramificación por acotación y subestimación: se ordena la lista abierta a partir del coste acumulado y la estimación  heurística. Para ello creamos un nuevo método en utils.py llamado babg. Copiamos el método FIFOQueue y en extend ordenamos por el coste del camino acumulado y la estimación heurística.
Comprobamos que la búsqueda informada expande menos nodos que la no informada.

## Redes Neuronales - Detección de Malaria**

A partir del código proporcionado entrenamos una red neuronal convolucional que a partir de un dataset con imágenes de muestras de glóbulos rojos infectados y no infectados de malaria, pueda distinguir entre esas dos categorías.
Importamos la biblioteca keras de redes neuronales de código abierto escrito en Python.
Aplicamos una nueva capa convolucional, le aplicamos maxpooling para reducir datos y usamos la función dropout para evitar el sobreajuste.
