# Desarrollo de la Pagina de Eco Villa Real
## Mantenimiento Inicial del Sitio
1. Se elimino el plugin llamado Jetpack, el cual no permitía que wp funcionara.
2. Se realizo un backup del sitio, este esta ubicado en una carpeta de GDrive.
3. Se actualizo a la versión mas reciente de wordpress (5.4.1).
4. Se actualizaron todos los plugins existentes.

## Personalización
1. Se instalo el tema de Astra.
2. Se instalo el plugin Astra-Starter Templates.
3. Se importo el template "outdoor" adventure.
4. Se migro la información de "Acerca de Nosotros" y "Ubicación" a una 
   única pagina llamada "Sobre Nosotros".
5. Se unieron todas las fotos rescatadas del sitio previo bajo un sitio llamado "Galería".
6. Se creo una pagina de "Asamblea" para los blogs de las pagina.
7. Se creo un “Landing Page” para el sitio.
8. Se migro la información de http://www.podioconsultores.com/reservasvr/ hacia la pagina de reservaciones.
9. Se creo el modulo de booking.
10. Se modificaron los correos para mostrar las áreas reservadas.
11. Se elimino la opción de reservar el mismo día.
12. Se actualizo el panel de administracipón para mostrar una vista semanal y diaria de las reservaciones.
13. Se configuro la funcionalidad para la aprobación o negación remota de las reservaciones, esto enruta hacia una pagina especial donde se confirma la acción tomada. Esto es realizado mediante el correo enviado a la administración una vez se crea una nueva aprovación.
## Recuperación del Sitio
Aproximadamente a las 12 am uno de los integrantes del equipo de desarrollo encontró la pagina caida, tras inspección del suceso se encontró que la base de datos bajo la cual el wordpress fue instalado había sido borrada. Entre las posibles causas se descarto un ataque de inyección de SQL y se sospecha que un usuario malicioso con credenciales al panel de Godaddy llego a borrarla. Aun así se contaba con un backup completo del sitio y este fue restaurado en aproximadamente 10 minutos.
### Reparación del Hosting
Poco después de terminar el desarrollo del sitio, el modulo de reservaciones paro de funcionar o más bien este se quedaba cargando sin llegar a completar entre otros sintomas se volvio imposible modificar el sitio e instalar, actualizar y remover plugins en el sitio de wordpress. El unico codigo de error o indicio que proporcionaba el sitio era un 503, se probaron multiples soluciones entre las cuales se intento:
1. Remover todos los plugins a excepción del plugin de reservación para averiguar si existía algún conflicto.
2. Desactivar las notificaciones por correo del plugin en caso de que el servidor de correo estuviera bloqueando dichas transacciones.
3. Según GoDaddy, una posible solución seria desactivar firewall del sitio pero para tener acceso a esto fue necesario adquirir una licencia especial de seguridad. (No soluciono el problema)
4. Según GoDaddy, una posible solución seria tanto actualizar el plan de hosting a uno mas reciente con cPannel lo cual de nuevo requiere de costo adicional.
### Actualizacion del Hosting
Tras conversar con un agente de soporte de GoDaddy, se llego al acuerdo de mejorar el hosting antiguo a uno actualizado con acceso a cPannel. A pesar del costo de entrada para un mes, se utilizara el saldo restante del plan previo lo cual incremento el plan por 6 meses en total.
