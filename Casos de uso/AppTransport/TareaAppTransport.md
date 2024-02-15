# Tabla Actor

| Actor | Aplicación de transporte |
|-------|-------------------------|
| Descripción | Los usuarios pueden regristrarse en la app | 
| Flujo de eventos |  El usuario se registra y planea la ruta por geolocalización |
| Flujo basico | El usuario se registra, después de loggearse y verificar sus datos accede al planeador de rutas, de ahí el sistema sugiere destinos al hacer click en el boton de 'Destinos interesantes' |
| Flujos alternativos | El usuario tiene la posibilidad de fallar al hacer Login |


# Tabla Caso de Uso

| Nombre de caso de uso | Definir transporte |
|-------|-------------------------|
| Actor | Administrador | 
| Resumen |  El trabajo del administrador es definir el medio de transporte para el Usuario |
| Precondiciones | El medio de transporte es registrado y comprueba su disponibilidad |
| Postcondiciones | El transporte llega al destino elegido por el propio usuario |