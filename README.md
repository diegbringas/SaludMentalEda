# Análisis de Datos: Impacto del Trabajo Remoto en la Salud Mental

Este proyecto analiza cómo el trabajo remoto afecta la salud mental de los empleados, utilizando un conjunto de datos detallados. Los resultados son útiles para investigadores, profesionales de recursos humanos y empresas que desean mejorar sus políticas laborales.

## Objetivo

El análisis tiene como objetivo identificar tendencias relacionadas con:
- Niveles de estrés.
- Equilibrio entre vida laboral y personal.
- Satisfacción laboral.
- Influencia del entorno laboral (remoto, híbrido, presencial).

## Descripción del Conjunto de Datos

El conjunto de datos contiene información sobre 5,000 empleados, con las siguientes características:
- **Edad**, **Género**, **Industria**, **Rol laboral**, entre otras.
- Factores relacionados con la salud mental, como:
  - Nivel de estrés.
  - Condición de salud mental (ansiedad, depresión, etc.).
  - Acceso a recursos de salud mental.
  - Actividad física y calidad del sueño.

### Exploración de Datos Inicial

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Cargar datos
df = pd.read_csv('Impact_of_Remote_Work_on_Mental_Health.csv')

# Resumen inicial
print(df.info())
print(df.describe())
