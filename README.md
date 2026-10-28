# Algoritmo Genético para Optimización de Funciones Multimodales

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Institución](https://img.shields.io/badge/TESI-Ingeniería%20en%20Sistemas-red.svg)](https://www.tesi.org.mx/)

Proyecto integrador correspondiente al **Segundo Parcial** de la materia de **Algoritmos Evolutivos**, enfocado en la investigación teórica de paradigmas y la implementación práctica de un Algoritmo Genético (AG) en Python[cite: 1, 2, 3].

---

## Descripción del Proyecto

El repositorio contiene el desarrollo completo de la evaluación basada en competencias de las **Unidades 2 y 3** ("Del Paradigma a la Implementación: Cómputo Evolutivo y Algoritmos Genéticos"):
1. **Investigación Comparativa:** Cuadro comparativo entre Estrategias Evolutivas (EE), Programación Evolutiva (PE) y Algoritmos Genéticos (AG), acompañado de una tabla de decisión fundamentada.
2. **Componentes del AG:** Desglose formal de los operadores de representación, selección (ruleta), cruce (un punto), mutación (bit-flip) y evaluación de aptitud, con un ejemplo numérico resuelto paso a paso.
3. **Implementación Práctica (`ag_optimizacion.py`):** Código ejecutable y modular para maximizar la función multimodal $f(x) = x \cdot \sin(10\pi x) + 1.0$ en el rango $[-1, 2]$, configurable mediante un archivo externo `config.json`[cite: 2].
4. **Experimentación y Convergencia:** Análisis estadístico evaluando 4 configuraciones con 5 repeticiones independientes por semilla aleatoria (promedio y desviación estándar).
5. **Artículo Técnico:** Paper corto integrado con los resultados empíricos y teóricos del proyecto[cite: 3].


