
Portafolio de Dashboards – Power BI

Este repositorio reúne una colección de dashboards desarrollados en Power BI como parte de un portafolio profesional orientado al análisis de datos, modelado, visualización y creación de indicadores de negocio. Cada proyecto incluye la estructura del modelo de datos, métricas DAX, diseño visual y construcción de reportes interactivos.

El portafolio está organizado en dos proyectos principales:

- People Analytics Dashboard  
- Sales Dashboard

Las imágenes y el código utilizado para cada dashboard se encuentran disponibles en las carpetas correspondientes dentro de este repositorio.

---

People Analytics Dashboard

Dashboard diseñado para el análisis de Recursos Humanos, con enfoque en rotación, satisfacción laboral, horas extra, perfiles de empleado y métricas clave de People Analytics. El proyecto incluye modelado de datos, creación de KPIs, columnas calculadas, storytelling visual y tres páginas:

1. Overview  
Incluye métricas generales como empleados totales, attrition, ingresos promedios, satisfacción laboral, antigüedad, y gráficas por departamento, rol, work-life balance y seniority.

2. Attrition Analysis  
Presenta análisis detallado de rotación por edad, salario, rol, satisfacción, balance vida–trabajo, entre otros factores asociados.

3. Employee Profile  
Describe la composición del personal por nivel educativo, género, estado civil, rango de edad, campo de estudio y variables cualitativas relacionadas con satisfacción, ambiente laboral y job involvement.

Las imágenes de este proyecto se encuentran en:
images/people_analytics_dashboard/

---

Sales Dashboard

Dashboard orientado al análisis de ventas, ingreso, ticket promedio, productos vendidos y transacciones. Está construido sobre un modelo en estrella compuesto por:

- Tabla de hechos: fact_ventas  
- Dimensiones: dim_tiendas, dim_productos y dim_calendario  

Se crearon medidas DAX para ingresos, productos vendidos, ticket promedio y métricas comparativas contra el mes anterior. El dashboard está dividido en dos páginas:

1. Reporte de Ingresos  
Incluye: ingresos totales del mes seleccionado, comparación con el mes anterior, ticket promedio, productos vendidos, transacciones, ingresos por tienda, ingresos por categoría, tendencia diaria de ingresos y unidades vendidas.

2. Reporte de Productos  
Incluye: ingresos por producto segmentados por tienda, ingresos de las tiendas por categoría, tabla detallada con SKU, producto, categoría, ingresos y unidades vendidas, y treemap con los productos de mayor ingreso.

Las imágenes de este proyecto se encuentran en:
images/sales_dashboard/

---

Visualización en GitHub Pages  
La versión publicada del portafolio puede consultarse en el siguiente enlace:
https://github.com/christoforo13/christopher_cumi.github.io

---

Estructura del Repositorio
/
├── index.html
├── README.md
└── images/
      ├── people_analytics_dashboard/
      └── sales_dashboard/

---

Autor  
Christopher Cumi Llanes  
Portafolio orientado a análisis de datos, modelado, visualización y soluciones de negocio con Power BI.
