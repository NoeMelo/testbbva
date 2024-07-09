# testbbva
dataset test CoE Intern

## Descripción del Dataset de Clasificación
Este dataset contiene información sobre clientes y está diseñado para un ejercicio de clasificación, donde el objetivo es predecir si un cliente hará un default en el pago (es decir, si no pagará). El dataset tiene 500 registros y las siguientes columnas:

id_cliente: Identificador único para cada cliente.

edad: Edad del cliente.

ingreso_anual: Ingreso anual del cliente en unidades monetarias.

gasto_mensual: Gasto mensual del cliente en unidades monetarias.

estado_civil: Estado civil del cliente, que puede ser uno de los siguientes: "Soltero", "Casado", "Divorciado", "Viudo".

default_de_pago: Indicador binario de si el cliente ha hecho default en el pago (0 = No, 1 = Sí).

## Descripción del Dataset Complementario de Clasificación
Este dataset complementa al anterior y contiene información adicional sobre los clientes. Cada registro en este dataset está relacionado con un registro en el primer dataset mediante el campo id_cliente. Las columnas de este dataset son:

id_cliente: Identificador único para cada cliente, que coincide con el primer dataset.

ocupacion: Ocupación del cliente, que puede ser una de las siguientes: "Empleado", "Desempleado", "Autónomo", "Jubilado".

num_dependientes: Número de dependientes que tiene el cliente.

region: Región donde reside el cliente, que puede ser una de las siguientes: "Norte", "Sur", "Este", "Oeste".
