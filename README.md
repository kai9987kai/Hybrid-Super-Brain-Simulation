# PROJECT 1X4G: Hybrid Super Brain Simulation

**Hybrid-Super-Brain-Simulation** is a browser-based prototype UI for a **hybrid neuro–quantum–biological simulation** that combines:

- a **Gene Regulatory Network (GRN)** layer (gene interactions + environmental noise),
- a **hybrid neural substrate** (biological neurons + neuromorphic neurons),
- a **learning loop** (reward history / learning progress),
- periodic **genetic modification** (interval + strength, with a manual “force” action),
- a **quantum influence/enhancement** control intended to modulate system dynamics.

The repository currently ships as a single `index.html` page defining the simulation dashboard layout, controls, and parameter surface. :contentReference[oaicite:0]{index=0}

---

## Repository contents

- `index.html` — “PROJECT 1X4G: Hybrid Super Brain Simulation” dashboard UI/spec. :contentReference[oaicite:1]{index=1}

> No additional code, packages, or build tooling are present yet—this is a **UI/spec scaffold** that can be wired to a simulation engine next. :contentReference[oaicite:2]{index=2}

---

## What the UI exposes (current surface)

### Visualization panels
The page is structured around three primary monitoring areas: :contentReference[oaicite:3]{index=3}

- **GRN State Visualization**
- **Neural Activity Monitor**
- **Reward History**
- plus **System Statistics** and **System Logs**.

### Live statistics (placeholders in the current UI)
- **Episode**
- **Current Reward**
- **Avg Reward**
- **Error** :contentReference[oaicite:4]{index=4}

### Simulation controls
- **Start Simulation**
- **Pause**
- **Reset** :contentReference[oaicite:5]{index=5}

---

## Parameters

All parameters are currently specified as UI controls (intended to drive the eventual engine). :contentReference[oaicite:6]{index=6}

### Environment parameters (GRN / world)
- **Number of Genes** (default shown: 10)
- **Gene Interaction Strength** (default shown: 0.5)
- **Environment Noise** (default shown: 0.1)

### Neural system parameters
- **Biological Neurons** (default shown: 100)
- **Neuromorphic Neurons** (default shown: 1000)
- **Firing Threshold (mV)** (default shown: -50)

### Learning parameters
- **Learning Rate** (default shown: 0.001)
- **Discount Factor** (default shown: 0.99)
- **Exploration Rate** (default shown: 0.2)

### Genetic modification
- **Modification Interval** (default shown: 100)
- **Modification Strength** (default shown: 0.1)
- Action: **Force Genetic Modification**

### Quantum processor
- **Quantum Influence** (default shown: 0.3)
- Action: **Apply Quantum Enhancement**

(Each is displayed with a “?” hint marker in the UI.) :contentReference[oaicite:7]{index=7}

---

## Quick start

### Option A — open directly
1. Download/clone the repo:
   ```bash
   git clone https://github.com/kai9987kai/Hybrid-Super-Brain-Simulation.git
   cd Hybrid-Super-Brain-Simulation
