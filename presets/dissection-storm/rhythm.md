# Dissection · Storm of the Light's Bane — Rhythm

- **Instrumento:** Guitarra
- **Estilo / referencia:** Metal / black-melodic death · Dissection, *Storm of the Light's Bane* (1995)
- **Guitarra / pastillas:** Ibanez RG, EMG activas
- **Firmware:** 73
- **Estado:** borrador
- **Versión:** 0.1

## Cadena
`GATE → DS → AMP → EQ → DLY → REV` (MOD apagado; el AMP es Full Rig, no lleva CAB)

| Bloque | Modelo MK-300 | Ajustes |
|---|---|---|
| GATE | AI Gate | Gate 45, Bias 50 |
| DS | MW-DS1 (sustituye al Boss DS-2) | Gain 40, Tone 60, Level 70 |
| AMP | 4J900_HV (JCM 900 High Gain, Full Rig) | Gain 80, Level 50, Bass 45, Middle 55, Treble 60, Reso 50, Pres 55, Bright 30 |
| EQ | Guitar EQ 6 | 100 Hz −3, 200 Hz −2, 400 Hz −1, 800 Hz +1, 1.6 k +2, 3.2 k +2 |
| DLY | Clean | Apagado en ritmos (se usa en Lead) |
| REV | Hall | Decay 30, Mix 10, High Pass 30, Low Pass 60, Mod Depth 20 |

## Notas y variantes
- **Alternativa de cadena:** DS en MT_2 (MT-2 Metal Zone) con gain bajo, como boost de tono. La hoja DS no lista sus parámetros: ajustar a oído.
- **Alternativa de cab:** 3J900_DS + cab 10MAR1960_412 (Level 50, Low Cut 80 Hz, High Cut 8 kHz).
- **Variante "Night's Blood"** (más cuerpo, tremolo picking): Treble 55, Middle 60, Gate 55, delay apagado.
- Si las EMG suenan muy comprimidas o con fizz: Gain del amp 70, Pres 45.
- Si falta mordida: Tone del DS 70.

## Alternativa TONE3000 (NAM)
El firmware no trae un DS-2 ni el JCM900 4100 exacto. Estas capturas se acercan más al equipo documentado.

| Bloque | Buscar en TONE3000 | Autor / tipo | ESR (Full / Lite) | Enlace |
|---|---|---|---|---|
| AMP (preferida) | "Marshall JCM 900 Ch B w/ SD 805" | obijuan · Amp Head (DI, necesita CAB) | no listado | https://www.tone3000.com/tones/marshall-jcm-900-ch-b-w-sd-805-69753 |
| AMP (alternativa) | "MARSHALL JCM 900 4100" | deathblossomaudio · Amp Head, canal Lead, solo preamp | no listado | https://www.tone3000.com/tones/marshall-jcm-900-4100-45684 |
| DS (pedal) | "BOSS DS-2 Turbo Distortion" | ratchetstrapmedia · Pedal, 6 capturas (modos 1 y 2) | no listado | https://tone3000.com/tones/boss-ds-2-turbo-distortion-5475 |
| DS (alternativa) | "Boss Turbodistorsion DS-2" | raultrathrash · Pedal, posiciones I y II | no listado | https://www.tone3000.com/tones/boss-turbodistorsion-ds-2--29355 |

- Con las capturas de ampli solo, usar el CAB 10MAR1960_412.
- Las capturas de pedal solo sirven si el bloque NAM del MK-300 las acepta; si no, mantener MW-DS1.
- Es probable que estas capturas sean más fieles que el DS-1 usado como sustituto, pero sin reseñas verificables.

Verificado: 2026-11-18.

## Cambios
| Fecha | Cambio | Motivo |
|---|---|---|
| 2026-11-18 | Versión inicial | Generado con el Excel fw73 |
