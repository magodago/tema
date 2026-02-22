# Nivel avanzado

## Objetivos
- Comprender y aplicar métodos de programación funcional avanzados.
- Implementar patrones de diseño para la resolución de problemas complejos.

## Contenido
En esta lección del módulo de técnicas avanzadas, se profundizará en el uso de funciones puras y la manipulación de listas en lenguajes de programación que soportan programación funcional. Se explorará cómo las funciones puras pueden ser utilizadas para crear código más limpio y fácilmente testable, así como técnicas avanzadas como el map, filter y reduce para procesar datos de manera eficiente.

Además, se presentarán patrones de diseño avanzados que permiten la resolución de problemas complejos en un marco funcional. Se discutirá cómo los monads pueden ser utilizados para manejar efectos secundarios y promesas de forma elegante, y cómo las functors y applicatives ofrecen una abstracción más general para manipular datos.

## Ejercicio
Implemente una función en Haskell que use map y filter para procesar una lista de números enteros. La función debe filtrar los números pares e incrementar cada uno en 10, finalmente devolviendo la suma total del nuevo conjunto de números.

```haskell
import Data.List

sumIncrementedEvens :: [Int] -> Int
sumIncrementedEvens xs = sum (map (\x -> x + 10) (filter even xs))
```

## Resumen
- Se profundiza en el uso de funciones puras y patrones de diseño avanzados.
- Se exploran técnicas como map, filter y reduce para manipular datos eficientemente.
- Los monads se presentan como una herramienta poderosa para manejar efectos secundarios.