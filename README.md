# 👥 HR Analytics: Estrategias de Retención y Clima Laboral

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 🎯 Objetivo del Proyecto
Este proyecto analiza los factores clave que impulsan la rotación de personal (Attrition) en una organización de 1,470 empleados. El objetivo es identificar patrones de fuga de talento y evaluar el bienestar laboral para proponer acciones preventivas basadas en datos.

## 🖼️ Vista Previa del Dashboard
| Resumen Ejecutivo | Análisis de Rotación |
| :---: | :---: |
| ![Resumen Ejecutivo](Resumen_Ejecutivo.png) | ![Análisis de Rotación](Analisis_de_Rotacion.png) |

| Clima y Desempeño 
| :---: | :---: |
| ![Clima y Desempeño](Clima_y_Desempeño.png) 

## 📊 Estructura del Dashboard (5 Páginas)
El reporte está dividido en 5 vistas estratégicas interconectadas:

1. **Resumen Ejecutivo:** Vista macro de la empresa con KPIs de Tasa de Rotación (16.12%) y demografía general.
2. **Análisis de Rotación:** Profundización en las bajas por departamento (destacando Sales/Ventas) y su relación con el equilibrio vida-trabajo.
3. **Clima y Desempeño:** Análisis de satisfacción (Promedio: 2.73/4) vs. evaluación de desempeño y métricas de capacitación anual.
4. **Lealtad y Liderazgo:** Evaluación del impacto que tienen los años bajo el mismo jefe y el tiempo desde el último ascenso en la renuncia de empleados.
5. **Perfil del Talento:** Relación entre el nivel educativo, área de estudio y rangos salariales.

## 💡 Hallazgos Principales (Insights)
* **Punto de Quiebre de Salarios:** Se detectó una nube de puntos crítica en el gráfico de dispersión donde empleados con alta experiencia (10-20 años) mantienen salarios bajos, aumentando su probabilidad de renuncia.
* **El Factor Bienestar:** Los empleados con "Bajo" equilibrio vida-trabajo presentan una tasa de rotación significativamente superior al promedio general (aprox. 23%).
* **Cruce de Satisfacción:** En el área de Ventas, a pesar de tener evaluaciones de desempeño sólidas, la satisfacción ambiental es la más baja, sugiriendo un ambiente de alta presión.
* **Impacto Educativo:** Los perfiles con formación técnica muestran una rotación más acelerada en comparación con niveles de doctorado o maestría.

## 🛠️ Tecnologías Utilizadas
* **Python (Pandas/Matplotlib):** Limpieza, traducción de datos y análisis exploratorio inicial.
* **Power BI Desktop:** Modelado de datos, creación de medidas DAX avanzadas y diseño de interfaz de usuario (UI/UX).
* **DAX:** Implementación de medidas para Tasa de Attrition y promedios de satisfacción escalados.

## 🚀 Cómo utilizar este repositorio
1. Descarga el archivo `.pbix` ubicado en la carpeta raíz o `/Dashboards`.
2. Revisa el archivo de datos limpio en `/Data/HR_Analytics_Limpio.csv`.
3. El script de procesamiento original se encuentra en `/Scripts/Cleaning_Process.ipynb`.

---
✨ **Análisis desarrollado por [Tu Nombre]** *¿Te interesa este análisis? ¡Conectemos en LinkedIn!*
