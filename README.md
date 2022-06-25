# Redes-neuronales-prediccion-cancer
Contexto empresarial. Trabajamos en un grupo de investigación médica que trabaja para desarrollar un método de diagnóstico que identifica la predisposición al cáncer de un individuo en función de imágenes de células humanas.

Esta herramienta podría ser revolucionaria para identificar mutaciones específicas en el gen p53 asociado al cáncer sin pruebas genéticas; el procedimiento podría ser mucho más barato y menos invasivo. Además, si entendemos qué características de las imágenes se están utilizando para distinguir las células mutantes, esto podría ayudar a generar más hipótesis y experimentos sobre las diferencias biológicas subyacentes para ayudar a determinar la predisposición de una persona.

Hay tres tipos diferentes de mutaciones que desea poder detectar, basándose en cientos de imágenes de células fotografiadas bajo un microscopio. También debe poder detectar si existe una mutación.

Problema comercial. Se le ha encomendado predecir la mutación de una célula, dada cualquier información que pueda obtener de estas fotografías. Específicamente, utilizará imágenes sin procesar de células de fibroblastos humanos y características extraídas de estas imágenes mediante algoritmos de procesamiento de imágenes.

Contexto analítico. Trabajaremos con datos de imágenes y aprenderá sobre redes neuronales más avanzadas: en particular, la red neuronal convolucional (CNN). Practicará el uso y la comparación de una variedad de clasificadores de aprendizaje automático, tanto tradicionales como más modernos, para abordar la pregunta: ¿Podemos predecir mutaciones cancerosas a partir de imágenes de células humanas?

El caso está estructurado de la siguiente manera: (1) comprenderá el conjunto de datos de imágenes sin procesar; (2) construirás, entrenarás y evaluarás una CNN simple desde cero; (3) construirás, entrenarás y evaluarás una CNN más compleja usando el módulo keras de TensorFlow; y (4) creará, entrenará y evaluará un clasificador de aprendizaje automático más tradicional (bosque aleatorio) en un conjunto de características extraídas previamente de las imágenes sin procesar.
