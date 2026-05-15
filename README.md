# Capas GeoJSON

Repositorio para almacenar y gestionar capas de datos geográficos en formato GeoJSON.

## Descripción

Este proyecto contiene capas de información geográfica en formato GeoJSON que pueden utilizarse en aplicaciones web de mapas, SIG (Sistemas de Información Geográfica) y análisis espacial.

## Estructura

```
capas/
├── README.md
├── layers/
│   ├── example-points.geojson
│   ├── example-polygons.geojson
│   └── example-linestrings.geojson
└── package.json
```

## Formatos Soportados

- **GeoJSON (.geojson)**: Formato estándar RFC 7946 para datos geográficos

## Cómo Usar

### Visualizar capas

Puedes visualizar los archivos GeoJSON directamente en GitHub. Simplemente abre cualquier archivo `.geojson` y se renderizará automáticamente en el mapa.

### Procesar capas programáticamente

Si usas Node.js, instala las dependencias:

```bash
npm install
```

## Capas Disponibles

Consulta la carpeta `layers/` para ver todas las capas disponibles.

## Contribuir

Para añadir nuevas capas:

1. Crea o descarga un archivo GeoJSON válido
2. Colócalo en la carpeta `layers/`
3. Actualiza este README con la descripción de la nueva capa
4. Haz un commit y push

## Validación

Asegúrate de que tus archivos GeoJSON sean válidos usando herramientas como:
- [GeoJSON.io](https://geojson.io)
- [JSONLint](https://jsonlint.com/)

## Licencia

Sin especificar por ahora.

## Contacto

Creado por: [@jordisalvado](https://github.com/jordisalvado)
