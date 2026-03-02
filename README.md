# Pizarra Claustro Criminología

Aplicación web para organizar proyectos en pizarras separadas, con nodos visuales conectables sobre un lienzo infinito.

## Funcionalidades

- Título visible de producto: **Pizarra de Claustro**.
- Pizarras múltiples (una por proyecto).
- Elementos: nota, imagen, video/enlace y línea de tiempo.
- Línea de tiempo con formulario para múltiples eventos/periodos con fecha.
- Redimensionado manual de nodos (drag en esquina inferior derecha).
- Redimensionado de pildoras de **notas** y **timeline** con botones `A-` / `A+`.
- Cambio de color de pildoras con botón `🎨`.
- Edición directa en vivo de notas y pildoras del timeline (evento/periodo).
- Conexiones rectas entre nodos (modo **Conectar**).
- Importación de **JSON y TSV** desde el botón `Importar JSON/TSV` (pegado directo).
- Exportación de JSON de la pizarra activa (descarga de archivo `.json`).
- Pan (`Shift + arrastrar`) y zoom (rueda).
- Persistencia en `localStorage`.

## Ejecutar

```bash
python3 -m http.server 4173
```

Luego visita `http://localhost:4173`.
