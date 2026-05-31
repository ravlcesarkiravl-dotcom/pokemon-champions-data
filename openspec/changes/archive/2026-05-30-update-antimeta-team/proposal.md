## Why

El equipo actual tiene vulnerabilidades clave contra equipos de Trick Room (como Sinistcha) y es susceptible a ataques de área (spread moves) como Terremoto y Onda Ígnea. Para hacer de este un equipo realmente anti-meta, necesitamos optimizar los movimientos de los Pokémon existentes (Blastoise y Pelipper) sin sacrificar la cobertura actual. Esto nos dará ventaja frente a las estrategias dominantes de la escena competitiva (Dobles OU - Megaevolución).

## What Changes

- Modificación del set de movimientos de Blastoise-M:
  - Mantiene: Columna de Agua, Aura Esfera, Protección
  - **Nuevo**: Pulso Oscuro (reemplaza Rayo de Hielo)
- Modificación del set de movimientos de Pelipper:
  - Mantiene: Huracán, Viento Afín, Protección
  - **Nuevo**: Guardia Amplia (reemplaza Hidrobomba)
- Mantenimiento del resto del equipo intacto (Basculegion, Aegislash, Mamoswine, Raichu) para conservar la sinergia actual (como la cobertura de Hielo con Mamoswine x4 Dragón).

## Capabilities

### New Capabilities
- `blastoise-dark-pulse`: Incorporación de Pulso Oscuro en Blastoise-M para tener daño Súper Efectivo x2 contra Fantasmas (como Sinistcha y Sableye) potenciado por Megadisparador (Mega Launcher).
- `pelipper-wide-guard`: Integración de Guardia Amplia en Pelipper para bloquear todos los movimientos de área rivales (spread moves) que amenazan al equipo, especialmente útiles durante el posicionamiento clave.

### Modified Capabilities
- (Ninguna existente se modifica a nivel de requerimiento de software, pero el meta de combate se ve directamente afectado).

## Impact

- **Sets Individuales:** `blastoise_set_individual.md` y `pelipper_set_individual.md` serán actualizados con los nuevos movimientos.
- **Sinergias:** El equipo se vuelve resistente a movimientos spread y mejora significativamente su matchup contra Trick Room y equipos bulky fantasma, sin alterar sus respuestas frente a climas o dragones (a cargo del resto del roster).
