# Wall Crawler — Vertical Surface Robot

> **Status: Prototype — v2 redesign planned**

Robot with active adhesion capable of moving on vertical surfaces. Built during high school and presented publicly at two separate events.

---

## Recognition

- 🏛️ **Presented at Noaptea Cercetătorilor** (European Researchers' Night) — public science event organised across EU research institutions
- 📰 **Published in Sirius** — technical student journal, Colegiul Național Eudoxiu Hurmuzachi, Rădăuți

---

## Concept

The robot uses an active adhesion mechanism (motorised fan/impeller creating low pressure between chassis and surface) to maintain contact with vertical and inverted surfaces while four driven wheels provide locomotion.

```
         VERTICAL SURFACE
         ┌──────────────┐
         │   WALL       │
         └──────┬───────┘
                │ ← suction / low pressure zone
         ┌──────▼───────┐
         │   CHASSIS    │
         │  [IMPELLER]  │
         │  ●  ●  ●  ●  │  ← 4 driven wheels
         └──────────────┘
```

---

## Hardware

| Component | Role |
|-----------|------|
| Arduino (Uno/Nano) | Main controller |
| DC motors × 4 | Wheel drive |
| Motor driver | H-bridge for 4 motors |
| Fan/impeller motor | Active adhesion |
| Battery pack | Power supply |
| Chassis | Custom 3D printed / machined |

---

## What Worked / What Didn't — v1 Honest Assessment

**Worked:**
- Active adhesion concept — suction pressure was measurable
- Basic locomotion on flat vertical surfaces
- Mechanical structure held together under load

**Didn't work:**
- Insufficient suction pressure for reliable adhesion on all surfaces
- Motor current draw exceeded initial estimates
- Chassis weight vs adhesion force balance not optimised

---

## v2 Planned Improvements

- [ ] CFD analysis of impeller geometry for optimised airflow
- [ ] Lighter chassis — carbon fibre or thin aluminium sheet
- [ ] Brushless motor for impeller — higher RPM, more suction
- [ ] Closed-loop adhesion control — pressure sensor feedback
- [ ] Wheel grip material — silicone or rubber compound
- [ ] optimized electrical wiring( all in one PCB)
---


---

## Author

**Cosmin Leonardo Cozaciuc**  
Electrical Engineering Student — UPB, Bucharest  

