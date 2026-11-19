# Satyricon · The Shadowthrone — In the Mist by the Hills (acústica / limpio)

- **Instrumento:** Guitarra
- **Estilo / referencia:** Pasaje central acústico/limpio de "In the Mist by the Hills" (*The Shadowthrone*, 1994)
- **Guitarra / pastillas:** Ibanez RG, EMG activas
- **Firmware:** 73
- **Estado:** borrador
- **Versión:** 0.1
- **Solo modelos del firmware:** sin capturas TONE3000, por indicación del usuario.

> Una reseña describe un pasaje central con guitarra acústica española y luego guitarra distorsionada. El firmware no tiene simulador de acústica, así que esto aproxima ese carácter con un limpio abierto y cab de rango completo.

## Cadena
`GATE → FX → AMP → CAB → EQ → REV` (DS, MOD y DLY apagados)

| Bloque | Modelo MK-300 | Ajustes |
|---|---|---|
| GATE | AI Gate | Gate 10, Bias 50 |
| FX | A Boost (Acoustic) | Gain 40, Bass 45, Mid 50, Treble 60, Level 50 |
| DS | Apagado | - |
| AMP | 1J120_CL (Jazz Chorus 120 Clean) | Gain 15, Level 50, Bass 45, Middle 50, Treble 55, Reso 40, Pres 40, Bright 30 |
| CAB | 39HIFI_OK (HIFI Full Frequency) | Level 50, Low Cut 80 Hz, High Cut 12 kHz |
| EQ | Guitar EQ 6 | 100 Hz −2, 200 Hz 0, 400 Hz −1, 800 Hz 0, 1.6 k +1, 3.2 k +2 |
| REV | Hall | Decay 40, Mix 25, High Pass 30, Low Pass 70, Mod Depth 20 |

## Notas y variantes
- **Más cuerpo de acústica:** Bass 50 en el A Boost y Low Cut 70 Hz.
- **Más oscuro y medieval:** Treble 50, High Cut 9 kHz.
- **Cambio de escena:** al volver al riff distorsionado, cambiar a [distorsion.md](distorsion.md).
- **Volumen entre presets:** si el limpio suena más fuerte, Level del amp 40 (EMG activas).

## Cambios
| Fecha | Cambio | Motivo |
|---|---|---|
| 2026-11-18 | Versión inicial | Generado con el Excel fw73, solo modelos del firmware |
