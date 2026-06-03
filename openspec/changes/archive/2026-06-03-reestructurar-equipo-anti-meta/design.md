# Diseño: Reestructuración Anti-Meta y Balance de Lluvia

## Contexto

El metagame de Pokémon Champions presenta combinaciones agresivas de Sol (Mega Charizard Y + Venusaur) y atacantes físicos rápidos (Sneasler + Garchomp con Pañuelo Elección). El equipo actual sufre de un exceso de debilidades de tipo Agua y nulo control de daño físico tras enviar a Aegislash a la banca.

Para solucionarlo, retiramos a Mamoswine y Basculegion, trayendo de vuelta a Aegislash e introduciendo a Incineroar para formar un núcleo defensivo de doble Sorpresa e Intimidación.

## Objetivos / No Objetivos

### Objetivos:
* Desactivar los sets individuales de Mamoswine y Basculegion (marcar como inactivos en la banca).
* Reactivar el set individual de Aegislash (eliminar advertencia de inactividad).
* Crear el archivo de set individual para Incineroar con reparto óptimo de 66 EVs (32/32/2).
* Asegurar que todos los sets individuales activos sumen exactamente 66 EVs.
* Actualizar la guía de estrategias competitivas de dobles con tácticas contra Sol/Planta (Venusaur/Charizard Y), Garchomp (Scarf) y Basculegion (Homenaje Póstumo).

### No Objetivos:
* No se modificará el set de movimientos de Mega-Blastoise para conservar sus ataques potenciados por Megadisparador.
* No se modificará a Archaludon ni a Pelipper más allá de asegurar el reparto de 66 EVs correcto.

## Decisiones Técnicas y de Sets

### 1. Incineroar (Fuego/Siniestro) @ Baya Cidra (Citrus Berry) / Restos (Leftovers)
* **Habilidad:** Intimidación (Intimidate)
* **Movimientos:**
  * Sorpresa (Fake Out)
  * Último Turno (Parting Shot)
  * Desarme (Knock Off)
  * Envite Ígneo (Flare Blitz)
* **EVs (66 en total):**
  * `32 PS / 32 Def. Esp / 2 Defensa` (Naturaleza Cauta / Careful: +SpD, -SpA) o `32 PS / 32 Defensa / 2 Def. Esp` (Naturaleza Agitada / Impish: +Def, -SpA). Esto le da una supervivencia inmensa por el lado físico y especial para pivotar.

### 2. Aegislash (Acero/Fantasma) @ Restos (Leftovers)
* **Habilidad:** Cambio Táctico (Stance Change)
* **Movimientos:**
  * Bola Sombra (Shadow Ball)
  * Cañón Resplandor (Flash Cannon)
  * Sombra Vil (Shadow Sneak)
  * Escudo Real (King's Shield)
* **EVs (66 en total):**
  * `32 PS / 32 At. Esp / 2 Def. Esp` (Naturaleza Apacible / Quiet: +SpA, -Spe).

### 3. Raichu (Eléctrico) @ Baya Yacana (Shuca Berry - reduce daño Tierra)
* **Habilidad:** Pararrayos (Lightning Rod)
* **Movimientos:** Sorpresa, Frote (Nuzzle), Cambiavoltaje, Esfuerzo (Endeavor).
* **EVs (66 en total):**
  * `32 Velocidad / 32 PS / 2 Def. Esp` (Naturaleza Miedosa / Timid).

## Riesgos y Mitigaciones

* **[Riesgo] Debilidad a Tierra de Incineroar y Raichu** -> *Mitigación:* Pelipper es 100% inmune a Tierra por tipo Volador. Se jugará con pivots hacia Pelipper si se predice un ataque de tipo Tierra.
* **[Riesgo] Reducción de daño de Fuego de Incineroar bajo la Lluvia** -> *Mitigación:* El propósito principal de Incineroar es el soporte (Intimidación, Sorpresa, Último Turno, Desarme). Envite Ígneo se reserva para cuando el rival ponga el Sol, convirtiendo su propio clima en nuestra contra.
