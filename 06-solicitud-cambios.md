# Solicitud de Cambios - Geolocalización de Puestos

En la semana 10 iniciado el proyecto, la Alcaldía hizo la solicitud de un módulo de **geolocalización** de puestos, se procedió de la siguiente manera:

## Proceso de Evaluación

1. Se hizó el análisis de requerimientos para determinar los detalles específicos del nuevo módulo.
2. Se evaluó el impacto e importancia del nuevo módulo en el proyecto, en este caso la inclusión de un módulo de geolocalización bien planteado involucraría el desarrollo de una aplicación movil y por lo tanto la inclusión de un profesional, lo cual excede el presupuesto actual.
3. Se negoció la inclusión del módulo aclarando el impacto en el tiempo, dificultad y necesidades actuales.
4. Se negó la inclusión del nuevo módulo en el MVP debido a la importancia de sacar el producto con los requerimientos escenciales y se dejó el módulo para una versión posterior. Sin embargo se agregaron campos para información de coordenadas (latitud, longitud, link de mapa) al registro de puestos para su posterior extensión.

## Actualización de Riesgos

Dada la posibilidad de extensión se agregó un riesgo al final de la tabla de riesgos.

| N   | Riesgo                                    | Probabilidad | Impacto | Mitigación                                                                                                                                                                     |
| --- | ----------------------------------------- | ------------ | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 6   | Inexactitud en el registro de coordenadas | Alto         | Medio   | Incluir la capacidad de registrar enlaces de mapas, permitiendo de cierta manera un registro más preciso y menos margen de error que si se tuviera que copiar las coordenadas. |
