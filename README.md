# houses-data-analytics
Se hace el análisis de una base de datos de distintas viviendas acompañadas de variables tales como el aárea, cuartos, pisos, baños, etc, para seguido a esto llegar a conclusiones utiles para usuarios interesados en comprar como para usuarios interesados en vender propiedades, todo esto mediante diferntes metodos de exploracion y visualizacion.

# Proyecto de Análisis de Datos – Housing.csv

Este proyecto consiste en un análisis exploratorio y estadístico del dataset **Housing.csv**, proveniente de Kaggle, el cual contiene información de viviendas y sus características estructurales. El propósito es identificar patrones, relaciones entre variables y factores que influyen en el precio de las propiedades.

---

## Integrantes del equipo
- David Santiago Hernández Arandia
- Wendy Dayana Otalvaro Velasquez 
 
---

##  Estructura de los datos

El archivo **Housing.csv** contiene información sobre viviendas con las siguientes columnas principales:

- **price**: Precio de la vivienda.  
- **area**: Área construida.  
- **bedrooms**: Número de habitaciones.  
- **bathrooms**: Cantidad de baños.  
- **stories**: Número de pisos.  
- **parking**: Plazas de parqueadero.  

---

##  Diccionario de datos

| Variable     | Tipo      | Descripción |
|--------------|-----------|-------------|
| price        | numérica  | Precio total de la vivienda |
| area         | numérica  | Metros construidos |
| bedrooms     | numérica  | Número de habitaciones |
| bathrooms    | numérica  | Número de baños |
| stories      | numérica  | Número de pisos |
| parking      | numérica  | Espacios de parqueadero |

---

##  Instrucciones para ejecutar el notebook

1. Clonar el repositorio:
   ```bash
   git clone <https://github.com/iamdavidhdz/houses-data-analytics>
2. Instalar dependencias:
   pip install -r requirements.txt
3. Abrir el archivo .ipynb en Jupyter Notebook, VSCode o Google Colab.
4. Ejecutar las celdas en orden.

Conclusiones finales:

El área es la variable con mayor relación con el precio, mostrando que viviendas más grandes tienden a ser significativamente más costosas.

El mercado presenta precios concentrados en rangos medios, con pocas viviendas extremadamente costosas después del winsorizing.

Las características como baños, parqueaderos y número de pisos aportan al valor, pero su influencia es menor comparada con el área.

Los análisis de agrupación muestran que viviendas con más baños y parqueaderos presentan incrementos constantes en el precio, sugiriendo criterios claros de valoración.

La data evidencia que invertir en viviendas medianas puede ser más eficiente en retorno/costo que comprar propiedades demasiado grandes o lujosas.
