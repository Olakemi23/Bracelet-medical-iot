# 🫀 Bracelet de Monitoring Médical — ESP32 + Python

Projet personnel réalisé dans le cadre de ma candidature en Master Génie Biomédical.

# Objectif
Concevoir un dispositif embarqué de mesure de la fréquence cardiaque (FC) 
et de la saturation en oxygène (SpO2) avec transmission sans fil des données 
et visualisation en temps réel via Python.

# Technologies utilisées
- **Microcontrôleur** : ESP32 (WiFi + BLE intégré)
- **Capteur** : MAX30102 (SpO2 + fréquence cardiaque)
- **Communication** : Bluetooth Low Energy (BLE)
- **Traitement & visualisation** : Python (matplotlib, pandas, pyserial)

## 📁 Structure du projet
bracelet-medical-iot/
├── hardware/       Code embarqué ESP32 (Arduino C++)
├── scripts/        Scripts Python d’acquisition et visualisation
├── data/           Données captées
└── docs/           Schémas de câblage, documentation
