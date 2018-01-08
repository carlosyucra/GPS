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

.. rubric:: Tabla 1. Sección de Matriz de Trazabilidad de Logística del MiniERP

En Tabla 1, se presenta una sección de la matriz de trazabilidad para enlazar los requerimientos con su respectivos archivos a desarrollar mediante la metodología seguida en el proyecto. En la columna fuente se encuentran los archivos fuentes en codigo Java y JS que realizan las funcionalidades descritas en cada requerimiento enlazado.

Estructura Detallada del Desglose de Trabajo (EDT)

Se realizó la Estructura Detallada del Desglose del trabajo, para cada área de trabajo, en este caso, del área de logística. Se considero el mismo esquema del proyecto en conjunto que a su vez es adoptado por cada área de trabajo del MiniERP.

Gestión de los Recursos Humanos
------------------------------

Identificar a los Interesados
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En este caso se identificó a los interesados del proyecto en general, en este caso, los responsables del área de contabilidad, logística, procesos y gerencia en las organizaciones.

Para poder identificar sus intereses, expectativas y requisitos, se llevo a cabo una reunión formal con el interesado del proyecto (gerente) de una organización.

Esta información no fue documentada, sin embargo PMBOK recomienda hacerlo.


Gestión del Cronograma
----------------------

 En esta sesión describiremos cómo será gestionado según el tiempo del proyecto, para ellos incluye procesos requeridos desde la definición y el secuenciamiento de las actividades hasta la estimación de la duración de cada actividad y desarrollo del cronograma del proyecto.

Para esta elaboración se tomará en cuenta los hitos del proyecto. las cuales se usarán para definir las fechas principales del proyecto.

