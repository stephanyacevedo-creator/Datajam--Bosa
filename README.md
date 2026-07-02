# 1. Datajam--Bosa
análisis de datos abiertos para identificar puntos críticos de disposición inadecuada de residuos sólidos en la localidad de Bosa mediante Python, Google Colab y Power BI.
# 2. Fuentes de datos utilizadas
Portal de Datos Abiertos de Bogotá: Datasets oficiales con reportes sobre la gestión de residuos urbanos, hogares y puntos críticos específicos de la localidad de Bosa.
# 3. Metodología general
El proyecto integró herramientas de analítica y BI mediante el siguiente flujo:
1. rocesamiento y Análisis: Uso de Python en **Google Colab** para la limpieza, tratamiento de datos nulos, filtrado geográfico por Bosa y análisis exploratorio inicial.
2. Modelado y Visualización: Importación de los datos limpios a **Power BI** para configurar un modelo de datos robusto y diseñar un tablero interactivo con indicadores estadísticos y geoespaciales.
# 4. Estructura del repositorio
* `/data`: Contiene los archivos originales (Excel/CSV) descargados directamente del Portal de Datos Abiertos de Bogotá que sirvieron como insumo técnico.
* `/notebooks`: Contiene el archivo `Analisis 1.ipynb` con todo el desarrollo, limpieza y código documentado en Python.
* `/outputs`: Contiene el archivo `.pbix` correspondiente al dashboard final interactivo desarrollado en Power BI.
# 5. Instrucciones de ejecución
1. **Código:** Puede revisar el proceso de limpieza y análisis analítico abriendo directamente el archivo dentro de la carpeta `/notebooks`.
2. **Tablero:** Para interactuar con los gráficos, filtros y mapas, descargue el archivo guardado en la carpeta `/outputs` y ejecútelo localmente utilizando la aplicación *Power BI Desktop*.
