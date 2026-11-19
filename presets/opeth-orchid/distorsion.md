# Opeth · Orchid — Distorsión

- **Instrumento:** Guitarra
- **Estilo / referencia:** Death/prog metal · Opeth, *Orchid* (1995)
- **Guitarra / pastillas:** Ibanez RG, EMG activas
- **Firmware:** 73
- **Estado:** borrador
- **Versión:** 0.1

> El equipo específico de este álbum no está bien documentado. Las listas disponibles son generales de la banda (amplis Laney, Peavey 5150, Mesa Rectifier, Marshall JCM800, pedales Boss). Ver `notas.md`.

## Cadena
`GATE → AMP → CAB → EQ → REV` (DS, MOD y DLY apagados)

| Bloque | Modelo MK-300 | Ajustes |
|---|---|---|
| GATE | AI Gate | Gate 40, Bias 50 |
| DS | Apagado | - |
| AMP | 24J800_DS (JCM 800 Distortion) | Gain 65, Level 50, Bass 50, Middle 60, Treble 55, Reso 45, Pres 50, Bright 20 |
| CAB | 54MRSH03 | Level 50, Low Cut 80 Hz, High Cut 8 kHz |
| EQ | Guitar EQ 6 | 100 Hz −1, 200 Hz 0, 400 Hz −1, 800 Hz +1, 1.6 k +1, 3.2 k 0 |
| REV | Room | Decay 20, Mix 10, High Pass 30, Low Pass 60, Mod Depth 20 |

## Notas y variantes
- **Por qué JCM800:** el Laney GH100L (amplis Laney de la banda) se describe como un JCM800 con una etapa de ganancia extra conmutable. No hay Laney en el MK-300.
- **Pasajes más pesados / growl:** Gain 75, Middle 55.
- **Secciones medias (crunch):** AMP 23J800_OD (JCM 800 Overdrive), Gain 55.
- **Más cuerpo:** sube Bass a 55 si las EMG suenan delgadas.
- Orchid alterna partes pesadas y suaves: guardar el limpio (clean.md) en otra escena.

## Alternativa TONE3000 (NAM)
| Bloque | Buscar en TONE3000 | Autor / tipo | ESR (Full / Lite) | Enlace |
|---|---|---|---|---|
| AMP + CAB (preferida) | "Laney GH100L Celestion Vintage 30" | nordtveit · Amp + Cab, 8 capturas de limpio a alta ganancia | 0.0008 y 0.0015 / 0.0036 y 0.0072 (las dos primeras listadas) | https://www.tone3000.com/tones/laney-gh100l-celestion-vintage-30-77827 |
| AMP (alternativa) | "Laney GH100L free NAM capture" | Mad Hatter Amp Lab · Amp Head DI, 2 capturas gratis (GH100L modificado con gain extra) | no listado | https://www.tone3000.com/tones/laney-gh100l-free-nam-capture-74515 |

- La preferida es rig completo: apagar CAB. Las de ampli solo se usan con CAB 54MRSH03.
- Un mismo pack cubre limpio y distorsión, útil para armar las dos escenas.
- Sin reseñas visibles; elegida por el modelo exacto de ampli y su ESR.

Verificado: 2026-11-18.

## Cambios
| Fecha | Cambio | Motivo |
|---|---|---|
| 2026-11-18 | Versión inicial | Generado con el Excel fw73 |
