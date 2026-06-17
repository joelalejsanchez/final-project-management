# Descripción Técnica

## Metodología

El proyecto aplicará una **Metodología Híbrida** dado que los requerimientos serán mayormente estrictos, pero involucrar aspectos de metodologías ágiles para adaptar cambios necesarios.

## Requerimientos

- Registro de puestos y comerciantes: Es necesario realizar el registro de información personal de los comerciantes o puestos y con ello gestionar el permiso y fechas de vencimiento para realizar el control posterior.
- Registro de tarifas y cobros: Es necesario llevar el seguimiento de las tarifas de funcionamiento y mantenimiento, también con ello hacer un seguimiento correspondiente de los pagos y así poder revocar el permiso si no se cumple con los pagos.
- Seguimiento para licencias sanitarias: Para mantener la calidad sanitaria de los espacios de venta y puestos es necesario registrar licencias sanitarias y poder actualizarla ante posteriores revisiones.
- Informes mensuales de ingresos: Es necesario la generación de reportes para la dirección de ingresos para que tengan constancia del cobro de tarifas en los mercados municipales.

## Matriz de Priorización

| Must                                                                      | Should                                                                                                                                                                                                                                                                |
| ------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| - Registro de puestos y comerciantes <br/> - Registro de tarifas y cobros | - Seguimiento de licencias sanitarias <br/> - Informes para la dirección de ingresos <br/> - Respaldos fotrográficos                                                                                                                                                  |
| **Could**                                                                 | **Won't**                                                                                                                                                                                                                                                             |
| - Geolocalización                                                         | - Registro de sindicatos <br/> - Acceso directo para comerciantes o encargados de puestos <br/> - No gestionará cobros de servicios básicos <br/> - No gestionará traspasos o herencias, debe realizarse un nuevo proceso <br/> - Control de pesos, medidas o precios |

## Cronograma

El proyecto a realizarse en 6 meses, se divide en 24 semanas, detallado en la siguiente tabla secuencialmente:

| Semana(s) | Módulo(s)                                          |
| --------- | -------------------------------------------------- |
| 1 - 3     | Arquitectura base y acceso al sistema              |
| 4 - 6     | Registro de puestos y comerciantes                 |
| 7 - 9     | Seguimiento de licencias sanitarias                |
| 10 - 11   | Registro de tarifas                                |
| 12 - 13   | Cobros                                             |
| 14 - 15   | Elaboración de Informes                            |
| 16 - 19   | Pruebas de calidad y verificación de funcionalidad |
| 20 - 21   | Capacitación a usuarios del sistema                |
| 22 - 24   | Despliegue a producción y registros iniciales      |

## Riesgos

| N   | Riesgo                                                      | Probabilidad | Impacto | Mitigación                                                                                                                                                                                                               |
| --- | ----------------------------------------------------------- | ------------ | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | Renuncia de integrantes del equipo de desarrollo            | Medio        | Alto    | Realizar la negociación con el integrante o buscar la contratación de un integrante para el mismo rol                                                                                                                    |
| 2   | Cambio de requerimientos durante el desarrollo del producto | Medio        | Medio   | Realizar un analísis de importancia e impacto del requerimiento indicado. Si es necesario deberá proveerse más tiempo y recursos económicos                                                                              |
| 3   | Problemas de compatibilidad con dispositivos                | Bajo         | Medio   | Evaluar y adecuar el producto a los dispositivos actuales o plantear la compra de dispositivos nuevos según las necesidades del sistema y presupuesto disponible                                                         |
| 4   | Tiempos insuficientes para desarrollo                       | Bajo         | Alto    | Realizar una evaluación constante de cambios para identificar cuellos de botella y notificar debidamente para realizar una extensión mientras se prioriza características importantes para que el proyecto sea funcional |
| 5   | Cambio en las normativas asociadas al proyecto              | Medio        | Medio   | Identificar las características estrechamente relacionadas con normativas para aislarlas de elementos genéricos y reducir el impacto                                                                                     |

## Plan de Recursos

El equipo de desarrollo debe contar con computadoras para el trabajo y deben usar herramientas de software libre y evitar software de licencia o restrictivo como software propietario.
Los recursos necesarios son:

- 1 desarrollador backend, encargado de la aplicación de servidor y administración de base de datos.
- 1 desarrollador de escritorio, encargado de desarrollar la aplicación para computadoras.
- 1 encargado de QA y analísis, encargado de evaluar el funcionamiento correcto del sistema y que esté apegado a las reglas de negocio impuestas.
- Servidor para desarrollo y pruebas
- 3 Computadoras para desarrollo
- Software de Gestión y Planificación, para hacer registro de las tareas pendientes y el avance semanal, permitiendo asi documentar el trabajo mienstras se va completando

## Presupuesto

|                                   | Total (Bs.) | Comentarios                                      |
| --------------------------------- | ----------- | ------------------------------------------------ |
| Dev. Backend                      | 24000.00    | Tiempo completo                                  |
| Dev. Escritorio                   | 24000.00    | Tiempo completo                                  |
| Encargado QA                      | 12000.00    | Tiempo parcial                                   |
| Servidor (Cloud)                  | 600.00      | VPS para desarrollo                              |
| Software de Gestión/Planificación | 1500.00     | Usado para documentar el avance y requerimientos |
