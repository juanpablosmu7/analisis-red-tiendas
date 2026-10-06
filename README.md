# Análisis de la red de tiendas RetailNow

Este proyecto corresponde al Trabajo 3 de análisis de datos con Python. El objetivo es trabajar con datos de una cadena ficticia de tiendas utilizando Pandas y NumPy.

A partir de tres archivos CSV se analizan las ventas, el inventario disponible y la satisfacción de los clientes. Todo el desarrollo está realizado en un Jupyter Notebook para poder separar el trabajo por apartados y mostrar los resultados de cada análisis de forma clara.

## Archivos del proyecto

- `analisis_red_tiendas.ipynb`: notebook principal con todo el análisis.
- `sales.csv`: datos de ventas.
- `inventories.csv`: datos de inventario.
- `satisfaction.csv`: datos de satisfacción de clientes.

## Qué se analiza

En el notebook se realizan, entre otras, las siguientes operaciones:

- carga y limpieza de los CSV con Pandas;
- ventas totales por producto y por tienda;
- ingresos totales por tienda;
- resumen estadístico de las ventas;
- rotación del inventario;
- detección de inventarios críticos;
- análisis de satisfacción del cliente;
- mediana y desviación estándar con NumPy;
- simulación de ventas futuras utilizando números aleatorios y una semilla reproducible.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Visual Studio Code

## Ejecución

El ejercicio solicita utilizar estas rutas absolutas:

```text
/workspace/sales.csv
/workspace/inventories.csv
/workspace/satisfaction.csv
```

Por ello, los tres CSV deben encontrarse en `/workspace` cuando se ejecute el notebook en el entorno de evaluación.

Una vez colocados los archivos en esa ubicación, basta con abrir `analisis_red_tiendas.ipynb` y ejecutar las celdas en orden.

## Observación

Los datos proporcionados no incluyen una columna de categorías de producto. Por ese motivo no se ha inventado ninguna clasificación y el análisis por categoría indicado como opcional en el enunciado no se realiza.
