.. _metodologia:

Planificación del Proyecto MiniErp en el Módulo de Logística
============================================================

Gestión del Alcance
----------------------

En esta sección se presenta el trabajo necesario para culminar el proyecto con éxito, es decir, se define y se controla  qué se incluye y que no se incluye en el módulo de Logística del MiniERP. Segun la guia PMBOK [x], existen procesos involucrados en la planificación para el alcance de un proyecto y que a su vez han sido utilizados en el software MiniERP.


1. Recopilación de Requisitos
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para la recopilación de requisitos, se considero la documentación acerca de los deseos, necesidades y expectativas de las partes interesadas de las organizaciones en común en el área de logística. Tras la primera impresión, se diferenció entre los requisitos del proyecto y los requisitos del producto y de esa forma separar la parte técnica de la dirección del proyecto de forma organizacional.

Además, se realizo documentación acerca del análisis de un ERP mediante la siguiente metodología en el ciclo de vida del software: Proceso Racional Unificado (RUP). También se concretó la especificación de cada requerimiento identificado del software y se relacionaron entre si y con su consecución a lo largo del ciclo de vida del proyecto hacia el desarrollo mediante una Matriz de Trazabilidad. 

Sección de Matriz de Trazabilidad de Logística del MiniERP
----------------------------------------------------------

+-------------+------------+------------------------+----------------------------------------------------------------------------+
| Módulo      | Código Req | Nombre		    | Fuente								         |
+=============+============+========================+============================================================================+
|             | RQ01	   | Reporte de Inventario  | InventarioController,InventarioService,listarArticulos().			 |
+             +------------+------------------------+----------------------------------------------------------------------------+
| Logística   | RQ02	   | Orden de Compra	    | MovimientoCabeceraController,  MovimientoDetalleController,  mdService.	 |
+             +------------+------------------------+----------------------------------------------------------------------------+
|             | RQ03	   | Reporte de  Kardex     | KardexController, LogisticaKardexService, listarArticulos().		 |
+-------------+------------+------------------------+----------------------------------------------------------------------------+

