# LibraRed

LibraRed is a **Pokémon FireRed/LeafGreen (Gen 3) decomp rom hack** based on [`pret/pokefirered`](https://github.com/pret/pokefirered) that focuses on **stat rebalancing** to make more Pokémon viable while keeping core Gen 3 gameplay intact.

## Main Changes

### Evolution-stage Base Stat Rebalance
Instead of species having wildly different total base stats, LibraRed uses **BST bands by evolution stage**:

- **Stage 1 (basic):** 360 BST  
- **Stage 2 (middle of 3-stage lines):** 450 BST  
- **Final evolutions + single-stage Pokémon:** 540 BST  

Pokémon keep their identity through **stat distribution**, **typing**, **abilities**, and **movepools**—but are no longer held back primarily by low BST.

### Special Tiers
- **Pseudo-legendaries (final forms):** 570 BST  
- **Legendaries:** 600 BST  
- **Mythicals:** 600 BST  
- **Mewtwo:** 680 BST  

### How Stats Are Adjusted
Base stats are **scaled proportionally** to hit the target BST exactly (with integer rounding), preserving each Pokémon’s overall stat “shape” (fast stays fast, bulky stays bulky, etc.).

## Project Status
Early development. Expect balance iteration and data updates.

## Build / Credits
- Built from the **FR/LG decompilation** project: [`pret/pokefirered`](https://github.com/pret/pokefirered)
- Follow pret’s build instructions for compiling. This repository does not distribute ROM files.
