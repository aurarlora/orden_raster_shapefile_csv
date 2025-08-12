# Mapa de cuadrícula GRACE sobre basemap (EPSG:3857)

Este repositorio contiene utilidades para:

- Generar **líneas de cuadrícula** a partir de centros (`lons`, `lats`) ordenados (lon ascendente, lat descendente).
- Convertir centros de celda a **puntos** para anotar `cell_id`.
- Reproyectar todo a **EPSG:3857** y dibujar sobre un **basemap** de `contextily`.
- Controlar el **extent** usando los **bordes reales de la grilla** (no los centros) para cubrir los cuadros completos.

## Requisitos

- Python 3.9+
- Paquetes:
  - `geopandas`
  - `shapely`
  - `numpy`
  - `pyproj`
  - `contextily`
  - `matplotlib`

Instalación rápida:
```bash
pip install geopandas shapely numpy pyproj contextily matplotlib
