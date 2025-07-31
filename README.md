# Innovate - Análisis de Proyectos por Departamento

Este proyecto realiza un análisis visual de la cantidad de contratos de ejecución de proyectos en el Perú, agrupados por departamento. Utiliza Python, pandas y matplotlib para transformar los datos en gráficos comprensibles que facilitan la interpretación regional de la información.

## Descripción

A partir del dataset `proyectos_ejecucion_20230706.csv`, el notebook realiza:

- Carga y limpieza de datos con pandas.
- Agrupación de los datos por departamento.
- Cálculo de la cantidad de contratos ejecutados por región.
- Visualización de los resultados mediante gráficos de barras usando matplotlib.

## Estructura del proyecto

├── Innovate.ipynb - Notebook principal con el análisis de datos

├── proyectos_ejecucion_20230706.csv - Dataset necesario 

├── README.md - Documentación del proyecto 

## Requisitos

- Python 3.8 o superior  
- pandas  
- matplotlib  

## Instalación de dependencias

pip install pandas matplotlib

## Cómo usar

1. Clona este repositorio:

git clone https://github.com/AndreAH2207/Proyectos-ProInnovate.git
cd Proyectos-ProInnovate

2. Coloca el archivo `proyectos_ejecucion_20230706.csv` en el mismo directorio que el notebook.

3. Abre el notebook en Jupyter:

jupyter notebook Innovate.ipynb

4. Ejecuta las celdas para generar los análisis y visualizar los gráficos.
