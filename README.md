# Manual de Python

Libro Quarto con el [Manual de Python de aprendeconalf](https://aprendeconalf.es/docencia/python/manual/), de Alfredo Sánchez Alberca, con la misma estructura que [bioestadistica-practicas-r](https://github.com/asalber/bioestadistica-practicas-r).

## Estructura

- `_quarto.yml`: configuración del libro (capítulos, apéndices, formatos HTML/PDF/EPUB, salida en `docs/` para GitHub Pages).
- `index.qmd`: prefacio y licencia.
- `NN-*.qmd`: capítulos, generados a partir de los ficheros Markdown originales del manual (cada NN es un número).
- `img/`: imágenes del manual.
- `docs/`: sitio HTML renderizado (listo para publicar con GitHub Pages apuntando a la carpeta `docs`).

## Renderizado

```sh
quarto render            # todos los formatos
quarto render --to html  # solo HTML
quarto preview           # vista previa local en el puerto 1313
```

Para el PDF se necesita una instalación de LaTeX (`quarto install tinytex`).

## Licencia

Creative Commons Reconocimiento – No comercial – Compartir igual 3.0 España (CC BY-NC-SA 3.0 ES), como la obra original.
