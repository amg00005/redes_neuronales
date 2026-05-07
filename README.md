# redes neuronales // tecnicas reunidas
Este proyecto recoge los fundamentos teóricos y estructurales de las redes neuronales artificiales, centrándose en el Perceptrón y el Multilayer Perceptron (MLP).
El objetivo principal es comprender cómo una neurona artificial evoluciona desde un modelo simple (perceptrón) hasta una arquitectura más potente (MLP) capaz de resolver problemas complejos no lineales.

🎯 Objetivos
Entender qué es un perceptrón y cómo funciona.
Analizar sus limitaciones (ej. problema XOR).
Comprender el concepto de multicapa (MLP).
Estudiar la estructura de una red neuronal:
Capa de entrada
Capa(s) oculta(s)
Capa de salida
Visualizar la arquitectura de una red neuronal.

🔹  Perceptrón
El perceptrón es una neurona artificial que:
Recibe entradas x
Las multiplica por pesos w
Suma un sesgo b
Aplica una función de activación
Fórmula:
y=σ(w Tx+b)
🔴 Limitación: solo resuelve problemas lineales (no puede resolver XOR).
🔹  Capas
🔵 Entrada: recibe los datos
🟡 Oculta: aprende patrones (clave para resolver problemas complejos)
🔴 Salida: da el resultado final
Perceptrón → solo separa con líneas rectas
MLP → puede aprender relaciones no lineales (ej. XOR)

El MLP mejora al perceptrón añadiendo capas ocultas, lo que permite resolver problemas complejos.
Es la base de muchas técnicas modernas de Deep Learning.
