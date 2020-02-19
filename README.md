# Trase Atlas TopoJSON

This repository hosts TopoJSON files for each of the [Trase](https://trase.earth) focus countries. It is a direct fork of Mike Bostock's [U.S. Atlas](https://github.com/topojson/us-atlas) and it aims to follow the original implementation as closely as possible.

For each country there is both a projected and an unprojected file. The former is designed to fit a 975×610 viewport.

To align the names of subnational jurisdictions in different countries, three levels have been set:  

* `level1`: country
* `level2`: region/state
* `level3`: municipality/district

## File Reference

### Argentina
* Source: [IGN 2019](https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG)
* Projection: http://pacificprojections.spc.int/22182

```js
d3.geoTransverseMercator().rotate([69, 0]).scale(980.2979807902225).translate([394.0295922144024, -352.4488151969341])
````

<img src="https://raw.githubusercontent.com/bayre/trase-atlas/master/img/Argentina.png" width="480" height="300">

### Brazil
* Source: [IBGE 2018](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html?=&t=downloads)
* Projection: https://epsg.io/5880

```js
d3.geoPolyconic().rotate([54, 0]).scale(836.2137562522385).translate([463.8813199818494, 97.39056551533082])
````

<img src="https://raw.githubusercontent.com/bayre/trase-atlas/master/img/Brazil.png" width="480" height="300">

### Colombia
* Source: [DANE 2017](https://geoportal.dane.gov.co/servicios/descarga-y-metadatos/descarga-mgn-marco-geoestadistico-nacional/)
* Projection: https://epsg.io/21899

```js
d3.geoTransverseMercator().rotate([68.08091666666667, 4.599047222222222]).scale(1816.4205041593148).translate([681.1027944777343, 601.6964125962452])
````

<img src="https://raw.githubusercontent.com/bayre/trase-atlas/master/img/Colombia.png" width="480" height="300">

### Indonesia
* Source: BIG 2016
* Projection: https://epsg.io/23845

```js
d3.geoTransverseMercator().rotate([-139.5, 0]).scale(1052.5481799863685).translate([927.2748077807194, 277.41785402287417])
````

<img src="https://raw.githubusercontent.com/bayre/trase-atlas/master/img/Indonesia.png" width="480" height="300">

### Paraguay
* Source: [DGEEC 2019](http://geo.stp.gov.py/user/dgeec/tables/paraguay_2019_distritos/public)
* Projection: https://epsg.io/32720

```js
d3.geoTransverseMercator().rotate([63, 0]).scale(3874.743636286315).translate([205.86055006293162, -1286.5350680128174])
````

<img src="https://raw.githubusercontent.com/bayre/trase-atlas/master/img/Paraguay.png" width="480" height="300">
