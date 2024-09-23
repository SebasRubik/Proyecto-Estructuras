# Proyecto-Estructuras: Simulación del Software del Rover Curiosity

Este proyecto es una simulación del software utilizado por el rover Curiosity de la NASA. A través del uso de estructuras de datos como árboles y grafos, se simula el movimiento y almacenamiento de información del rover en su misión de explorar la superficie marciana.

## Descripción del Proyecto

El rover Curiosity es un vehículo explorador desarrollado por la NASA cuya misión principal es buscar condiciones favorables para la vida en Marte. En este proyecto, replicamos la funcionalidad del software que controla el movimiento y la recolección de datos de interés del rover utilizando estructuras de datos como árboles y grafos.

### Funcionalidades

1. **Cargar Comandos y Elementos**:
   - Cargar y administrar comandos de desplazamiento y análisis.
   - Cargar puntos de interés encontrados en el terreno marciano.

2. **Agregar Comandos y Elementos**:
   - Agregar nuevos comandos de movimiento y análisis.
   - Agregar nuevos elementos o puntos de interés en el terreno.

3. **Simulación de Comandos**:
   - Simular el desplazamiento del rover según los comandos cargados.
   - Validar la nueva posición del rover tras la ejecución de los comandos.

4. **Planeación de Desplazamientos**:
   - Utilizar árboles para almacenar la información de los puntos de interés.
   - Planificar desplazamientos sobre la base de las ubicaciones de los puntos de interés.

5. **Creación de Mapas y Búsqueda de Rutas**:
   - Generar un mapa de conexiones entre los puntos de interés utilizando grafos.
   - Encontrar la ruta más larga entre dos puntos de interés en el mapa generado.

### Componentes Principales

- **Estructuras de datos utilizadas**:
  - Listas para almacenar comandos y elementos.
  - Árboles (QuadTree) para almacenar información geográfica.
  - Grafos para representar la conectividad entre puntos de interés.

- **Comandos**:
  - `cargar_comandos`: Cargar comandos de un archivo.
  - `cargar_elementos`: Cargar elementos de un archivo.
  - `agregar_movimiento`: Agregar un nuevo comando de movimiento.
  - `agregar_analisis`: Agregar un nuevo comando de análisis.
  - `simular_comandos`: Simular la ejecución de los comandos cargados.
  - `crear_mapa`: Crear un mapa de conexiones entre los puntos de interés.
  - `ruta_mas_larga`: Encontrar la ruta más larga en el mapa generado.

### Requerimientos del Proyecto

- Lenguaje de programación: C++
- Librerías:
  - Standard Template Library (STL) para manejo de listas y vectores.
  - Librerías personalizadas para la implementación de grafos y árboles.

##Conclusión
Este proyecto demuestra cómo el uso de estructuras de datos eficientes puede emular el software del rover Curiosity de la NASA, mostrando la importancia de las estructuras de datos tanto lineales como no lineales en la resolución de problemas complejos.


