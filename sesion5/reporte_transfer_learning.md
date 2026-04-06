## ¿Qué es Transfer Learning?
El *Transfer Learning* es una técnica de aprendizaje en la que se utiliza un modelo previamente entrenado con una gran cantidad de datos para resolver un nuevo problema. En lugar de entrenar desde cero,solo se ajustan algunas partes del modelo.Esto permite ahorrar tiempo, usar menos datos y obtener mejores resultados.
## ¿Qué modelo usaste?
El modelo utilizado fue **MobileNetV2**.
Sus principales características son:
- Optimizada para dispositivos móviles
- Usa menos parámetros que otros modelos
- Ideal para colab y proyectos con recursos limitados
- Rápida y de fácil acceso
- Ideal para Transfer Learning

## Resultado de la predicción
Probé el modelo con una imagen de un gato.
El modelo predijo:
1. tabby                42.9%
2. Egyptian_cat         24.6%
3. tiger_cat            20.2%
La predicción del modelo fue correcto.

## Parámetros congelados vs entrenables
Total de parámetros: 2,422,081
Parámetros entrenables: 164,097 (6.8%)
Parámetros congelados: 2,257,984 (93.2%)

## Aplicación potencial
### ¿Cuál es el problema que quieres resolver?
El problema que quiero resolver es la detección temprana de enfermedades respiratorias (como neumonía o tuberculosis) 
### ¿Qué tipo de datos necesitarías?
Necesitaría imágenes médicas, como radiografías de tórax, tanto de personas sanas como de pacientes con enfermedades
respiratorias.
### ¿Qué modelo base usarías y por qué?
Usaría **MobileNetV2** porque es un modelo rápido, ligero y de acceso gratuito. 
Esto permitiría implementarlo en dispositivos móviles o computadoras con pocos recursos.
### ¿Cuántos datos crees que necesitarías?
Entre 2000 y 5000 imágenes médicas. ya que debido al Transfer Learning, no es necesario tener millones de datos, ya que el modelo ya tiene conocimientos previos sobre imágenes.

## Opinión personal
Lo que más me sorprendio fue la precision con la que identifica una imagen e incluso te da los distintos tipos de razas a las cuales puede pertenecer el animal.
