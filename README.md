# Implementación del Hill Cipher

Este proyecto es una implementación del algoritmo de cifrado Hill Cipher, desarrollado como proyecto final para un curso de álgebra matricial. El proyecto demuestra tanto un enfoque manual como una implementación en Python para cifrar y descifrar mensajes utilizando el Hill Cipher.

## Descripción del Proyecto

El Hill Cipher es un cifrado por sustitución poligráfica basado en álgebra lineal. Utiliza una matriz cuadrada como clave para cifrar bloques de texto. La matriz clave debe ser invertible en el espacio aritmético modular definido por el tamaño del alfabeto utilizado.

## Características

- Implementación manual del algoritmo Hill Cipher.
- Implementación automatizada utilizando las bibliotecas de Python: NumPy, SymPy y Math.
- Cifrado y descifrado de mensajes de texto.
- Generación de matrices invertibles.
- Aritmética modular para manejar el conjunto de caracteres.

## Bibliotecas Utilizadas

- **NumPy**: Para operaciones numéricas eficientes y manejo de matrices.
- **SymPy**: Para matemáticas simbólicas e inversión de matrices.
- **Math**: Para funciones matemáticas como el cálculo del máximo común divisor.

## Cómo Funciona

### Implementación Manual

1. **Generación de la Matriz Clave**: Se genera una matriz invertible aleatoria como clave de cifrado. Se verifica que la matriz sea invertible dentro del módulo especificado.
2. **Vectorización del Mensaje**: El mensaje se convierte en un vector numérico utilizando un conjunto de caracteres predefinido.
3. **Cifrado**: El vector del mensaje se multiplica por la matriz clave y luego se reduce módulo el tamaño del conjunto de caracteres.
4. **Descifrado**: Se utiliza la inversa de la matriz clave para descifrar el mensaje, invirtiendo el proceso de cifrado.

### Implementación en Python

Los mismos pasos que la implementación manual se traducen en código Python, aprovechando las capacidades de NumPy, SymPy y Math para cálculos y operaciones matriciales eficientes.


## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, no dudes en enviar un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.

## Contacto

Para cualquier pregunta o sugerencia, por favor abre un issue o contáctame directamente.
