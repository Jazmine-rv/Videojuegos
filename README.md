# Usuarios en una Plataforma de Videojuegos

Este proyecto forma parte de la materia **Procesamiento de Aprendizaje Automatico**.

## Descripción

El objetivo es aplicar un enfoque basado en reglas para clasificar las acciones que realizan los usuarios en una plataforma de videojuegos según su tipo y duración.

- Combate → Victoria o Derrota
- Exploración → Descubrimiento o Sin hallazgos
- Interacción social → Mensaje enviado

## Herramientas utilizadas

- Python


## Respuestas a las preguntas de reflexión

**1. ¿Qué reglas funcionaron mejor para clasificar las acciones?**

Las reglas basadas en la duración de la acción funcionaron bien para distinguir entre resultados como Victoria o Derrota en combate, y entre Descubrimiento o Sin hallazgos en exploración.
También la acción Interacción social fue sencilla de clasificar, ya que siempre conduce a un mismo tipo de resultado.

**2. ¿Qué limitaciones tiene este enfoque basado en reglas?**
- Rigidez: Las reglas son fijas y no se adaptan a nuevos patrones
- Complejidad limitada: No puede capturar relaciones complejas entre variables
- Mantenimiento difícil: Agregar nuevas reglas puede crear conflictos
- No aprende: No mejora con más datos
- Escalabilidad pobre: Con muchas variables, el número de reglas crece exponencialmente

**3. ¿Cómo se podría mejorar la clasificación utilizando modelos de machine learning más avanzados?**

Podría entrenarse un modelo de clasificación supervisado (por ejemplo, Árbol de Decisión) utilizando un conjunto de datos más grande.
El modelo aprendería automáticamente los patrones reales de comportamiento, logrando:
- Mayor precisión y adaptabilidad.
- Clasificación basada en probabilidades en lugar de reglas fijas.
- Capacidad para generalizar a nuevos tipos de usuarios o acciones.

## Archivos

- `README.md`: Este es un archivo descriptivo.
- `Videojuegos.py`: Contiene el código en Python.
