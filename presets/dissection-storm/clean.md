# Dissection · Storm of the Light's Bane — Clean

- **Instrumento:** Guitarra
- **Estilo / referencia:** Partes limpias / arpegios, ambiente oscuro
- **Guitarra / pastillas:** Ibanez RG, EMG activas
- **Firmware:** 73
- **Estado:** borrador
- **Versión:** 0.1

> Propuesta propia: no hay datos documentados de cómo se grababan los limpios. Se mantiene la familia Marshall.

## Cadena
`GATE → AMP → CAB → EQ → MOD → DLY → REV` (DS apagado)

| Bloque | Modelo MK-300 | Ajustes |
|---|---|---|
| GATE | AI Gate | Gate 20, Bias 50 |
| DS | Apagado | - |
| AMP | 53J900_CH1 (JCM 900 Channel 1 Clean) | Gain 25, Level 50, Bass 50, Middle 50, Treble 55, Reso 40, Pres 45, Bright 30 |
| CAB | 10MAR1960_412 | Level 50, Low Cut 80 Hz, High Cut 9 kHz |
| EQ | Guitar EQ 6 | 100 Hz −2, 200 Hz 0, 400 Hz −1, 800 Hz 0, 1.6 k +1, 3.2 k +1 |
| MOD | Chorus | Speed 1.5, Depth 30, Mix 30 |
| DLY | Clean | Time 0.5 s, Fb 30, Mix 20 |
| REV | Hall | Decay 45, Mix 20, High Pass 30, Low Pass 60, Mod Depth 20 |

## Notas y variantes
- **Más oscuro:** quitar el Chorus y subir el Decay del reverb a 55.
- **Más brillante:** Treble 60, Bright 40.
- **Volumen entre presets:** si el limpio suena más fuerte que el distorsionado, bajar el Level del amp a 40 (las EMG activas ya tienen mucha salida).

## Alternativa TONE3000 (NAM)
| Bloque | Buscar en TONE3000 | Autor / tipo | ESR (Full / Lite) | Enlace |
|---|---|---|---|---|
| AMP + CAB | "Marshall JCM 900 Ch A Full Rig" | obijuan · Full Rig, JCM 900 4100 Dual Reverb, canal A (apagar CAB) | 0.0028 y 0.0009 / 0.0144 y 0.0108 | https://www.tone3000.com/tones/marshall-jcm-900-ch-a-full-rig-69936 |

- El pack tiene varias capturas, una con boost. Probar la no boosteada para el limpio.
- Verificar al descargar que incluya un ajuste limpio; la descripción no lo detalla.

Verificado: 2026-11-18.

## Cambios
| Fecha | Cambio | Motivo |
|---|---|---|
| 2026-11-18 | Versión inicial | Generado con el Excel fw73 |
