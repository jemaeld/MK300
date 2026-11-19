# Satyricon · Nemesis Divina — Clean

- **Instrumento:** Guitarra
- **Estilo / referencia:** Partes limpias del álbum *Nemesis Divina* (1996)
- **Guitarra / pastillas:** Ibanez RG, EMG activas
- **Firmware:** 73
- **Estado:** borrador
- **Versión:** 0.1

> Propuesta propia. No hay equipo documentado para los limpios de este álbum. Se asume el mismo ampli de todo el disco (canal limpio de un Fender), sin pedales.

## Cadena
`GATE → AMP → CAB → EQ → REV` (DS, MOD y DLY apagados)

| Bloque | Modelo MK-300 | Ajustes |
|---|---|---|
| GATE | AI Gate | Gate 15, Bias 50 |
| DS | Apagado | - |
| AMP | 17FD_CH1 (65 Twin Reverb Channel 1) | Gain 30, Level 50, Bass 45, Middle 50, Treble 55, Reso 40, Pres 40, Bright 25 |
| CAB | 18FD_TW1971 | Level 50, Low Cut 80 Hz, High Cut 9 kHz |
| EQ | Guitar EQ 6 | 100 Hz −2, 200 Hz 0, 400 Hz −1, 800 Hz 0, 1.6 k +1, 3.2 k +1 |
| REV | Hall | Decay 40, Mix 18, High Pass 30, Low Pass 60, Mod Depth 20 |

## Notas y variantes
- **Más oscuro:** Treble 45, High Cut 7 kHz.
- **Más cristalino:** 21FD_TW2000 como cab y Bright 35.
- **Con movimiento (opcional):** MOD Chorus, Speed 1.5, Depth 25, Mix 20. No está documentado para este álbum.
- **Volumen entre presets:** si el limpio suena más fuerte que el distorsionado, Level del amp 40 (EMG activas).

## Alternativa TONE3000 (NAM)
| Bloque | Buscar en TONE3000 | Autor / tipo | ESR (Full / Lite) | Enlace |
|---|---|---|---|---|
| AMP | "performer 1000" (Fender Performer 1000) | joffo78 · Amp Head, solo limpio, 1 modelo "performertrain", ~204 descargas | 0.0896 / 0.0997 | https://www.tone3000.com/tones/performer-1000-31298 |

- Es el único ampli documentado del álbum, pero el ESR es alto (poco preciso) y tiene un solo comentario.
- Es amp head: usar con CAB (por ejemplo 18FD_TW1971).
- Un comentarista dice que funciona bien con un pedal de distorsión delante y suena a transistor "afilado".

Verificado: 2026-11-18.

## Cambios
| Fecha | Cambio | Motivo |
|---|---|---|
| 2026-11-18 | Versión inicial | Generado con el Excel fw73 |
