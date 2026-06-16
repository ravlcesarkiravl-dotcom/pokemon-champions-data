# Referencia de Tipos y Matchups — Pokémon Champions (Dobles)

Documento de consulta para análisis estratégico del equipo. Incluye correcciones confirmadas en partida y aprendizajes de exploración. **Actualizar cuando el usuario confirme nueva información.**

> Si falta data de un Pokémon del meta (p. ej. Primarina, Dragapult), pedir al usuario el archivo `*_datos_competitivos.md` en `M-2/Dobles/OU/` antes de asumir sets o movimientos.

---

## Efectividad de tipos — confirmado

### Acero vs Hada

| Atacante | Defensor | Multiplicador | Fuente |
|----------|----------|---------------|--------|
| Acero | Hada | **x2** (súper eficaz) | Confirmado por usuario (jun 2025) |

**Nota dual tipo:** En Pokémon **Agua/Hada** (Primarina), Acero es ×2 en Hada y ×0.5 en Agua → **×1 neutral neto**. Cañón Resplandor no es súper eficaz contra Primarina completa, pero sí lo es contra Hada pura.

### Hada vs Siniestro

| Atacante | Defensor | Multiplicador | Fuente |
|----------|----------|---------------|--------|
| Siniestro | Hada | **x0.5** (no muy eficaz) | Confirmado por usuario (jun 2025) |

**Implicación:** Pulso Oscuro y Golpe al Cuello **no son respuesta** contra Primarina (Agua/Hada) ni contra la parte Hada de cualquier Pokémon.

### Siniestro vs Siniestro/Fantasma (Sableye)

| Atacante | Defensor | Multiplicador |
|----------|----------|---------------|
| Siniestro | Sableye (Siniestro/Fantasma) | **x0.5** |

**Implicación:** Pulso Oscuro de Mega Blastoise hace poco daño a Sableye incluso **sin** Pantalla de Luz. Con pantalla, el daño efectivo cae aún más.

### Agua/Hada — Primarina (tipos base del juego)

| Tipo de ataque | Efectividad vs Agua/Hada | ¿Quién lo tiene en el equipo? |
|----------------|--------------------------|-------------------------------|
| Planta | x2 | Nadie |
| Eléctrico | x2 | Archaludon (Electrorrayo), Raichu |
| Veneno | x2 | Nadie |
| Siniestro | x0.5 | Blastoise, Incineroar — **evitar vs Primarina** |
| Agua | x0.5 | Pelipper, Blastoise — **evitar vs Primarina** |
| Hada | — | Nadie |

**Respuesta teórica principal al equipo:** **daño Eléctrico** (Archaludon bajo lluvia con Electrorrayo), no Pulso Oscuro.

---

## Matchups documentados en partida

### Sableye + Primarina (lead ocasional)

**Patrón rival:**
1. Sableye (Timador/Prankster) pone **Pantalla de Luz** con prioridad (+1).
2. Primarina presiona o usa Protección; puede recibir Sorpresa de Incineroar (no es Fantasma).
3. El daño **especial** del equipo queda a la mitad mientras la pantalla esté activa.

**Por qué falla el plan habitual:**
- Blastoise mega + Pulso Oscuro → x0.5 tipo + x0.5 pantalla vs Primarina.
- Pulso Oscuro vs Sableye → x0.5 tipo + pantalla.
- Columna de Agua → x0.5 tipo Agua vs Primarina + pantalla; además depende de PS.
- Doble dependencia de movimientos especiales sin romper pantallas.

**Herramientas que el equipo ya tiene y están subutilizadas:**
- **Electrorrayo** de Archaludon (x2 vs Primarina, especial pero con más base que siniestro resistido).
- **Sorpresa** de Incineroar solo sobre Primarina (Sableye es inmune).
- **Aura Esfera** vs Sableye (neutral x1, mejor que Pulso Oscuro).

**Herramientas que el equipo NO tiene:**
- Romper pantallas (Mofa, Defog, Rompecoraza en otro slot, Infiltrador).
- Daño físico fuerte que ignore Pantalla de Luz (pocos usuarios en el roster actual).

### Fantasmas al frente (Basculegion, Sableye, Dragapult)

- Sorpresa no afecta a tipos Fantasma.
- Incineroar + Raichu con Sorpresa → al menos una Sorpresa muerta si hay Fantasma lead.
- Dragapult disponible en el formato; **Chien-Pao no está disponible**.
- Archivo OU de Dragapult: ver sección Meta OU — Infiltrador 55.9%, set físico.

### Charizard Y y guerra de climas

- Rivales suelen **guardar** Charizard Y y **megaevolucionar después** de que Pelipper active lluvia, para borrar la lluvia con Sequía en el peor momento.
- Primarina aparece **a menudo sin** Charizard Y en la misma partida; es un problema independiente del clima.

---

## Blastoise — notas de set

| Movimiento | Megadisparador (mega) | Notas |
|------------|----------------------|-------|
| Pulso Oscuro | Sí (x1.5) | Útil vs Fantasma **puro** (Gengar, Sinistcha). Resistido por Sableye y Primarina. |
| Aura Esfera | Sí (x1.5) | Neutral vs Sableye; no muy eficaz vs Primarina. |
| Columna de Agua | **No** | Potencia según PS actuales; sin boost de Megadisparador. |
| Rompecoraza | — | ~38% en meta OU; turno de setup; sigue siendo daño especial (afectado por pantallas). |

### Set explorado — Blastoise (4 movimientos)

**Set recomendado en exploración:**

| Slot | Movimiento | Megadisparador | Usar contra |
|------|------------|----------------|-------------|
| 1 | **Hidropulso** | Sí | STAB lluvia; rivales débiles al agua (no Primarina) |
| 2 | **Pulso Oscuro** | Sí (120 BP) | Fantasma/Psíquico: Basculegion, Gengar, Farigiraf, Sinistcha |
| 3 | **Aura Esfera** | Sí | Farigiraf no (inmune); cobertura neutra donde no hay inmunidad Fantasma/Normal |
| 4 | **Protección** | — | Plan D; turnos peligrosos |

**Sacar:** Columna de Agua (depende de PS, sin Megadisparador, ×0.5 vs Primarina).

**No sacar Pulso Oscuro:** sigue siendo la mejor respuesta mega-boosted vs Fantasma puro y Psíquico. Solo **no** usarlo vs Primarina, Sableye ni Milotic (Hada/Siniestro resisten).

### Cuándo NO usar Pulso Oscuro

| Rival | Pulso Oscuro | Hidropulso | Aura Esfera |
|-------|--------------|------------|-------------|
| Primarina (Agua/Hada) | ×0.5 | ×0.5 | ×1 |
| **Sableye (Siniestro/Fantasma)** | ×0.5 | **×1** | **INMUNE** (Fantasma anula Lucha) |
| Farigiraf (Normal/Psíquico) | **×2** ✓ | ×1 | **INMUNE** (Normal anula Lucha) |
| Basculegion (Agua/Fantasma) | **×2** ✓ | ×0.5 | INMUNE |
| Gengar (Fantasma/Veneno) | **×2** ✓ | ×1 | INMUNE |

**Corrección Sableye:** Aura Esfera **no hace daño** — la inmunidad al tipo Lucha viene del tipo **Fantasma**. El tipo Siniestro no quita esa inmunidad; en dual tipo, la inmunidad gana. Contra Sableye, el mejor ataque especial de Blastoise suele ser **Hidropulso (×1 neutral)**, no Aura Esfera ni Pulso Oscuro (×0.5).

Habilidad pre-mega en set actual: Torrente. Meta OU Blastoise: mayoría Curación Pluvial (77.6%).

### Tipos que Blastoise puede aprender (confirmado por usuario)

**No puede aprender Planta.** Tipos disponibles: Normal, Agua, Roca, Tierra, Hielo, Lucha, un par de Dragón, un par de Siniestro y Acero.

**Implicación:** Blastoise no tiene ×2 vs Primarina (Agua/Hada). Cañón Resplandor es ×2 vs Hada pura, pero **×1 neutral** vs Primarina (Agua anula la ventaja Acero→Hada). Rol vs Primarina: limpieza tardía; el KO lo busca Archaludon con Electrorrayo.

---

## Incineroar — nombres de movimientos

| En el set del equipo | Efecto | No confundir con |
|----------------------|--------|------------------|
| Último Turno | Baja At. y At. Esp. del rival; usuario vuelve a la Pokébola | Mofa (Taunt) |
| Última Palabra (dato OU) | Mismo rol pivot en datos del meta, no es Mofa | — |

---

## Correcciones a documentación antigua del repo

Los siguientes razonamientos en `openspec/` o diseños archivados están **obsoletos o incompletos**:

1. **Pulso Oscuro x2 vs Primarina** — Falso: Hada resiste Siniestro.
2. **Pulso Oscuro como herramienta principal vs Sableye** — Falso: Sableye resiste Siniestro.
3. **Golpe al Cuello como counter a Primarina** — Es tipo Siniestro; también x0.5 vs Hada.

---

## Meta OU — Primarina (N.º 730)

**Tipos:** Agua / Hada | **Habilidad más usada:** Torrente (94.7%)

| Movimiento | Uso | Categoría | Nota táctica |
|------------|-----|-----------|--------------|
| Fuerza Lunar | 96.7% | Especial Hada | x2 vs Archaludon y Dragapult (parte Dragón) |
| Aria Burbuja | 78.7% | Especial Agua | STAB agua; ignora sustituto |
| Acuajet | 66.3% | **Físico** Agua | Prioridad; **ignora Pantalla de Luz** |
| Otra Vez | 40.5% | Estado | Puede encerrar a pivots (Pelipper, Incineroar) |

**Objetos frecuentes:** Baya Citrón (45.5%), Agua Mística (17.2%), Restos (15.3%)

**EVs típicos:** 32 At. Esp. + 32 PS (naturaleza Modesta 64.7%)

**Compañeros OU:** Garchomp, Archaludon, Meowscarada, Charizard, Gengar — Sableye no está en top 5 OU pero el usuario lo ha visto en lead con Primarina.

**Implicación para el equipo:** Primarina no solo tanquea — **contraataca**. Acuajet castiga a Blastoise/Raichu frágiles con daño físico bajo pantalla. Fuerza Lunar amenaza a Archaludon.

---

## Meta OU — Dragapult (N.º 887)

**Tipos:** Dragón / Fantasma | **Habilidad más usada:** Allanamiento/Infiltrador (55.9%)

| Movimiento | Uso | Categoría | Nota táctica |
|------------|-----|-----------|--------------|
| Dracoflechas | 68.0% | **Físico** Dragón | Golpea a ambos rivales en dobles |
| Ida y Vuelta | 43.0% | **Físico** Bicho | Pivot rápido |
| Golpe Fantasma | 40.6% | **Físico** Fantasma | |
| Golpe Bajo | 30.3% | **Físico** Siniestro | x0.5 vs Hada (Primarina) |
| Fuego Fatuo | 29.4% | Estado | Quemadura |

**Objetos frecuentes:** Banda Aguante (36.3%), Pañuelo Elección (25.8%)

**EVs típicos:** 32 Ataque + 32 Velocidad (naturaleza Firme/Alegre)

**Compañeros OU:** Charizard, Archaludon, Garchomp, Lucario, Meowscarada

**Implicación para el equipo:** Infiltrador confirma rol **rompe-pantallas con daño físico**. Pero vs Primarina: Dragón y Siniestro pegan x0.5 por Hada. Dragapult resuelve Sableye/pantallas, no remata a Primarina solo.

---

## Información pendiente de agregar

| Recurso | Estado | Para qué sirve |
|---------|--------|----------------|
| `primarina_datos_competitivos.md` | ✅ Agregado | — |
| `dragapult_datos_competitivos.md` | ✅ Agregado | — |
| `milotic_datos_competitivos.md` | No existe | Confirmar Escama Especial en el formato |
| `meowscarada_datos_competitivos.md` | No existe | Compañero frecuente de Primarina (Planta/Siniestro) |
| Tabla de tipos completa del formato | Parcial | Solo entradas confirmadas arriba |

---

## Regla para el asistente

Si no hay archivo OU o confirmación del usuario sobre mecánicas de Pokémon Champions, **no asumir**. Preguntar o marcar como pendiente en este documento.
