# Análisis Exploratorio del Impacto Ambiental de la Moda Rápida

Este proyecto contiene un análisis exploratorio de datos sobre el impacto ambiental de la industria de la moda rápida. Se trabaja con un conjunto de datos que incluye información sobre producción textil, consumo de ropa, emisiones de CO₂, uso de agua y generación de residuos por país, año y marca.

## Estructura del proyecto

```
FAST-FASHION-ANALYSIS/
├── data/
│   └── true_cost_fast_fashion.csv        # Archivo original con los datos
│
├── notebooks/
│   └── exploracion_fast_fashion.ipynb    # Análisis completo en Jupyter Notebook
│
├── environment.yml                       # Archivo con las dependencias del entorno
├── .gitignore                            # Para ignorar archivos y carpetas innecesarias
└── README.md                             # Descripción general del proyecto
```

## Objetivo

Explorar cómo diferentes marcas, países y años contribuyen al impacto ambiental de la industria textil, a partir de métricas como:

- Toneladas de ropa producidas
- Emisiones de carbono (tCO2e)
- Uso de agua (millones de litros)
- Residuos generados (toneladas)

## Herramientas utilizadas

- Python 3
- pandas
- numpy
- matplotlib

## Consultas realizadas

1. Países que más producen ropa
2. Promedio de emisiones de CO₂ por país
3. Países que generan más residuos textiles
4. Comparación de consumo entre países desarrollados y en desarrollo
5. Marcas que generan más CO₂ al año
6. Producción por país dentro de una marca específica
7. Evolución del impacto ambiental por año

## Cómo usar este proyecto

1. Clonar este repositorio.
2. Crear un entorno virtual con el archivo `environment.yml`:

```bash
conda env create -f environment.yml
conda activate fast-fashion-analysis
```

3. Abrir el archivo exploracion_fast_fashion.ipynb desde Jupyter Notebook o Visual Studio Code.

4. Ejecutar las celdas en orden para reproducir el análisis.

## Notas

Este proyecto se desarrolló con fines de aprendizaje, aplicando conceptos básicos de análisis de datos con pandas, numpy y matplotlib. Es un punto de partida para análisis más profundos con visualizaciones interactivas o modelos predictivos.