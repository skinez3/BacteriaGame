# Bacteria Game (Roblox)

**Play the game here:** [Bacteria Game on Roblox](https://www.roblox.com/share?code=7d12916e34330641af1835b167a1c608&type=ExperienceDetails&stamp=1753439645525)

This project is a multiplayer microscopic survival and strategy game developed on the Roblox platform (using Luau). It blends classic Agar.io-style foraging and growth with deep RPG progression, asymmetric class balancing, PvP combat, and Tower Defense mechanics. 

Players spawn into a massive petri dish as one of five bacteria strains, competing for resources, mutating their genomes, and surviving against both enemy players and AI-driven environmental threats.

---

## Core Gameplay Loop

The game is divided into distinct progression phases, seamlessly transitioning players from a passive foraging experience into active combat and territory control:

1. **Early Game (Levels 1 - 4): Foraging & Mutation**
   Players focus on gathering 9 different types of food scattered across the map. Digesting food grants points used to level up core stats: Digestion Speed, Max Health, and Genome Resistances.
2. **Mid Game (Level 5+): PvP & Scavenging**
   Upon reaching Level 5, PvP combat is unlocked. Players can upgrade their Attack skill to engage enemy strains. Defeated players leave behind "dead bacteria" which can be digested for a massive point boost, creating high-risk, high-reward scavenging zones.
3. **Late Game (Level 10+): Territory Control & AI Threats**
   At Level 10, players unlock the "Cell Division" mechanic, allowing them to sacrifice 2 levels to deploy a stationary Turret. This transforms the game into a localized Tower Defense. Simultaneously, giant AI-controlled Phagocytes begin targeting Level 10+ players, and actively hunt anyone who reaches Level 15.

---

## Key Features & Mechanics

### Asymmetric Class & Genome System
The game features a unique rock-paper-scissors style resistance matrix. Players choose from 5 bacteria classes:
*   `Pseudomonas necrophila` (Genome A)
*   `Salmonella maligna` (Genome B)
*   `Staphylococcus pestis` (Genome C)
*   `Bacillus venenatus` (Genome D)
*   `Vibrio mortiferus` (Genome E)

**The 100% Rule:** Each class produces its own specific genome (granting 100% immunity to it) while having varying degrees of vulnerability (from 0.2 to 0.7) to the other four genomes. Players must strategically upgrade their weak points as they level up.

### Tactical Cell Division (Turrets)
Players can split their cells to place command turrets. These turrets inherit all of the player's current stats (including attack damage) and passively infect the surrounding area with the player's specific genome, locking down rich food areas or defending against rival teams.

### AI Environmental Hazards
To prevent high-level players from dominating the server passively, **Phagocytes** (giant yellow NPCs) are introduced as a PvE balancing mechanic. They roam the map, capable of eating Level 10+ players, and switch to aggressive hunting behavior against Level 15+ players.

### Team Coordination & UI
The game heavily relies on positioning and team play, supported by a dynamic minimap:
*   **Green:** Local Player
*   **Blue:** Teammates 
*   **Cyan:** Player-owned Command Turrets
*   **Purple:** Genome Bots

---

## Tech Stack
*   **Engine:** Roblox Studio
*   **Language:** Luau
*   **Genre:** Multiplayer Survival / RPG / Tower Defense
