# Visualizador de Emergencias

El objeto es fijar una serie de convenios para marcar una configuración óptima que pudiera usarse como base para la publicación de cartografía de interés sobre situaciones de emergencia como la motivada por la erupción del volcán de La Palma.


## Versión preliminar

* BackgroundLayer
  * PNOA MA+ IGN Base Capa Callejero para imagen
  * Mapa LIDAR + IGN Base Capa Callejero para imagen
  * Ortofotos máxima actualidad del PNOA https://www.ign.es/wmts/pnoa-ma
  * Mapa LiDAR https://wmts-mapa-lidar.idee.es/lidar
  * Ocupación del Suelo https://servicios.idee.es/wmts/ocupacion-suelo
  * Mapa base https://www.ign.es/wmts/ign-base
* Capas adicionales.
  * Sucesivas capas vectoriales con las coladas
  * Comprobar la actualización de estas capas. Las demás no merecen la pena.
  * Unidades administrativas https://www.ign.es/wms-inspire/unidades-administrativas?
  * Terremotos (10, 30 y 365 días) https://www.ign.es/wms-inspire/geofisica?
  * PNOA Histórico (SIGPAC, 2005, 2009, 2012, 2015, 2018) https://www.ign.es/wms/pnoa-historico?
  * Catastro

Por ahora nos olvidamos de capas precargadas pues obligaría a usar el *fulltoc* que no es muy  útil para los móviles.

Ponemos el plugin del comparador, aunque tampoco se muy bien si se verá en el comparador.
