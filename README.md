# Investigaciones RDT — V5.12 Publicación

Sitio académico-divulgativo para el proyecto de Refrigeración Doméstica en Clima Tropical.

## Estructura

- `index.html`: sitio público.
- `portal-interno-v5.html`: portal interno modular.
- `portal-interno.html`: copia compatible del portal interno.
- `404.html`: página de error.
- `assets/img/`: imágenes del sitio.
- `README.md`: instrucciones.

## Cambios V5.12

- Se eliminó del sitio público la sección interna duplicada de acceso interno.
- El menú del sitio público dirige a `portal-interno-v5.html`.
- El portal interno vuelve correctamente a `index.html`.
- Se mejoraron textos públicos para un tono más institucional.
- Se verificaron imágenes y enlaces locales para publicación en GitHub Pages.

## Publicación en GitHub Pages

Descomprimir el ZIP y subir todo el contenido a la raíz del repositorio:

```text
index.html
portal-interno-v5.html
portal-interno.html
404.html
README.md
assets/
```

No subir el ZIP como único archivo.

## Seguridad

GitHub Pages es público. No publicar credenciales, IP internas, tokens, bases crudas, evidencias reservadas ni documentos sensibles.


## V5.13
Prueba con imágenes reales suministradas por el usuario.

Imágenes principales ajustadas:
- hero.jpg: 1600x1140 px, 223.4 KB, fuente ChatGPT Image 26 jun 2026, 02_22_50 p.m. (1).png
- nube.jpg: 1400x700 px, 147.0 KB, fuente ChatGPT Image 26 jun 2026, 02_22_50 p.m. (2).png
- dashboards.jpg: 1400x700 px, 137.9 KB, fuente ChatGPT Image 26 jun 2026, 02_22_51 p.m. (3).png
- iot.jpg: 1400x700 px, 135.7 KB, fuente ChatGPT Image 26 jun 2026, 02_22_51 p.m. (4).png
- impacto.jpg: 1400x700 px, 184.6 KB, fuente ChatGPT Image 26 jun 2026, 02_22_51 p.m. (5).png

También se generaron miniaturas verticales en `assets/img/mini/` para uso posterior.

## V5.14
Ajuste del encabezado superior:
- Se redujo y controló el tamaño del texto del logotipo.
- Se ajustó el ancho de la columna de marca.
- Se redujo el texto del banner para evitar desbordamiento.
- Se añadieron reglas responsive para pantallas medianas y móviles.


## V5.15
- Se eliminó la sigla `RDT` del título del encabezado principal.
- El logotipo conserva solo el texto `INVESTIGACIONES`.

## V5.17
Corrección directa del fondo del cuadro Proyecto:
- Se reemplazó `assets/img/hero.jpg` por la imagen del refrigerador instrumentado con mapa del Huila.
- Se actualizó el `style` inline del primer `<article class="story large">`.
- Se agregó CSS de prioridad para asegurar que el cuadro Proyecto use `assets/img/hero.jpg`.
- Se incluyó `assets/img/proyecto-huila.jpg` como copia de la imagen original.
