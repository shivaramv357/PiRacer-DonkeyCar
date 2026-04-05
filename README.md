# PiRacer DonkeyCar 🚗

Autonomous racing car using Raspberry Pi 5 and DonkeyCar framework.

## 🧠 Project Overview
This project focuses on improving autonomous driving performance using multi-dataset training:
- Lane following
- Turn handling
- Recovery from off-track situations

## 📂 Dataset Strategy
- `data_center` → normal driving
- `data_turns` → sharp turns
- `data_recovery` → recovery from deviations

## 🏋️ Training
- Model: Keras Linear
- Epochs: ~59
- Validation Loss: ~0.078
- Multi-dataset training used

## ⚙️ Hardware
- Raspberry Pi 5
- PiCamera
- PiRacer chassis

## 🚀 Future Improvements
- Better recovery stability
- Reduced oscillations
