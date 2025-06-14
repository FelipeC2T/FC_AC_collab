# Nombre del Proyecto

Este es un proyecto de ciencia de datos en colaboración con [nombre del compañero]. Aquí analizamos [breve descripción del objetivo del proyecto].

## 🧱 Estructura del repositorio

- `data/`: contiene los datasets (no subir datos privados).
- `notebooks/`: notebooks con análisis exploratorio y pruebas.
- `src/`: scripts Python organizados por función.
- `tests/`: pruebas para el código.
- `requirements.txt`: librerías necesarias para reproducir el entorno.

## 🚀 Cómo empezar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/nombre-del-repo.git


 # Clasificación de Facies a partir de Datos de Pozo

Este proyecto busca aplicar modelos de machine learning para clasificar facies geológicas a partir de registros de pozo. Contamos con un dataset de aproximadamente 4000 filas y 9 variables por pozo, incluyendo propiedades petrofísicas.

## 📊 Variables esperadas

- Profundidad
- Gamma Ray (GR)
- Resistividad
- Densidad
- Porosidad
- SP (Potencial espontáneo)
- Neutrón
- Sonic
- Facies (target)

## 🎯 Objetivo

Entrenar y evaluar modelos de clasificación supervisada para predecir la facies geológica en función de las propiedades medidas.

## 🔧 Posibles modelos

- Random Forest
- Support Vector Machine
- XGBoost
- Redes neuronales
- KNN

## 🚧 Próximos pasos

- [ ] Limpieza de datos
- [ ] Análisis exploratorio (EDA)
- [ ] Preparación de features
- [ ] Entrenamiento de modelos
- [ ] Evaluación con métricas (F1, accuracy, confusion matrix)
