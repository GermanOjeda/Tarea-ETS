# Casos de uso Biblioteca

## Actores
---
|   **Actor**   |         Usuario            |
|---------------|----------------------------|
| Descripción   | La supuesta persona que va a la biblioteca |
| Características | Puede devolver un libro y buscarlo |
| Relaciones | Se relaciona con el actor de Bibliotecario |
| Referencias | Casos de usos: Devolver Libro, Buscar Libro |
| Autor | Germán Ojeda |


|   **Actor**   |         Bibliotecario            |
|---------------|----------------------------|
| Descripción   | La supuesta persona que trabaja en la biblioteca |
| Características | Puede prestar un libro y buscarlo |
| Relaciones | Se relaciona con el actor de Usuario |
| Referencias | Casos de usos: Prestar Libro, Buscar Libro |
| Autor | Germán Ojeda |


## Casos De Uso
---

|   **Nombre del caso de uso**   |           Prestar Libro          |
|---------------|----------------------------|
| Actor Primario | Bibliotecario |
| Precondiciones | El usuario tiene que estar registrado en el sistema. El libro tiene que estar disponible para ser prestado |
| Flujo Principal | El usuario busca un libro. El usuario solicita el prestamo del mismo. El bilbiotecario verifica si el libro está disponible para el prestamo. Se registra el prestamo en el sistema y al usuario se le presta el libro. |

|  **Nombre de caso de uso**  |       Devolver libro      |
|------------|-------------------------|
|Actor Primario| Usuario |
|Actor Secundario| Bibliotecario |
|Precondiciones| El usuario tiene que tener un préstamo en curso.|
|Flujo Principal|El usuario devuelve el libro al bibliotecario. El bibliotecario verifica el estado del libro al ser devuelto. La devolución es registrada en el sistema.|

|  **Nombre de caso de uso**  |         Buscar libro          |
|---------|-------------------------|
| Actor Primario | Usuario |
| Actor Secundario | Bibliotecario |
| Precondiciones | La base de datos de los libros está actualizada y es accesible. |
| Flujo Principal | El usuario mira al catálogo de la biblioteca. Realiza la búsqueda por título, autor, género u otros criterios de busqueda. Mira los resultados y elige un libro para más detalles. |