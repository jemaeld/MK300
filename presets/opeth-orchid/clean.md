# Opeth · Orchid — Clean

- **Instrumento:** Guitarra
- **Estilo / referencia:** Partes limpias y arpegios de *Orchid* (1995), prog / folk
- **Guitarra / pastillas:** Ibanez RG, EMG activas
- **Firmware:** 73
- **Estado:** borrador
- **Versión:** 0.1

> Propuesta propia: no hay equipo documentado para los limpios de este álbum. Antes de las guitarras acústicas, las partes suaves se tocaban con eléctricas limpias.

## Cadena
`GATE → AMP → CAB → EQ → MOD → DLY → REV` (DS apagado)

| Bloque | Modelo MK-300 | Ajustes |
|---|---|---|
| GATE | AI Gate | Gate 15, Bias 50 |
| DS | Apagado | - |
| AMP | 53J900_CH1 (JCM 900 Channel 1 Clean) | Gain 20, Level 50, Bass 45, Middle 45, Treble 60, Reso 40, Pres 45, Bright 30 |
| CAB | 10MAR1960_412 | Level 50, Low Cut 80 Hz, High Cut 9 kHz |
| EQ | Guitar EQ 6 | 100 Hz −2, 200 Hz 0, 400 Hz −1, 800 Hz 0, 1.6 k +1, 3.2 k +1 |
| MOD | Chorus (opcional) | Speed 1.2, Depth 25, Mix 25 |
| DLY | Clean (opcional) | Time 0.4 s, Fb 20, Mix 10 |
| REV | Hall | Decay 45, Mix 20, High Pass 30, Low Pass 60, Mod Depth 20 |

## Notas y variantes
- **Efecto "brillante":** Åkerfeldt ha dicho que antes usaba un limpio con un Small Stone (phaser) para hacerlo más brillante. No está confirmado para *Orchid*. Alternativa: MOD Phaser con Speed 4, MidCut 0, Reso 30, Fb 20.
- **Partes tipo acústica:** el firmware no tiene simulador de acústica. Usar este preset con Treble 65 y Bass 40, o FX "A Boost (Acoustic)" como realce.
- **Volumen entre presets:** si el limpio suena más fuerte que la distorsión, Level 40 (EMG activas).

## Alternativa TONE3000 (NAM)
| Bloque | Buscar en TONE3000 | Autor / tipo | ESR (Full / Lite) | Enlace |
|---|---|---|---|---|
| AMP + CAB | "Laney GH100L Celestion Vintage 30" (usar las capturas limpias del pack) | nordtveit · Amp + Cab, de limpio a alta ganancia | 0.0008 y 0.0015 / 0.0036 y 0.0072 (las dos primeras listadas) | https://www.tone3000.com/tones/laney-gh100l-celestion-vintage-30-77827 |
| Opción extra | "Laney Lionheart Clean" | dedevillas12 · Full Rig | 0.0044 | https://www.tone3000.com/tones/laney--34854 |

- Rig completo: apagar CAB.
- Mismo pack que la distorsión: coherencia entre escenas.
- Probar de la captura de menor ganancia hacia arriba.

Verificado: 2026-11-18.

## Cambios
| Fecha | Cambio | Motivo |
|---|---|---|
| 2026-11-18 | Versión inicial | Generado con el Excel fw73 |
