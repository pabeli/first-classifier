# Machine Learning 
## Terminología
- Cada fila es una observación (ejemplo, instancia, registro).
- Cada columna es una característica (predictor, atributo, variable independiente)
- 
## Iris dataset
- Es considerado un problema de aprendizaje supervisado: predecir la especie de un iris usando mediciones. 
- Es famoso ya que su predicción es sencilla. 

### Cargar el dataset con scikit-learn
1. Importar la clase load_iris del módulo de datasets: 
`from sklearn.datasets import load_iris`
1. Resguarda el objeto que contiene al dataset: `iris = load.iris()`