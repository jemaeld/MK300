# MK-300 · Presets

Repositorio de presets para la **MK-300** (modelador de amplificadores y multiefectos), con su prompt de generación y el historial de ajustes de cada uno.

> **Firmware actual de referencia: 73.** El firmware 75 se agregará más adelante; los presets se irán actualizando cuando haga falta (ver `docs/ACTUALIZAR_FIRMWARE.md`).

## Estructura

```
├── README.md
├── CHANGELOG.md
├── prompt/
│   └── PROMPT_PRESETS_MK300.md      Prompt para generar presets
├── data/
│   └── fw73/                        Excel de modelos del firmware 73
├── docs/
│   ├── CONTEXTO.md                  Cómo trabajar y mejorar presets
│   └── ACTUALIZAR_FIRMWARE.md       Proceso para migrar a un firmware nuevo
└── presets/
    ├── plantilla.md                 Plantilla para presets nuevos
    └── <proyecto>/                  Un directorio por artista, álbum o sonido
```

## Estado de los presets

Estados: `borrador` → `en pruebas` → `final`

| Proyecto | Preset | Instrumento | Estado | Firmware |
|---|---|---|---|---|
| Dissection · Storm of the Light's Bane | [Rhythm](presets/dissection-storm/rhythm.md) | Guitarra | borrador | 73 |
| Dissection · Storm of the Light's Bane | [Lead](presets/dissection-storm/lead.md) | Guitarra | borrador | 73 |
| Dissection · Storm of the Light's Bane | [Clean](presets/dissection-storm/clean.md) | Guitarra | borrador | 73 |

## Flujo de trabajo

1. Generar el preset con el prompt y el Excel del firmware vigente.
2. Guardarlo en `presets/<proyecto>/` con la plantilla, en estado `borrador`.
3. Probarlo en la MK-300 y anotar cada ajuste en la sección **Cambios** del archivo (un commit por ajuste).
4. Al quedar bien, pasarlo a `final` y crear un tag, por ejemplo `dissection-rhythm-v1.0`.
