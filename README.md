# Máquinas Térmicas — recurso HTML con Quarto

Este proyecto reproduce la misma arquitectura del recurso de **Refrigeración y HVAC**: navegación lateral por semanas, índice de contenido a la derecha, botón para guardar como PDF, paneles ocultables, tema Cosmo y estilos institucionales personalizados.

## Estructura

- `clases/semanaXX/claseXX.qmd`: contenido de cada clase.
- `imagenes/semanaXX/`: imágenes de cada clase, numeradas según su orden de aparición.
- `evaluaciones/`: páginas de las evaluaciones de las semanas 4, 8, 12 y 16.
- `recursos/`: presentaciones, evaluaciones y material complementario fuente.
- `styles.css`: estilos compartidos del curso.
- `boton-pdf.html`: botón Guardar como PDF.
- `paneles.html`: controles para ocultar/mostrar navegación e índice.

## Reemplazar imágenes

Para reemplazar una imagen sin editar el `.qmd`, copie la nueva imagen sobre el archivo existente conservando exactamente el mismo nombre y extensión.

## Ejecutar

Desde la carpeta raíz:

```bash
quarto preview
```

Para renderizar todo el sitio:

```bash
quarto render
```
