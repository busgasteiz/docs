# AGENTS.md — Documentación BusGasteiz

Repositorio de documentación general del proyecto BusGasteiz.

---

## Estructura del repositorio

```
docs/
├── README.md                                   # Descripción mínima del repositorio
├── referencias.md                              # Referencias y enlaces de interés (APIs, estándares, …)
├── data-index-gtfs-rt.json                     # Índice del API de datos abiertos de Euskadi (GTFS-RT)
├── lineas_tuvisa.pdf                           # Mapa de líneas de Tuvisa (autobuses Vitoria-Gasteiz)
├── COLOURlovers.com_Autumn_Rainbow.html        # Paleta de colores "Autumn Rainbow" (CC BY-NC-SA)
└── COLOURlovers.com_Rainbow_To_Me.html         # Paleta de colores "Rainbow To Me" (CC BY-NC-SA)
```

---

## Contenido

### `referencias.md`

Recopilación de enlaces útiles para el desarrollo: documentación de GTFS, GTFS-RT, APIs de Tuvisa y
Open Data Euskadi, herramientas de inspección de protobuf, referencias de SwiftUI/MapKit, etc.

### `data-index-gtfs-rt.json`

Volcado del índice del catálogo de datos abiertos de Euskadi correspondiente a los feeds GTFS-RT de
Moveuskadi (Tuvisa, Euskotren). Sirve como referencia estática de las URLs y metadatos de los feeds.

### `lineas_tuvisa.pdf`

Mapa oficial de la red de autobuses urbanos de Vitoria-Gasteiz (Tuvisa). Útil para consultar los
recorridos y numeración de líneas.

### Paletas de colores

Las paletas `Autumn_Rainbow` y `Rainbow_To_Me` de COLOURlovers se usaron como referencia durante
el diseño de los colores de las líneas. Licencia **CC BY-NC-SA**.

---

## Instrucciones para agentes

- Este repositorio es solo documentación de referencia; **no contiene código ejecutable**.
- No generar ficheros de código fuente aquí.
- Los diagramas de arquitectura se crean en formato **PlantUML**.
- La documentación general se escribe en **Markdown**.
