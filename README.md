# Análisis de los datos de ventas para una empresa de servicios tecnológicos
El presente proyecto comprende un análisis de datos general o inicial para una empresa dedicada a brindar soluciones tecnológicas. El enfoque principal es comparar las ventas de los años 2022 y 2023, evaluando su desempeño en tres ciudades clave: Osaka, Tokyo y Yokohama. Además, se identifican tendencias y patrones generales, con el objetivo de proporcionar información valiosa para la toma de decisiones.

## Fuentes de Datos:

Los datos utilizados en este proyecto provienen del repositorio de Sven Bosau en GitHub.

Dataset Original: https://github.com/Sven-Bo/datasets/tree/master

El conjunto de datos incluye 1,730 registros con las siguientes columnas:

- order_id: Identificador único del pedido.

- product_id: Identificador único del producto.

- store_id: Identificador único de la tienda.

- product_name: Nombre del producto.

- product_category: Categoría del producto.

- city: Ciudad donde se realizó la venta.

- date_of_sale: Fecha de la venta.

- quantity_sold: Cantidad vendida.

- sales_amount: Importe total de la venta.


## Procesamiento de Datos:

### Transformaciones Realizadas

- Conversión de Tipos de Datos: La columna date_of_sale se transformó al formato datetime.

- Extracción de Mes y Año: Se crearon columnas adicionales para analizar patrones temporales.

- Agrupaciones: Se calcularon ventas totales por ciudad, mes, año y categoría.

- Cálculo de Cambios Porcentuales: Se estimaron cambios porcentuales interanuales en ventas.

### Análisis Realizado

1. Ventas Totales por Ciudad:
   - Osaka y Yokohama mostraron un crecimiento general en 2023.
   - Tokyo tuvo una disminución del 9.06% en sus ingresos totales.

2. Tendencias Mensuales:
   - En Yokohama, los primeros meses de 2023 tuvieron un buen desempeño, pero hubo una caída significativa en la segunda mitad del año.
   - Osaka también presentó un patrón similar, con un destacado aumento en enero (+90%).
   - En Tokyo, las ventas disminuyeron significativamente en los últimos meses de 2023, afectando su desempeño general.

3. Análisis por Categoría:
   - Categorías como herramientas de desarrollo de software y tecnológicas mostraron crecimiento en general.
   - Productos creativos y educativos tuvieron desempeños mixtos, con algunas pérdidas en 2023.

## Conclusiones:

- Crecimiento Inicial en 2023: Las ciudades analizadas mostraron desempeños positivos en los primeros meses de 2023.

- Debilidad en la Segunda Mitad del Año: Las caídas en las ventas en la segunda mitad del año resaltan la necesidad de estrategias para estabilizar el rendimiento.

- Oportunidades de Mejora: Es crucial analizar factores internos y externos que afectan el desempeño en los últimos meses.

## Tecnologías Utilizadas

- Python:
  - Bibliotecas: pandas, matplotlib, numpy

- Jupyter Notebook: Para documentar y realizar el análisis.


