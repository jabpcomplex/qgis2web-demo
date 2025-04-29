# qgis2web-demo

A pesar de que la creación de mapas web está estrechamente relacionada con la programación y tiene una curva de aprendizaje alta, existen algunas herramientas que podemos utilizar para hacer mapas interactivos de una forma sencilla.

Una forma de publicar mapas web de forma rápida y sencilla, es utilizando el complemento **qgis2web** en QGIS. Basta con dar unos cuantos clicks en la interfaz gráfica de qgis y podrás generar un mapa html, con javascript y css para después publicar en Github pages.

El origen de este plugin está en los plugins ya existentes qgis2leaf, desarrollado por Riccardo Klinger y  qgis-ol3 de Victor Olaya. Ambos plugins  se han fusionado en uno único denominado qgis2web y ahora es Tom Chadwin quien mantiene este nuevo complemento.

**qgis2web** utiliza las siguientes librerías:

- ol3-layerswitcher
- Autolinker.js
- requestAnimationFrame polyfill
- Function.prototype.bind polyfill
- Leaflet.draw
- Leaflet.label
- Leaflet.markercluster
- Leaflet.MeasureControl
- leaflet-hash
- Proj4js
- Proj4Leaflet
- OSMBuildings

# Ejemplo de mapa creado con qgis2web

<p align="center">
<img src="https://raw.githubusercontent.com/jabpcomplex/qwis2web-demo/refs/heads/main/utopias_iztapalapa.png">
</p>

