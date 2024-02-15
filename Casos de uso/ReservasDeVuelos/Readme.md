# Casos de Uso Reserva de Vuelos

## Casos de uso
---
## Reservar Vuelo

   |Nombre de caso de uso| Reservar Vuelo |
   |-|-|
   |Actores|Pasajero, Agente de Reservas|
   |Precondiciones| El sistema tiene que estar en línea para el uso.|
   |Flujo Principal| El pasajero o agente de reservas inicia la sesión en el sistema de reservas. El pasajero o agente de reservas busca los vuelos disponibles. El sistema expone la lista de vuelos disponibles. El pasajero o agente de reservas elige el vuelo deseado. El sistema muestra los detalles del vuelo. Se confirma la reserva del vuelo. El sistema afirma la reserva del vuelo y da el número de confirmación. |
   |Flujo alternativo| Si el pasajero o agente de reservas no dispone de una cuenta se le dará la opción de crearla. Si no hay vuelos que estén disponibles, el sistema enviará un mensaje de error al usuario. Si el pasajero o agente cancela la reserva, el sistema cancelará la reserva y enviará un mensaje de confirmación.|

## Buscar Vuelo

   |Nombre de caso de uso| Buscar Vuelo |
   |-|-|
   |Actores| Pasajero|
   |Precondiciones| El sistema tiene que estar en línea y disponible el uso. |
   |Flujo Principal| El pasajero inicia su cuenta en el sistema de reservas. El pasajero busca los vuelos que estén disponibles. El sistema muestra la lista de dichos vuelos. |
   |Flujo alternativo| Si el pasajero no dispone de una cuenta, se le dará la opción de crear una. Si no hay vuelos disponibles, el sistema enviará un mensaje de error al usuario.|

## Cancelar Reserva

   |Nombre de caso de uso| Cancelar Reserva |
   |-|-|
   |Actores| Pasajero, Agente de Reservas|
   |Precondiciones| El sistema tiene estar en línea y disponible para el uso.|
   |Flujo Principal|El pasajero o agente inicia su cuenta en el sistema. El pasajero o agente elige la reserva que quiera cancelar. El sistema enseña los detalles de la reserva. El pasajero o agente afirma la cancelación de su reserva. El sistema cancela dicha reserva y envia un mensaje de confirmación.|
   |Flujo alternativo|  Si el pasajero o agente no tiene una cuenta, se le dará la opción de crear una. Si no hay reservas existentes, el sistema enviará un mensaje de error. Si el pasajero o agente decide no cancelar la reserva, el sistema no tendrá acción alguna. |


## Actores
---

## Pasajero

   |Nombre actor| Pasajero |
   |-|-|
   |Descripcion| El pasajero es el usuario del sistema que busca y reserva los vuelos. |
   |Caracteristicas| Puede buscar vuelos, puede reservar vuelos y cancelar reservas existentes. |
   |Relaciones| Cancelar Reserva, Buscar Vuelo y Reservar Vuelo. |

## Agente de Reservas

   |Nombre actor| Agente de Reservas |
   |-|-|
   |Descripcion|El agente de reservas es el usuario del sistema que busca y reserva los vuelos en nombre de otros pasajeros. |
   |Caracteristicas| Puede buscar vuelos disponibles, reservarlos en nombre de los pasajeros y cancelar reservas existentes. |
   |Relaciones|Cancelar Reserva y Reservar Vuelo. |


