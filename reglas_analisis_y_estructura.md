# Directrices de Estructura y Análisis Estratégico

Este documento define las reglas de formato, la organización de archivos y la metodología de análisis táctico para **Pokémon Champions**. Cualquier agente o desarrollador que trabaje en este repositorio debe respetar estas reglas.

## 1. Reglas Generales del Metagame
*Las reglas detalladas sobre EVs (máximo 66 EVs), objetos baneados y mecánicas de Megaevolución se encuentran en el archivo [reglas_pokemon_champions.md](./reglas_pokemon_champions.md).*

## 2. Requisito de Lectura en Tareas de Análisis
Cuando se te solicite realizar análisis estratégicos, proponer counters o modificar equipos, **debes leer y considerar obligatoriamente**:
1. **Reglas del Metagame:** El archivo [reglas_pokemon_champions.md](./reglas_pokemon_champions.md) para cumplir con el límite de 66 EVs y las restricciones de objetos y megaevoluciones.
2. **Tabla de Efectividades e Inmunidades:** El archivo [referencia_tipos.md](./referencia_tipos.md) para respetar las efectividades de tipos e inmunidades validadas para este equipo.
3. **Análisis de Metagame:** La carpeta `OU/` del formato correspondiente (`Dobles/OU/` o `Singles/OU/`) para entender qué Pokémon son populares y qué sets usan.
4. **Análisis de Rendimiento:** La carpeta `Matches/` para buscar misplays previos, debilidades detectadas en combates reales y patrones de juego.
5. **Validación del Equipo:** Cualquier cambio en el equipo activo en `My Team/` debe contrastarse con los puntos anteriores y validar que no rompa el límite de EVs.

## 3. Plantillas Obligatorias de Archivos

### A. Ficha de Pokémon (`My Team/`)
Todos los Pokémon del equipo deben guardarse en archivos individuales con el formato `nombre_set_individual.md` y estructurarse respetando los apartados definidos en la plantilla:
*(Ver plantilla vacía en [templates/my_team_template.md](./templates/my_team_template.md))*
- Información Básica (Tipos, Forma, Origen).
- Habilidad y rol táctico.
- Naturaleza.
- Tabla de Movimientos con propósitos tácticos.
- Tabla de Estadísticas con la distribución exacta de EVs (máx 66).
- Objeto equipado.

### B. Reporte de Combate (`Matches/`)
Cada reporte de batalla debe guardarse en un archivo con formato `fecha_rival.md` dentro de `Matches/` y estructurarse así:
*(Ver plantilla vacía en [templates/match_template.md](./templates/match_template.md))*
- Resultado y alineaciones de ambos jugadores.
- Análisis de turnos clave y sinergias activadas.
- Registro de **Misplays** (errores propios) y **Bloopers** (eventos de suerte/RNG).
- Conclusiones y ajustes sugeridos para el equipo.
