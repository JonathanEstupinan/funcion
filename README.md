# funcion
Esta función se llama ConcatenarDatosEmpresario y toma el nombre del empresario, el teléfono y la cédula como parámetros. enlaza estos valores en un formato específico y devuelve el resultado.

Para usar esta función, puedes hacerlo de la siguiente manera:

SELECT ID_NOMBRE, ID_TELEFONO, CEDULA, ConcatenarDatosEmpresario(ID_NOMBRE, ID_TELEFONO, CEDULA) AS DatosConcatenados
FROM EMPRESARIO_DESCUENTO;

Esto seleccionará los valores de nombre, teléfono y cédula de la tabla EMPRESARIO_DESCUENTO y también mostrará los datos Enlazados utilizando la función ConcatenarDatosEmpresario.
