## ADDED Requirements

### Requirement: Configuración del Set de Incineroar
El sistema SHALL tener un archivo de set individual para Incineroar (Fuego/Siniestro) con la habilidad Intimidación, naturaleza Cauta (+Def. Esp / -At. Esp), objeto Baya Zarza, los movimientos Sorpresa, Último Turno, Desarme y Envite Ígneo, y un reparto de 32 PS / 32 Def. Esp / 2 Defensa (total 66 EVs).

#### Scenario: Verificación de atributos del set de Incineroar
- **WHEN** se consulta el archivo individual de Incineroar
- **THEN** este MUST contener la habilidad Intimidación, objeto Baya Zarza, los 4 movimientos especificados y EVs totales de exactamente 66.

### Requirement: Rol de Soporte y Pivot de Incineroar
La guía de estrategias SHALL documentar el uso de Incineroar como pivot ofensivo que activa Intimidación al entrar y usa Último Turno para traer a Pelipper de forma segura.

#### Scenario: Pivot seguro hacia Pelipper
- **WHEN** Incineroar usa Último Turno (Parting Shot) sobre el oponente
- **THEN** el rival debe recibir -1 de Ataque y -1 de At. Esp, y Incineroar MUST salir del campo permitiendo la entrada de Pelipper para activar la Lluvia.
