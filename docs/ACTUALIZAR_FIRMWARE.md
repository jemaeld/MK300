# Actualizar presets a un firmware nuevo (73 → 75)

1. Agregar el Excel nuevo en `data/fw75/` (mantener `data/fw73/` como historial).
2. Comparar contra el Excel anterior: modelos nuevos, renombrados, quitados y cambios de parámetros o rangos, hoja por hoja.
3. Anotar las diferencias relevantes en `CHANGELOG.md`.
4. Revisar cada preset:
   - ¿Usa un modelo que cambió o desapareció?
   - ¿Hay ahora un modelo más cercano al equipo real? (por ejemplo un DS-2 en vez del DS-1 usado como sustituto)
   - ¿Cambió algún parámetro o rango?
5. En cada preset actualizado: cambiar el campo `Firmware`, agregar una entrada en **Cambios** y, si ya estaba `final`, subir la versión.
6. Actualizar la tabla de estado del `README.md` y el tag del preset si aplica.

Los presets que no se toquen conservan `Firmware: 73` hasta que se verifiquen.
