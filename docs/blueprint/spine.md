# Myth.OS Design Document (Framework Draft)

---

## 1. Philosophy and Purpose
*The Foundational Stone*

### Purpose
- Explain why Myth.OS exists beyond technical needs.
- Anchor emotional and symbolic intention.
- Align contributors at the values level before touching mechanics.

### Key Content
- Systems are recursive mythologies.
- Story → Structure → Spirit is operational reality.
- Myth.OS is a tool for navigation, exploration, and symbolic becoming.

---

## 2. Core Principles
*The Living Laws*

### Purpose
- Define the non-optional metaphysical rules for any Myth.OS world.

### Core Concepts
- **Narrative Time**: World updates by story pressure, not clocks.
- **Symbolic Navigation**: Movement occurs by meaning, not spatial distance.
- **World Memory**: Worlds remember interactions and evolve.
- **Mythic Layering**: Surface logic overlays deeper symbolic currents.
- **Recursive World Evolution**: Worlds mutate via memory and myth tension.

### Dual-Layered Mapping: Round and Mythic
- **Round Layer**: Concrete spatial coordinates (x, y, z) for players, terrain, and entities.
- **Mythic Layer (Vexotra)**: Emotional-symbolic field overlaying spatial structure.

### Vexotra (Emotional Geography)
- **Default fields**: joy, grief, anger, sadness, lightness, darkness
- **Value range**: normalized floating-point [-1.0 to 1.0]
  - `+1.0` = maximum emotional presence
  - `0.0` = neutral absence
  - `-1.0` = maximum emotional suppression
- Emotional fields are independent; absence is not inverse presence.

- **Optional Mode**: Worlds may opt for open integer accumulation via `eth.os` configuration.

---

## 3. Architecture and Machinery
*The Bones and Vessels*

### Purpose
- Establish technical structure reflecting symbolic metaphysics.

### Core Components
- **Myth Engine**: Interprets structure, time, memory, emotional forces.
- **Navigator**: Translates player input into world actions across Round/Mythic layers.
- **Memory System**: Persistent symbolic and spatial world state.
- **Schema Specification**:
  - Requires `round_coordinates` (x, y, z)
  - Requires `vexotra_profile` (joy, grief, etc.)

### World Configuration (`eth.os`)
- Defines emotional model (`vexotra_mode`)
- Defines active emotional fields (`vexotra_fields`)

---

