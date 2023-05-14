# Seleccion-de-caracteristicas
Métodos de selección de características


Filtrar métodos
Los métodos de filtro son el tipo más simple de método de selección de características. Funcionan filtrando características antes de la construcción del modelo en función de algunos criterios.


Ventajas


Son computacionalmente económicos, ya que no implican probar las características subdivididas usando un modelo.


Pueden funcionar para cualquier tipo de modelo de aprendizaje automático.


Desventajas


Es más difícil tener en cuenta las relaciones multivariadas porque no estamos evaluando el rendimiento del modelo. Por ejemplo, una variable puede no tener mucho poder predictivo por sí sola, pero puede ser informativa cuando se combina con otras variables.


No están diseñados para tipos específicos de modelos.


Ejemplos


Umbrales de varianza


Correlación


Información mutua


Métodos de envoltura


Los métodos de envoltura implican ajustar un modelo y evaluar su rendimiento para un subconjunto particular de características. Funcionan mediante el uso de un algoritmo de búsqueda para encontrar qué combinación de funciones puede optimizar el rendimiento de un modelo determinado.

Ventajas


Pueden determinar el conjunto óptimo de características que producen los mejores resultados para un problema específico de aprendizaje automático.


Pueden explicar mejor las relaciones multivariadas porque se evalúa el rendimiento del modelo.


Desventajas


Son computacionalmente costosos porque el modelo debe reajustarse para cada conjunto de características que se prueba.


Ejemplos


Selección de funciones secuenciales adelante/atrás/bidireccional


Eliminación de características recursivas


Métodos integrados


Los métodos integrados también implican la creación y evaluación de modelos para diferentes subconjuntos de características, pero su proceso de selección de características ocurre al mismo tiempo que el paso de ajuste del modelo.

Ventajas


Al igual que los métodos de envoltorio, pueden optimizar el conjunto de funciones para un modelo en particular y tener en cuenta las relaciones multivariadas.


También son generalmente menos costosos computacionalmente porque la selección de características ocurre durante el entrenamiento del modelo.
Ejemplos


Regularización (p. ej., regresión de lazo/cresta)


Importancia de las características basadas en árboles


Conclusión
Cuando se trata de la cantidad de funciones que debe mantener para su modelo, más no siempre es mejor. Vale la pena ser selectivo sobre qué funciones conservar para maximizar el rendimiento y reducir el ruido. Por lo tanto, encontrar e implementar el método de selección de características correcto es una parte clave del desarrollo de un modelo efectivo y confiable.
