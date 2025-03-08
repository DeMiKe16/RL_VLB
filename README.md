# Practica 2. Aprendizaje en entornos complejos
## Información
- **Alumnos:**  López Cuéllar, Alejandro; Vera Frutos, Miguel Ángel; Belda Fernández, Alejandro
- **Asignatura:** Extensiones de Machine Learning
- **Curso:** 2024/2025
- **Grupo:** VLB
## Descripción
El problema de la exploración y explotación en la toma de decisiones se estudia con modelos como el bandido de k-brazos, pero en entornos más complejos se usan procesos de decisión de Markov con recompensas desconocidas. Para resolverlos sin conocer el modelo del entorno, los agentes aprenden a través de la experiencia siguiendo una secuencia de observación, acción, transición y recompensa. Las técnicas de Monte Carlo actualizan la política al final de un episodio, mientras que las de Diferencias Temporales lo hacen en cada paso. Cuando el espacio de estados y acciones es demasiado grande, se usan funciones de aproximación con descenso del gradiente, como redes neuronales, o métodos de optimización directa de la política, como los enfoques Actor-Crítico. En esta práctica nos encargaremos de realizar un estudio de diferentes problemas del entorno Gymnasium, para lo cual resolveremos algunos de sus problemas haciendo uso de agentes y técnicas de aprendizaje por refuerzo. Realizando así un estudio, comparación, análisis y descripción de los resultados obtenidos.
## Estructura
La organización de los ficheros de este repositorio es la siguiente:
src: Contiene los ficheros py. En este ejemplo estara vacío.
data: Contiene los datos de entrenamiento y prueba. En este ejemplo estara vacío.
tests: Contiene los tests. En este ejemplo estara vacío.
main.ipynb: Fichero de Jupyter Notebook que te lleva a Google Colab. Además incluye una linea para descargar el repositorio.
notebook1.ipynb: Fichero de Jupyter Notebook que contiene una breve introducción del problema y enlace a los estudios.
etc.ipynb: Ficheros de Jupyter Notebook que contienen los estudios de los diferentes problemas
Videos: Directorios en los que se encuentran los videos de evaluacion para cada entorno y para agente implementado que intenta resolver el problema.
## Instalación y Uso
Abrir cada fichero en colab con el enlace que se incluye. En cada notebook se incluira una celda para importar el repositorio, instalar librerias que no esten en Colab e importar librerias.
## Tecnologías Utilizadas
Notebook 
Google Colab
Python 
Libreria Gymnasium

