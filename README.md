Date.prototype.getDate()
Retorna el día del mes (1–31) para la fecha especificada acorde a la hora local.

Date.prototype.getDay()
Retorna el día de la semana (0–6) para la fecha especificada acorde a la hora local.

Date.prototype.getFullYear()
Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora local.

Date.prototype.getHours()
Retorna la hora (0–23) para la fecha especificada acorde a la hora local.

Date.prototype.getMilliseconds()
Retorna los milisegundos (0–999) para la fecha especificada acorde a la hora local.

Date.prototype.getMinutes()
Retorna los minutos (0–59) para la fecha especificada acorde a la hora local.

Date.prototype.getMonth()
Retorna el mes (0–11) para la fecha especificada acorde a la hora local.

Date.prototype.getSeconds()
Retorna los segundos (0–59) para la fecha especificada acorde a la hora local.

Date.prototype.getTime()
Retorna el valor númerico de la fecha especificada como el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC. (Retona valores negativos para fechas previas.)

Date.prototype.getTimezoneOffset() (en-US)
Retona la diferencia horaria en minutos para la hora local.

Date.prototype.getUTCDate() (en-US)
Retorna el día (fecha) del mes (1–31) para la fecha especificada acorde a la hora local.

Date.prototype.getUTCDay() (en-US)
Retona el día de la semana (0–6) para la fecha especificada en hora universal.

Date.prototype.getUTCFullYear()
Retona el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora universal.

Date.prototype.getUTCHours() (en-US)
Retona la hora (0–23) para la fecha especificada acorde a la hora universal.

Date.prototype.getUTCMilliseconds() (en-US)
Retona los milisegundos (0–999) para la fecha especificada acorde a la hora universal.

Date.prototype.getUTCMinutes() (en-US)
Retorna los minutos (0–59) para la fecha especificada acorde a la hora universal.

Date.prototype.getUTCMonth() (en-US)
Retonar el mes (0–11) para la fecha especificada acorde a la hora universal.

Date.prototype.getUTCSeconds() (en-US)
Retorna los segundos (0–59) para la fecha especificada acorde a la hora universal.

Date.prototype.getYear() (en-US)
Retorna el año (usualmente de 2 a 3 dígitos) para la fecha especificada acorde a la hora local. Usa getFullYear() en su lugar.

Date.prototype.setDate() (en-US)
Establece el día del mes para la fecha especificada acorde a la hora local.

Date.prototype.setFullYear()
Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha espefica acorde a la hora local.

Date.prototype.setHours() (en-US)
Establece la hora para una fecha especifica acorde a la hora local.

Date.prototype.setMilliseconds() (en-US)
Establece los milisegundos para una fecha especifica acorde a la hora local.

Date.prototype.setMinutes() (en-US)
Establece los minutos para una fecha especifica acorde a la hora local.

Date.prototype.setMonth()
Establece el mes para una fecha especifica acorde a la hora local.

Date.prototype.setSeconds() (en-US)
Establece los segundos para una fecha especifica acorde a la hora local.

Date.prototype.setTime() (en-US)
Establece el objeto Date al tiempo representado por un número de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC. Usa números negativos para fechas previas.

Date.prototype.setUTCDate() (en-US)
Establece el día del mes para la fecha especificada acorde a la hora universal.

Date.prototype.setUTCFullYear() (en-US)
Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha espefica acorde a la hora universal.

Date.prototype.setUTCHours() (en-US)
Establece la hora para una fecha especifica acorde a la hora universal.

Date.prototype.setUTCMilliseconds() (en-US)
Establece los milisegundos para una fecha especifica acorde a la hora universal.

Date.prototype.setUTCMinutes() (en-US)
Establece los minutos para una fecha especifica acorde a la hora universal.

Date.prototype.setUTCMonth() (en-US)
Establece el mes para una fecha especifica acorde a la hora universal.

Date.prototype.setUTCSeconds() (en-US)
Establece los segundos para una fecha especifica acorde a la hora universal.

Date.prototype.setYear() (en-US)
Establece el año (usualmente de 2 a 3 dígitos) para una fecha especifica acorde a la hora local. Usa setFullYear() en su lugar.

Date.prototype.toDateString()
Retona la "fecha" del objeto Date como una cadena facil de leer por humanos 'Thu Apr 12 2018'.

Date.prototype.toISOString()
Convierte una fecha a una cadena siguiendo el ISO 8601 de Formato Extendido.

Date.prototype.toJSON()
Retorna una cadena representando el objeto Date usando toISOString(). Destinado a ser usado por JSON.stringify().

Date.prototype.toGMTString() (en-US)
Retona una cadena representando el objeto Date basado en la zona horaria GMT (UTC). Usa toUTCString() en su lugar.

Date.prototype.toLocaleDateString()
Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

Date.prototype.toLocaleString()
Retorna una cadena con una representación sensible a la localización de esta fecha. Sobrescribe el método Object.prototype.toLocaleString().

Date.prototype.toLocaleTimeString()
Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

Date.prototype.toString() (en-US)
Retorna una cadena representando el objeto especificado Date. Sobrescribe el método Object.prototype.toString().

Date.prototype.toTimeString() (en-US)
Retona la porción de "tiempo" del objeto Date a una cadena legible para humanos.

Date.prototype.toUTCString()
Convierte una fecha a una cadena usando la zona horaria UTC.

Date.prototype.valueOf() (en-US)
Retona el valor primitivo de un objeto Date. Sobrescribe el método Object.prototype.valueOf().

ChatGPT
Métodos de la Clase Date
La clase Date en JavaScript proporciona una amplia gama de métodos para trabajar con fechas y horas. Aquí están los principales métodos de la clase Date:

Métodos para Obtener Componentes de Fecha y Hora
getDate(): Retorna el día del mes (1–31) para la fecha especificada en la hora local.
getDay(): Retorna el día de la semana (0–6) para la fecha especificada en la hora local.
getFullYear(): Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada en la hora local.
getHours(): Retorna la hora (0–23) para la fecha especificada en la hora local.
getMilliseconds(): Retorna los milisegundos (0–999) para la fecha especificada en la hora local.
getMinutes(): Retorna los minutos (0–59) para la fecha especificada en la hora local.
getMonth(): Retorna el mes (0–11) para la fecha especificada en la hora local.
getSeconds(): Retorna los segundos (0–59) para la fecha especificada en la hora local.
getTime(): Retorna el valor numérico de la fecha especificada como el número de milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC.
getTimezoneOffset(): Retorna la diferencia horaria en minutos para la hora local.
getUTCDate(): Retorna el día del mes (1–31) para la fecha especificada en hora universal (UTC).
getUTCDay(): Retorna el día de la semana (0–6) para la fecha especificada en hora universal (UTC).
getUTCFullYear(): Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada en hora universal (UTC).
getUTCHours(): Retorna la hora (0–23) para la fecha especificada en hora universal (UTC).
getUTCMilliseconds(): Retorna los milisegundos (0–999) para la fecha especificada en hora universal (UTC).
getUTCMinutes(): Retorna los minutos (0–59) para la fecha especificada en hora universal (UTC).
getUTCMonth(): Retorna el mes (0–11) para la fecha especificada en hora universal (UTC).
getUTCSeconds(): Retorna los segundos (0–59) para la fecha especificada en hora universal (UTC).
getYear(): (Desaprobado) Retorna el año (usualmente de 2 a 3 dígitos) para la fecha especificada en la hora local. Se recomienda usar getFullYear() en su lugar.
Métodos para Establecer Componentes de Fecha y Hora
setDate(): Establece el día del mes para la fecha especificada en la hora local.
setFullYear(): Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha especificada en la hora local.
setHours(): Establece la hora para una fecha especificada en la hora local.
setMilliseconds(): Establece los milisegundos para una fecha especificada en la hora local.
setMinutes(): Establece los minutos para una fecha especificada en la hora local.
setMonth(): Establece el mes para una fecha especificada en la hora local.
setSeconds(): Establece los segundos para una fecha especificada en la hora local.
setTime(): Establece el objeto Date al tiempo representado por un número de milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC.
setUTCDate(): Establece el día del mes para la fecha especificada en hora universal (UTC).
setUTCFullYear(): Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha especificada en hora universal (UTC).
setUTCHours(): Establece la hora para una fecha especificada en hora universal (UTC).
setUTCMilliseconds(): Establece los milisegundos para una fecha especificada en hora universal (UTC).
setUTCMinutes(): Establece los minutos para una fecha especificada en hora universal (UTC).
setUTCMonth(): Establece el mes para una fecha especificada en hora universal (UTC).
setUTCSeconds(): Establece los segundos para una fecha especificada en hora universal (UTC).
setYear(): (Desaprobado) Establece el año (usualmente de 2 a 3 dígitos) para una fecha especificada en la hora local. Se recomienda usar setFullYear() en su lugar.
Métodos para Representar la Fecha como Cadena
toDateString(): Retorna la "fecha" del objeto Date como una cadena fácil de leer por humanos.
toISOString(): Convierte una fecha a una cadena siguiendo el formato ISO 8601 Extendido.
toJSON(): Retorna una cadena representando el objeto Date usando toISOString(). Destinado a ser usado por JSON.stringify().
toLocaleDateString(): Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.
toLocaleString(): Retorna una cadena con una representación sensible a la localización de esta fecha.
toLocaleTimeString(): Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.
toString(): Retorna una cadena representando el objeto especificado Date.
toTimeString(): Retorna la porción de "tiempo" del objeto Date como una cadena legible para humanos.
toUTCString(): Convierte una fecha a una cadena usando la zona horaria UTC.
Otros Métodos
valueOf(): Retorna el valor primitivo de un objeto Date.
Recuerda consultar la documentación oficial de JavaScript para más detalles sobre estos métodos y sus usos.