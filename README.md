-- Pre-Entrega4 - Consultas SQL de negocio--

--  Extrayendo métricas clave con SQL --

-- En la Consulta 1 — Resumen ejecutivo mensual: el resultado es el total facturado, la cantidad de pedidos y el ticket promedio agrupados por mes, usando MONTH(fecha_venta), SUM(), COUNT(), AVG(), GROUP BY.

-- En la Consulta 2 — Ranking de producto: el resultado es el Top 5 productos por total facturado, con unidades vendidas, usando TOP 5, GROUP BY, ORDER BY total_facturado DESC.

-- En la Consulta 3 — Clientes recurrentes: el resultado son los clientes con más de un pedido, ordenados por total gastado, usando GROUP BY id_cliente + HAVING COUNT(*) > 1.

-- En la Consulta 4 — Meses por encima/por debajo del promedio: el resultado es el total facturado por mes con etiqueta comparativa vs el promedio genera, usando WITH (CTEs), AVG(), CROSS JOIN y CASE WHEN, THEN 'Por encima' ELSE 'Por debajo' END.

-- Se detalla en el bloque de cierre, 3 hallazgos que arrojan los resultados de las consultas realizadas.  
