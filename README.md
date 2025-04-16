# Figuras Geométricas - Cálculo de Áreas

## Propósito del repositorio
Este repositorio contiene una implementación en Python que permite representar diferentes figuras geométricas (como **rectángulos**, **triángulos** y **círculos**) y calcular el área de cada una de ellas. El proyecto está diseñado utilizando **herencia de clases abstractas** para promover la reutilización de código, implementando la interfaz común `calcular_area()` para todas las figuras.

El objetivo principal es proporcionar una forma organizada y reutilizable de trabajar con cálculos de áreas para distintas figuras geométricas.

## Cambios realizados
A continuación se detallan las correcciones y mejoras realizadas en el código:

1. **Corrección en el nombre del archivo**: Se cambió el nombre del archivo para seguir la convención de nombres en minúsculas y con guiones bajos (**snake_case**).
   
2. **Corrección de los nombres de las variables globales**: Se ajustaron los nombres de las variables globales para cumplir con el estándar **UPPERCASE** según **PEP 8** (por ejemplo, `BASE_RECTANGULO` en lugar de `base_rectangulo`).

3. **Espaciado en los operadores**: Se corrigió el espaciado alrededor de los operadores matemáticos y de asignación para mejorar la legibilidad, siguiendo las recomendaciones de **PEP 8**.

4. **Añadidos docstrings a clases y métodos**: Se agregaron comentarios dentro de las clases y métodos para describir su propósito. Esto mejora la documentación y comprensión del código.

5. **Refactorización de la clase `FiguraGeometrica`**: Se añadió un nuevo método `tipo_figura()` en la clase abstracta para devolver el tipo de figura. Esto aumenta la reutilización del código y la consistencia en las clases hijas.

6. **Método adicional en `Rectangulo`**: Se añadió el método `mostrar_propiedades()` en la clase `Rectangulo` para mostrar la base y altura del rectángulo, mejorando la funcionalidad de la clase.

7. **Revisión de nombres de clases y métodos**: Se corrigieron los nombres de las clases y métodos para asegurar que cumplieran con las convenciones de **CamelCase** y **snake_case**.

8. **Eliminación de sentencias `pass` innecesarias**: Se eliminó la sentencia `pass` de métodos en la clase `FiguraGeometrica` que no lo requerían, ya que la implementación del método `calcular_area` en las clases hijas lo hacía redundante.

## Integrantes del equipo

| Apellidos      | Nombres            |
|----------------|--------------------|
| Inciso Aguilar | Elizabeth Antonela |

