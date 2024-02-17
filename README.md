# reto_1
Primer reto, recuerden que pueden usar las tecnologías con las que esten comod@s. Recordar leer el README, descargar el proyecto y crear una rama para desarrollar tu solución en ella.
Hoy será un reto básico de validaciones de campos. Lo idel para que sea facil de trabajar es usar alguna tecnologia web, como JSP, alguna de las tecnologias JSF (primefaces, richfaces, otros) u otra tecnologia web que permita hacer validacion de campos desde java.
## Descripción
Crear un formulario que permita hacer una reserva a un restaurante y debe tener al menos los siguientes campos:
- Fecha de la reserva.
   Validar el formato de fecha.
   que sea igual o posterior al dia actual en que se realice la reserva
   Solo se puede realizar una reserva con una diferencia de 6 meses en adelante.
- Hora de la reserva
  Validar formato de hora de la reserva y que esté en un hoario normal de un restaurante (11:00-23:00)
- Nombre de quien realiza la reserva
- mail de quien realiza la reserva
  Validar formato de mail
- telefono de qien realiza la reserva
  Validar que sea un numero de telefono fijo o velular según el formato de colombia
  Se permite el telefono con o sin indicativo de colombia (+57)
  Otros formatos u otros indicativos se notifica como error 
- cantidad de personas incluidas en la reserva.
  Normalmente un restaurante tienen mesas de 2, 4 o 6 puestos, por tanto, validar que una reserva sea para máximo 6 personas

## Otras consideraciones
- Validar que no se hagan 2 reservar repitiendo mail o telefono. 
(Puede ser simplemente guardando una lista o un Map guardando telefono e email al darle guardar mientras se ejecute el programa).
- No hace falta guardar en base de datos pero al darle guardar, que valide los campos y al superar las validaciones que diga que se guardó correctamente.
- Al darle guardar, generar un codigo aleatorio de 4 letras y numeros para que con ese codigo llegue al restaurante como justificante de la reserva (No hace falta guardarlo, solo que se lo muestre al usuario)

