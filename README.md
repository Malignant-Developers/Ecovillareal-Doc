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
## Recuperacion del Sitio
Aproximadamente a las 12 am uno de los integrantes del equipo de desarrollo encontró la pagina caida, tras inspección del suceso se encontró que la base de datos bajo la cual el wordpress fue instalado había sido borrada. Entre las posibles causas se descarto un ataque de inyección de SQL y se sospecha que un usuario malicioso con credenciales al panel de Godaddy llego a borrarla. Aun así se contaba con un backup completo del sitio y este fue restaurado en aproximadamente 10 minutos.
