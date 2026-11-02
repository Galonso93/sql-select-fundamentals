¿Por qué es mala práctica usar SELECT * en producción? 
Trae datos innecesarios: consume más recursos y puede hacer más lenta la consulta y la transferencia de resultados.
Vuelve más frágil el código: si agregan columnas a la tabla, cambia el resultado y puede afectar a la aplicación que lo utiliza.
Puede exponer información sensible: por ejemplo, traer contraseñas o datos personales que no necesitabas consultar.

¿Por qué son importantes los alias para un stakeholder no técnico?
Porque algunos nombres de columnas pueden ser muy técnicos y no tan claros para stakeholders. Ejemplo la columna order_date al ser renombrada por fecha_pedido es más claro para personas que no comprenden inglés.
