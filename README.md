# Implementaciones de Machine Learning y Deep Learning desde Cero

Colección de algoritmos fundamentales de aprendizaje automático y redes neuronales implementados desde sus principios matemáticos, sin depender de abstracciones de alto nivel para el entrenamiento. El objetivo de este repositorio es demostrar el dominio de la mecánica interna, el cálculo matricial y la optimización detrás de cada modelo.

## Contenido del Repositorio

| Archivo | Algoritmo / Técnica | Enfoque Matemático y Técnico |
| :--- | :--- | :--- |
| `LogisticRegression.ipynb` | **Regresión Logística** | Implementación de la función sigmoide, entropía cruzada binaria (*log-loss*) y optimización mediante descenso de gradiente. |
| `BackPropagation.ipynb` | **Retropropagación (*Backpropagation*)** | Cálculo explícito de gradientes mediante la regla de la cadena para actualizar pesos en redes neuronales multicapa. |
| `RNN.ipynb` | **Redes Neuronales Recurrentes (RNN)** | Modelado de datos secuenciales y propagación del estado oculto a través del tiempo. |
| `GradCAM.ipynb` | **Grad-CAM (Explicabilidad Visual)** | Uso de gradientes de la última capa convolucional para generar mapas de calor e interpretar decisiones en visión por computadora. |
| `KnowledgeTransfer.ipynb` | **Transferencia de Conocimiento (*Transfer Learning*)** | Reutilización y ajuste fino de representaciones aprendidas en modelos preentrenados para nuevas tareas. |

## Stack Utilizado
* **Lenguaje:** Python
* **Cómputo numérico:** NumPy / Álgebra lineal matricial
* **Entorno:** Jupyter Notebooks
