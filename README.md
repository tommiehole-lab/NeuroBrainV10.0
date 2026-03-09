# 🧬 NeuroBrainV10.0: The Synthetic Connectome

**"What's on your mind?"** — This repository is a bio-inspired AI architecture that simulates 8 distinct regions of the mammalian brain to solve complex, survival-based environments.

## 🧠 Brain Architecture

| Region | Function | Role in V10.0 |
| :--- | :--- | :--- |
| **Prefrontal Cortex (PFC)** | Executive Function | Simulates future moves and **Vetoes** dangerous habits. |
| **Amygdala** | Emotional Memory | **One-Trial Learning** for instant fear/trauma responses. |
| **Hippocampus** | Episodic Memory | Facilitates **Offline Replay (Sleep)** to consolidate daily experiences. |
| **Hypothalamus** | Homeostasis | Manages **Energy levels** and triggers survival drives. |
| **VTA (Dopamine)** | Motivation | Calculates Reward Prediction Error (RPE) to tune learning speed. |
| **Basal Ganglia** | Procedural Memory | Stores successful **Habit Loops** for rapid execution. |
| **Thalamus** | Sensory Gating | Filters environmental noise based on current internal needs. |
| **OFC** | Value Mapping | Assigns long-term "emotional value" to specific spatial coordinates. |

## 🚀 Key Features
- **Homeostatic Drive:** The agent isn't just seeking points; it's fighting to keep its Energy above zero.
- **Veto Logic:** The PFC can override the "instinctual" Basal Ganglia if it predicts a hazardous outcome.
- **Trauma Encoding:** High-pain events (hitting hazards) create permanent "Flashbulb Memories" in the Amygdala.
- **REM Cycle:** Between episodes, the Hippocampus "dreams," replaying high-impact memories to strengthen neural connections.

## 🛠️ Usage
Simply run `neuro_brain.py` with Python 3.x. Watch as the agent evolves from a chaotic newborn into a cautious, efficient navigator.
