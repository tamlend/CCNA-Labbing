# Lab 1: Connecting Devices (Jeremy's IT Labs)

**Date Completed**: May 28, 2026

### Lab Objective
Correctly cable a multi-site topology (routers, switches, PCs, and server) using the proper cable types while respecting distance limitations and Auto-MDIX rules.

### Key Concepts Practiced
- Auto-MDIX not supported → must choose correct cable type manually
- Straight-through cables: PC ↔ Switch, Switch ↔ Router
- Crossover cables: Switch ↔ Switch, Router ↔ Router
- Fiber optic cables:
  - Single-mode fiber (R1–R3, 3 km)
  - Multi-mode fiber (R3–R4, 250 m)

### Steps Completed
1. Connected all end devices (PC1, PC2, PC3, SRV1) using copper straight-through cables.
2. Connected switches to each other and to routers using correct crossover or straight-through cables.
3. Connected routers:
   - R2–R1: copper crossover (50 m)
   - R1–R3: single-mode fiber (3 km)
   - R4–R3: multi-mode fiber (250 m)

### Screenshots

**Before** – All devices present but unconnected  
![Before Topology](./before-topology.png)

**After** – Fully connected topology with correct cables  
![After Topology](./after-topology.png)
### Why This Matters
Physical cabling knowledge (copper vs fiber, pinouts, distance limits) is critical for racking servers, patching switches, and maintaining structured cabling in data centers.
