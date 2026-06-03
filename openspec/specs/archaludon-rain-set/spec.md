# archaludon-rain-set Specification

## Purpose
TBD - created by archiving change implementar-archaludon-mamoswine-dobles. Update Purpose after archive.
## Requirements
### Requirement: Configuración del Set de Archaludon
El sistema SHALL tener un archivo de configuración del set individual para Archaludon (Acero/Dragón) en la carpeta de equipos, con la habilidad Firmeza (Stamina), el objeto Restos (Leftovers), la naturaleza Modesta y los movimientos Electrorrayo, Cañón Resplandor, Pulso Dragón y Protección.

#### Scenario: Verificación de atributos del set de Archaludon
- **WHEN** se consulta el archivo individual de Archaludon
- **THEN** este MUST contener la habilidad Firmeza, el objeto Restos, la naturaleza Modesta y los 4 movimientos seleccionados.

### Requirement: Integración de Estrategia de Lluvia de Archaludon
La guía de estrategias competitivas de dobles SHALL documentar el uso de Archaludon en Lluvia, específicamente su rol como counter de Charizard Y.

#### Scenario: Ejecución de Electrorrayo en Lluvia
- **WHEN** el clima de Lluvia está activo
- **THEN** Archaludon MUST ejecutar Electrorrayo en un solo turno sin cargar, ganando +1 de Ataque Especial y amenazando a Charizard Y.

