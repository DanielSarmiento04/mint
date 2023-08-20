# Curso de Keras con TensorFlow

Las redes neuronales artificiales son un intento por simular el comportamiento de aprendizaje del cerebro. Los primeros experimentos se bañan en conectar partes del cerebro para estimular el aprendizaje

[https://images.app.goo.gl/aJ2Jga1WPVdSqxXv7](https://images.app.goo.gl/aJ2Jga1WPVdSqxXv7)

### Librerías disponibles

1. [Tensorflow](https://www.tensorflow.org/)
2. [PyTorch](https://pytorch.org/)

Inteligencia artificial ⇒ Busca replicar inteligencia humana.

Machine learning ⇒ Técnicas que busca replicar el aprendizaje automático.

Deep learning ⇒ Aprendizaje profundo, 

| Machine learning | Deep learning |
| --- | --- |
| Implementa lógica de negocio | Solo red neuronal |
|  | Peligro con el overfitting, (sobre entrenar) |
|  |  |

## Neuronas

Celulas nerviosas interconectadas

El perceptron, es una neurona artificial que busca imitar el funcionamiento de las neuronas del cerebro, el objetivo es tener varios perceptores con el fin de comunicarlos entre si, esto se hace con el fin de incluir casos atípicos?, se usa en el aprendizaje supervisado, de esta manera va alterando los pesos a medida que los resultados van coincidiendo con los datos reales

![Screenshot 2023-08-18 at 9.03.11 PM.png](Curso%20de%20Keras%20con%20TensorFlow%20301e3a5867174c7c8a4a06bdc1830c9b/Screenshot_2023-08-18_at_9.03.11_PM.png)

## Arquitectura

Sea n el numero de  entradas  y m en numero de neuronas (perceptrones) 

$$
\begin{vmatrix}
W_{11} & W_{12} & W_{13} & ... & W_{1n} \\
W_{21} & W_{22} & W_{23} & ... & W_{2n} \\                              ... & ... & ... &  & ... \\                                             W_{m1} & W_{m2} & W_{m3} & ... & W_{mn} \\
\end{vmatrix}_{mxn} *           \begin{vmatrix}
X_{1} \\
X_{2} \\                              X_{3} \\                                         ...   \\                                                       X_{n} \\
\end{vmatrix}_{n x 1} = \begin{vmatrix}
X1*W_{11} + X_2 *W_{12} + X_3* W_{13} + ...  + X_n *W_{1n} \\
X1*W_{21} + X_2 *W_{22} + X_3* W_{23} + ...  + X_n *W_{2n} \\                    ...  \\                          X1*W_{m1} + X_2 *W_{m2} + X_3* W_{m3} + ...  + X_n *W_{mn}\\
\end{vmatrix}_{mx1}  
$$

Referencias 

[https://www.famaf.unc.edu.ar/~revm/digital24-3/redes.pdf](https://www.famaf.unc.edu.ar/~revm/digital24-3/redes.pdf)

[https://www.famaf.unc.edu.ar/~revm/digital24-3/redes.pdf](https://www.famaf.unc.edu.ar/~revm/digital24-3/redes.pdf)

[https://datascientest.com/es/perceptron-que-es-y-para-que-sirve#:~:text=Un perceptrón es una neurona,redes neuronales del Deep Learning](https://datascientest.com/es/perceptron-que-es-y-para-que-sirve#:~:text=Un%20perceptr%C3%B3n%20es%20una%20neurona,redes%20neuronales%20del%20Deep%20Learning).