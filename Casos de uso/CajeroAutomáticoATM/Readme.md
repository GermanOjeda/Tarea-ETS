# Casos de Uso Cajero ATM

## Casos de uso
---

## Login

   |Nombre de caso de uso| Hacer login |
   |-|-|
   |Actor Primario| Administrador, Cliente bancario|
   |Descripcion|  El actor pone sus credenciales para acceder al sistema. |
   |Flujo Principal|El actor selecciona el login. El sistema pide los datos del actor. El actor introduce sus datos. El sistema valida los datos y concede el acceso.|

## Hacer la transferencia

   |Nombre de caso de uso| Realizar transferencia  |
   |-|-|
   |Actor Primario| Administrador, Cliente bancario|
   |Descripcion| El actor realiza una transferencia a otra cuenta. |
   |Flujo Principal|El actor selecciona la opción de la transferencia. El sistema pide los detalles de la transferencia. El actor pone los detalles de la transferencia. El sistema realiza la transferencia.|

## Ingresar dinero

   |Nombre de caso de uso|Ingresar dinero |
   |-|-|
   |Actor Primario|Administrador, Cliente bancario |
   |Descripcion|El actor deposita dinero en su cuenta.|
   |Flujo Principal|El actor usa la opción de ingresar dinero. El sistema pregunta por la cantidad a depositar. El actor introduce la cantidad. El sistema realiza el depósito.|

## Ver saldo

   |Nombre de caso de uso| Ver saldo|
   |-|-|
   |Actor Primario| Administrador, Cliente bancario |
   |Descripcion|El actor consulta el saldo de su cuenta. |
   |Flujo Principal|El actor elige la opción de ver saldo. El sistema enseña el saldo de la cuenta.|



## Poner dinero al móvil

   |Nombre de caso de uso| Poner dinero al móvil |
   |-|-|
   |Actor Primario|Administrador, Cliente bancario |
   |Descripcion| El actor añade el saldo en el móvil. |
   |Flujo Principal|El actor elige la opción de añadir dinero a su dispositivo. El sistema pida la cantidad con la que recargar y el número de teléfono. El actor introduce la cantidad a recargar y el número de teléfono. El sistema realiza la recarga.|


# Actores


## Administrador

|Nombre actor|Administrador|
|-|-|
|Descripcion| Es el actor que gestiona y mantiene el sistema del cajero. |
|Caracteristicas| Tiene acceso completo al sistema y puede realizar todas las operaciones posibles.|
|Relaciones| Hacer login, Realizar transferencia, Ver saldo, Ingresar dinero y Poner dinero al móvil|


## Cliente bancario

|Nombre actor|Cliente bancario|
|-|-|
|Descripcion| Es el usuario del cajero que realiza operaciones como transferencias, depósitos, consultas de saldo, etc. |
|Caracteristicas| Tiene acceso limitado al sistema y puede realizar operaciones relacionadas con su cuenta.|
|Relaciones| Hacer login, Realizar transferencia, Ver saldo, Ingresar dinero y Poner dinero al móvil|
