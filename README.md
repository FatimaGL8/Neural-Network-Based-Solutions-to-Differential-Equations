# Solución de EDOs y EDPs con Redes Neuronales (PINNs) 🤖
## 📖 Descripción
¡Bienvenido a este repositorio! Aquí encontrarás códigos para la aproximación y solución de Ecuaciones Diferenciales Ordinarias (EDOs), Sistemas Diferenciales Ordinarios (SDOs) y Ecuaciones en Derivadas Parciales (EDPs) utilizando técnicas de ajuste y redes neuronales, con un enfoque especial en las PINNs (Physics-Informed Neural Networks).

### 🗂️ ¿Qué incluye este repositorio?
#### ⚙️ Aproximación utilizando técnicas de interpolación o ajuste
Se utilizan técnicas de interpolación o ajuste, aplicadas a casos simples como una EDO o a casos más complejos como puede ser un SDO o una EDP.

#### 🎯 Aproximación utilizando métodos numéricos
En algunos de los problemas se utilizan diferencias finitas o métodos como el Runge-Kutta (de 3º orden) para aproximar la solución, si no se puede obtener la solución exacta.

#### 🧠⚡ Solución mediante PINNs 
Luego, se resuelven EDOs y EDPs complejas con PINNs, aprovechando la física conocida y las redes neuronales para encontrar soluciones precisas y eficientes. Entre los casos implementados se incluyen:

o EDO trigonométrica (simple)

o SDO (modelo difusión) 🧪  [⚫⚫⚫ | 〰️ | ⚪⚪ ]

o Ecuación de ondas unidimensional 🌊📈

o Ecuación de ondas (en dominios 1️⃣D y 2️⃣D) 

o Ecuación de calor unidimensional 🔥

o Modelo Fisher-Kolmogorov (concentración tumoral) 🧬🦠

o Deformación estructural de una viga (en voladizo) 🏗️

## 🔍 ¿Qué encontrarás aquí?
o Modelos neuronales robustos: Arquitecturas diseñadas para resolver ecuaciones diferenciales con y sin condiciones iniciales y de contorno.

o Ejemplos prácticos: Casos clásicos y aplicaciones reales que muestran el potencial de las PINNs para resolver problemas complejos.

o Visualizaciones completas: Gráficas y animaciones 2D y 3D que permiten comparar la predicción de la red neuronal con soluciones exactas o aproximaciones numéricas.

o Implementación modular y extensible: Diseñado para adaptarse fácilmente y ampliarse a nuevos problemas físicos y matemáticos. Permite cambiar la arquitectura de la red, el número de iteraciones, la función de activación, los optimizadores, así como la cantidad de puntos de entrenamiento, facilitando una personalización completa según las necesidades del problema.

## 📚 Bibliografía
o  F. John. *Partial differential equations*, volume 1. Springer, 1991.
	[ Enlace.](https://es.1lib.sk/book/5002489/5a740a/partial-differential-equations.html)
 
o  Randall J. LeVeque. *Finite Difference Methods for Ordinary and Partial Differential Equations*. Siam, 2007.

o Salsa S., *Cap.Diffusion, Partial Differential Equations in Action*, UNITEXT, vol 86. Springer, Cham, 2015.

o Python Software Foundation. [*PYTHON*.](https://www.python.org/)

o NumPy documentation. [*NUMPY*.](https://numpy.org/)

o PyTorch documentation. [*PYTORCH*.](https://pytorch.org/)

o SciPy documentation. [*SCIPY*.](https://scipy.org/)

o TensorFlow documentation. [*TENSORFLOW*.](https://www.tensorflow.org/)

o Keras documentation. [*KERAS*.](https://keras.io/)

o Vuong Dang. *Learning the Waves: Solving the 2D Wave Equation with Physics-Informed Neural Networks*, Repositorio GitHub, 2025.[ Enlace.](https://github.com/vuongdang97/Portfolio-AI/tree/main)

o Paul C. Fife. *Reaction-Diffusion Equations and Their Applications to Biology*. Springer, 1979.

o Ferdinand P. Beer, E. Russell Johnston, John T. DeWolf. *Mechanics of Materials*. McGraw-Hill, 2012 (edition 7).

o Walter A. Strauss. *Partial Differential Equations: An Introduction*. Wiley, 2007 (edition 2).

o Cecilia Cespedes. *Inversión de datos sísmicos con PINN (Physics-Informed Neural Networks)*. Repositorio en GitHub, 2023.[ Enlace.](https://github.com/Ceciliaces/Inversion-de-datos-sismicos-PINN)

o Juan David Toscano. *Learning Scientific Machine Learning: Residual-Based Attention PINNs, PIKANs y DeepONets*. Repositorio en GitHub, 2023.[ Enlace.](https://github.com/jdtoscano94/Learning-Scientific_Machine_Learning_Residual_Based_Attention_PINNs_PIKANs_DeepONets)

o omniscientoctopus. *Physics-Informed Neural Networks*. Repositorio GitHub, 2021.[ Enlace.](https://github.com/omniscientoctopus/Physics-Informed-Neural-Networks/tree/main)

 
