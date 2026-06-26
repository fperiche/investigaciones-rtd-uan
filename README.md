# Investigaciones RDT — V5 fiel a Versión 4

Esta versión toma la Versión 4 original como base estructural y visual.

Cambios aplicados:
- Se conserva la composición tipo revista/portal académico de la Versión 4.
- Se actualiza la denominación a Investigaciones RDT.
- Se incorporan imágenes reales optimizadas en `assets/img/`.
- Se mantiene el diseño, la navegación, la jerarquía visual y la distribución de cuadros de la Versión 4.
- Se prepara la estructura para GitHub Pages sin incrustar imágenes en Base64.


## V5.1
Imagen principal de prueba creada e insertada en `assets/img/hero.jpg`.


## V5.2
Corrección: las imágenes ahora se aplican usando los selectores reales de la Versión 4 (`.story`, `.thumb`, `.pic`).


## V5.4
Corrección del portal interno: página autocontenida con estilos propios y estética coherente con la V5 fiel a V4.

## V5.5
Corrección del enlace de acceso interno:
- El sitio público ahora enlaza a `portal-interno-v5.html`.
- Se conserva `portal-interno.html` por compatibilidad.
- Esto evita que, al abrir archivos locales desde Downloads, el navegador use un `portal-interno.html` antiguo.

## V5.6
Corrección de acceso interno:
- El menú principal ahora apunta a `#acceso-interno` dentro del mismo `index.html`.
- Esto evita errores locales cuando se abre un HTML suelto desde Downloads.
- Se conserva `portal-interno-v5.html` como portal completo opcional cuando se usa el paquete completo.

## V5.7
Revisión completa de enlaces desde el sitio principal:
- Se eliminaron del `index.html` los enlaces directos a `portal-interno.html` y `portal-interno-v5.html`.
- El menú `Acceso interno` ahora apunta únicamente a `#acceso-interno`.
- Esto evita `ERR_FILE_NOT_FOUND` cuando se abre un `index.html` local sin la carpeta completa.
- Los archivos `portal-interno.html` y `portal-interno-v5.html` se conservan en el ZIP como páginas independientes.

## V5.8
Corrección final del acceso interno:
- Se insertó realmente la sección `id="acceso-interno"` dentro de `index.html`.
- Todos los enlaces desde el sitio principal apuntan a esa sección interna.
- Se eliminan llamadas externas al portal desde el `index.html`.
- Se agregó JavaScript de respaldo para forzar el desplazamiento hacia la sección integrada.

## V5.9
Portal interno modular:
- Los 6 paneles del portal interno tienen botón `Ver módulo`.
- Cada módulo baja a una sección interna del mismo archivo.
- Se agregó un módulo detallado de Nube FOSS HomeEnergy con Node-RED, InfluxDB, Grafana y JupyterLab.
- Los accesos reales se dejan como botones de maqueta/restringidos para evitar exposición de URLs sensibles.

## V5.10
Navegación bidireccional corregida:
- `index.html` llama al portal interno mediante `portal-interno-v5.html`.
- `portal-interno-v5.html` vuelve al sitio público mediante `index.html`.
- `portal-interno.html` se conserva como copia compatible del portal modular.
- Para probar localmente, descargar el ZIP completo, descomprimirlo y abrir `index.html` desde la carpeta descomprimida.

## V5.11
Paquete completo para GitHub Pages:
- Se agregó la carpeta `assets/img/`.
- Se incluyeron todas las imágenes referenciadas por `index.html` y el portal interno.
- El ZIP debe descomprimirse y subirse completo a la raíz del repositorio.
