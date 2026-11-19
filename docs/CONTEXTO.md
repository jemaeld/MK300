# Contexto para seguir mejorando los presets

Este documento resume lo necesario para retomar el trabajo (con Claude u otra herramienta) sin repetir explicaciones.

## Equipo del usuario
- **Guitarra:** Ibanez RG con pastillas activas EMG (alta salida: conviene bajar el gain de los pedales de distorsión).
- **Procesador:** MK-300, firmware **73** (ver `data/fw73/`).

## Reglas al generar presets
- Usar **solo** los modelos del Excel del firmware vigente.
- Referenciar siempre por la columna **'Nombre MK-300'** (hoja DS) o **'Nombre en MK-300'** (hoja AMP) y el nombre de cada modelo en CAB, MOD, DLY, REV, etc.
- Si no hay un modelo idéntico al equipo real, elegir el más cercano y **dejarlo anotado** en el preset.
- Respetar los rangos de cada parámetro del Excel.

## Hojas del Excel (firmware 73)
| Hoja | Contenido |
|---|---|
| Wah | X-Wah, Funk-Wah, Slide-Wah, Cry-Wah, Wah-Wah, Sense-Wah |
| FX | Wah-Wah, LoFi, Boost (varios), Compress, Pitch, Octave, Ring, Whammy |
| GATE | AI Gate, Soft/Hard/Pro Gate, compresores |
| DS | Pedales de distorsión/overdrive (MW-808, MW-DS1, MW-RAT, MT-2, etc.) |
| AMP | Amplis de guitarra y bajo; algunos son **Full Rig** (traen cab incluido) |
| CAB | Cabinets de guitarra y bajo (Level, Low Cut 20-300 Hz, High Cut 5-18 kHz) |
| EQ | Guitar EQ 6, Bass EQ 7, Norm EQ 10 (±12 dB) |
| MOD | Chorus, Flanger, Tremolo, Phaser, Vibrato, Univibe, etc. |
| DLY | Delays mono y stereo |
| REV | Reverbs mono y stereo |

## Parámetros típicos de AMP
Gain, Level, Bass, Middle, Treble (50 = flat), Reso, Pres, Bright.

## Orden de cadena usado hasta ahora
`GATE → DS → AMP → (CAB, salvo Full Rig) → EQ → MOD → DLY → REV`

## Pendiente
- Pegar en `prompt/PROMPT_PRESETS_MK300.md` el resto del prompt original (se cortó en la sección 3.1).
- Agregar el Excel del firmware 75 en `data/fw75/` y revisar los presets (ver `docs/ACTUALIZAR_FIRMWARE.md`).
- Anotar las pruebas reales en la MK-300 en la sección **Cambios** de cada preset.
