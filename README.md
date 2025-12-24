# OAM-DNN-Beamforming
Synthetic dataset, training code, and trained model for ML-based OAM beam divergence compensation
# OAM Beamforming with Deep Learning

This repository contains the complete implementation of the work presented in *"Machine Learning for Intelligent Beam Divergence Compensation in Orbital Angular Momentum-Based Wireless Communication Systems"*.

It includes:
- Synthetic dataset generation code
- DNN training pipeline
- Trained model weights
- Visualization tools
- Manuscript PDF

All components are designed for full reproducibility.

## 📂 Folder Structure

- `/data`: Synthetic dataset (`oam_dataset.npz`)
- `/models`: Trained Keras model (`oam_beamformer_model.h5`)
- `/notebooks`: Interactive Jupyter notebooks for generation, training, and visualization
- `/src`: Python scripts for automation
- `/paper`: Final manuscript
- `requirements.txt`: Required Python packages

## 🧪 How to Reproduce

### 1. Install Dependencies
```bash
pip install -r requirements.txt
