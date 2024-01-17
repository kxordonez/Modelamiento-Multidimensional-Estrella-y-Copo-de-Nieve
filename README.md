# Modelamiento-Multidimensional-Estrella-y-Copo-de-Nieve
En este proyecto, nos propusimos mejorar la eficiencia y el rendimiento de la base de datos Northwind, una base de datos pública que simula la gestión de una tienda de productos, mediante la implementación de técnicas de modelado de estrella y copo de nieve en SQLite.
A partir de la base de datos denominada “Northwind” se generó los modelos de negocio el esquema estrella y el esquema de copo de nieve.
Ejemplos prácticos en los que se implementa un modelo multidimensional haciendo uso del esquema en estrella y copo de nieve. 
Para el modelo en estrella se realiza un proceso ETL extrayendo los datos desde la base de datos “Northwind”.
Para la implementación del modelo de copo de nieve se dice que este se deriva del esquema en estrella implementado, 
ya que su función es normalizar un esquema en estrella. Los dos esquemas implementados cumplen diferentes funcionalidades que los caracteriza. 

Optimización de la Estructura de Datos:

Reorganizar la estructura de la base de datos Northwind utilizando el modelo de estrella y copo de nieve para reducir redundancias y mejorar la eficiencia en la recuperación de datos.
Mejora del Rendimiento de Consultas:

Aplicar índices y claves primarias y foráneas de manera estratégica para acelerar el proceso de recuperación de datos y reducir el tiempo de ejecución de las consultas.
Facilitar el Mantenimiento:

Dividir las tablas en esquemas más normalizados para facilitar la administración y el mantenimiento a largo plazo de la base de datos.
Metodología y Herramientas:

Modelado de Estrella y Copo de Nieve:

Identificación de entidades centrales y auxiliares para construir un modelo de estrella y copo de nieve que reduzca la redundancia y mejore la organización de los datos.
SQLite:

Utilización de SQLite como sistema de gestión de base de datos, aprovechando su ligereza y capacidad de implementar técnicas avanzadas de modelado.
Normalización:

Aplicación de técnicas de normalización para eliminar redundancias y asegurar la integridad de los datos.
