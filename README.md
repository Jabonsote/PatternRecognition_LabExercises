# PatternRecognition_LabExercises

Repositorio de prácticas de la asignatura Reconocimiento de Patrones.

## Estructura

- `HMM/HAR_HMM.ipynb`: Implementación de un modelo oculto de Márkov (HMM) para reconocimiento de actividades humanas (HAR) en el dataset UCI HAR.

## Resumen de la práctica HMM/HAR_HMM.ipynb

- Selección de características por información mutua (MI) → reducción de 561 a 50 variables.
- Extracción de secuencias por sujeto (bloques continuos de misma actividad).
- Entrenamiento de un HMM Gaussiano (3 estados, covarianza diagonal) por cada una de las 6 actividades.
- Validación Leave‑One‑User‑Out (LOUO) con 30 sujetos.
- Métricas: precisión global 89.25%, F1‑score macro 89.26%, media por sujeto 89.56% ± 0.0928.

## Licencia

MIT License – uso libre, atribución no requerida.
