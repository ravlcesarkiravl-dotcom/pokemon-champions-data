## Context

El equipo actual tiene fuertes atacantes físicos (Mamoswine, Basculegion) y especiales (Blastoise-M, Aegislash, Pelipper). Sin embargo, presentaba vulnerabilidades ante core Trick Room populares y era débil frente a movimientos de área (spread) debido a la falta de mecanismos de protección múltiple. El objetivo de este diseño es documentar los cambios técnicos exactos (los sets) necesarios para cubrir estas debilidades.

## Goals / Non-Goals

**Goals:**
- Actualizar el set de Blastoise-M para incluir una respuesta directa contra Fantasmas rápidos y setters de TR.
- Actualizar el set de Pelipper para ofrecer protección a todo el equipo ante ataques dobles.
- Mantener la cohesión del resto del equipo intacta.

**Non-Goals:**
- Cambiar la alineación actual de 6 Pokémon.
- Cambiar estadísticas base (EVs), habilidades o naturalezas existentes. Todo el diseño se enfoca únicamente en el cambio de movimientos.

## Decisions

1. **Blastoise-M: Pulso Oscuro (Dark Pulse) sobre Sorpresa (Fake Out) o Rayo de Hielo (Ice Beam)**
   - *Rationale*: Sorpresa no afecta a Sinistcha ni a Gengar por ser tipo Fantasma. Rayo de Hielo es redundante teniendo a Mamoswine. Pulso Oscuro obtiene bonificación x1.5 gracias a la habilidad Megadisparador, logrando 120 BP, y pega Súper Efectivo x2 a las mayores amenazas (Sinistcha, Gengar), garantizando control de campo.

2. **Pelipper: Guardia Amplia (Wide Guard) sobre Hidrobomba (Hydro Pump)**
   - *Rationale*: Pelipper rara vez usa Hidrobomba teniendo Huracán en lluvia como STAB confiable, además, su precisión (80%) lo hace inestable. Por el contrario, Guardia Amplia bloquea Terremoto de Garchomp, Avalancha de Tyranitar y Aerodactyl, y Erupción / Onda Ígnea de Torkoal y Charizard-Y, protegiendo al valioso Blastoise.

## Risks / Trade-offs

- **[Risk] Falta de ataque de Hielo Especial** → Mitigación: Mamoswine provee el daño Hielo físico (x4 vs Dragones) con STAB. Si Mamoswine cae, Blastoise y Pelipper dependerán de daño masivo neutral de Agua para acabar con los Dragones.
- **[Risk] Predicción de Guardia Amplia** → Mitigación: Requiere buena lectura del rival; si el rival usa movimientos Single-Target previendo el Wide Guard, Pelipper podría desperdiciar el turno.
