# Desafio-citas-medicas

### Para iniciar el programa es necesario ejecutar en la terminal node index.js esperar el listen del localhost y aperturar en el navegador http:localhost:8080

**Requerimientos**
- El registro de los usuarios debe hacerse con la API Random User usando axios para consultar la data
- Cada usuario registrado debe tener un campo id único generado por el paquete UUID
- Cada usuario debe tener un campo timestamp almacenando la fecha de registro obtenida por medio del paquete Moment
- Por cada consulta realizada al servidor, se debe devolver al cliente una lista con los datos de todos los usuarios registrados usando Lodash para recorrer el arreglo de usuarios
- En cada consulta también se debe imprimir por la consola del servidor la misma lista de usuarios pero con fondo blanco y color de texto azul usando el paquete Chalk
- El servidor debe ser levantado con el comando Nodemon.
