# OAM Beamforming with Deep Learning

This repository supports the manuscript *"Machine Learning for Intelligent Beam Divergence Compensation in OAM-Based Wireless Communication Systems"*.

It contains:
- Synthetic dataset generation code
- DNN training pipeline
- Trained model
- Visualization tools
- Final manuscript

All components are designed for full reproducibility as required by *Array*.

## 📂 Contents

- `/data`: Synthetic dataset (`oam_dataset.npz`)
- `/models`: Trained Keras model (`oam_beamformer_model.h5`)
- `/notebooks`: Interactive Colab-style notebooks
- `/src`: Clean Python scripts
- `/paper`: Submitted manuscript PDF
- `/figures`: Publication-ready plots
- `requirements.txt`: Dependencies
- `LICENSE`: Open license

## ▶️ How to Reproduce Results

### 1. Install dependencies
```bash
pip install -r requirements.txt
