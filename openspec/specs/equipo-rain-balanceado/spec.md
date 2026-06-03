# equipo-rain-balanceado Specification

## Purpose
TBD - created by archiving change reestructurar-equipo-anti-meta. Update Purpose after archive.
## Requirements
### Requirement: Alineación Activa del Equipo
El equipo activo SHALL estar compuesto por Pelipper, Blastoise, Archaludon, Raichu, Incineroar y Aegislash. Los archivos individuales de Mamoswine y Basculegion MUST marcarse con la advertencia de inactividad `[!WARNING]`.

#### Scenario: Sets inactivos de Mamoswine y Basculegion
- **WHEN** se consultan los archivos de Mamoswine y Basculegion
- **THEN** estos MUST contener la advertencia `ESTE POKÉMON NO SE ENCUENTRA ACTIVO EN EL EQUIPO ACTUAL` en la parte superior.

### Requirement: Reparto de EVs del Equipo Activo
Todos los Pokémon activos MUST tener exactamente 66 EVs totales distribuidos en sus fichas individuales, con un máximo de 32 en cualquier estadística.

#### Scenario: Verificación de EVs de todos los sets activos
- **WHEN** se suman todos los EVs de un set activo
- **THEN** el total MUST ser exactamente 66, con distribución 32 / 32 / 2 en las estadísticas priorizadas.

### Requirement: Guía de Estrategias Actualizada
La guía `guia_estrategias_dobles.md` SHALL documentar cuatro escenarios de combate con el nuevo equipo de Lluvia Balanceada: contra Sol/Planta (Incineroar + Archaludon), contra Físicos rápidos (Garchomp Scarf y pivot a Pelipper), contra Bloqueadores de Prioridad (Farigiraf), y contra Basculegion rival (Homenaje Póstumo).

#### Scenario: Apertura contra Sol con Incineroar
- **WHEN** el rival lidera con Mega Charizard Y y Venusaur
- **THEN** la guía MUST especificar abrir con Incineroar + Archaludon para absorber ataques tipo Planta y Fuego sin exponer Pokémon de tipo Agua en el campo.

### Requirement: Objetos Únicos por Pokémon
Ningún Pokémon activo MUST compartir el mismo objeto con otro miembro del equipo. Los objetos asignados son: Pelipper (Banda Aguante), Blastoise (Blastoisita), Archaludon (Restos), Raichu (Baya Pasio), Aegislash (Baya Cidra), Incineroar (Baya Zarza).

#### Scenario: Verificación de objetos únicos
- **WHEN** se revisan todos los objetos de los sets activos
- **THEN** ningún objeto MUST repetirse entre los 6 miembros del equipo.

