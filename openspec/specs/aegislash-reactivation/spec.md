# aegislash-reactivation Specification

## Purpose
TBD - created by archiving change reestructurar-equipo-anti-meta. Update Purpose after archive.
## Requirements
### Requirement: Reactivación del Set de Aegislash
El archivo `aegislash_set_individual.md` MUST estar activo (sin advertencia de inactividad), con habilidad Cambio Táctico, naturaleza Apacible (+At. Esp / -Ataque), objeto Baya Cidra, movimientos Bola Sombra, Cañón Resplandor, Sombra Vil y Escudo Real, y un reparto de 32 PS / 32 At. Esp / 2 Def. Esp (total 66 EVs).

#### Scenario: Verificación de estado activo de Aegislash
- **WHEN** se consulta el archivo individual de Aegislash
- **THEN** este MUST NOT contener la advertencia de inactividad `[!WARNING]` y MUST reflejar un total de 66 EVs distribuidos como 32/32/2.

### Requirement: Counter de Sneasler con Aegislash
La guía de estrategias SHALL documentar que Aegislash es inmune a los STABs de Sneasler (tipo Lucha y Veneno) y puede usar Escudo Real para reducir el Ataque del rival en -1.

#### Scenario: Inmunidad a Sneasler
- **WHEN** Sneasler intenta usar A Bocajarro (tipo Lucha) o Garra Nociva (tipo Veneno) contra Aegislash
- **THEN** el ataque MUST no causar ningún daño al Aegislash por inmunidad de tipo.

