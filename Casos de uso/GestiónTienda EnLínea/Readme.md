# Casos de Uso Sistema de Tienda en linea

## Casos de uso
---

## Ver Catálogo

   |Nombre de caso de uso| Ver Catálogo |
   |-|-|
   |Actor Primario| Cliente |
   |Descripcion| El cliente mira los productos disponibles del catálogo de la tienda. |
   |Flujo Principal| El cliente abre la página del catálogo y el sistema expone los productos disponibles. |

## Realizar Compra

   |Nombre de caso de uso| Realizar Compra |
   |-|-|
   |Actor Primario| Cliente |
   |Descripcion| El cliente elije los productos que desee del catálogo, los añade a su lista de compra y los adquiere.|
   |Flujo Principal| El cliente elije un producto del catálogo. El cliente añade el producto a su lista de compra. El cliente mira los productos en su lista. El cliente adquiere sus productos. El sistema confirma la adquisición. |

## Gestionar Inventario

   |Nombre de caso de uso| Gestionar Inventario |
   |-|-|
   |Actor Primario| Administrador |
   |Descripcion| El administrador añade, elimina o modifica productos en el catálogo.|
   |Flujo Principal| El administrador abre la página para gestionar el inventario. El administrador añade, elimina o modifica un producto del inventario. El administrador prosigue con la acción elegida anteriormente. El sistema confirma la acción. |

## Actores


## Cliente

|Nombre actor|Cliente|
|-|-|
|Descripcion| Este actor puede visualizar el catálogo de productos y hacer compras. |
|Caracteristicas| Puede elegir productos, añadirlos a un lista de compra y realizar la compra.|
|Relaciones| Realizar Compra y Ver Catálogo |


### 2. Administrador

|Nombre actor|Administrador|
|-|-|
|Descripcion| Este actor tiene la posibilidad de gestionar el inventario. |
|Caracteristicas| Puede añadir, eliminar o modificar productos en el catálogo. |
|Relaciones| Gestionar Inventario |
