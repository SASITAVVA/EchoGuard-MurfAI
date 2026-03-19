# EchoGuard: Context-Aware IoT Auditory Interface

## 🚨 The Problem: "Alarm Fatigue"
Industrial spaces and smart cities depend on blaring, high-decibel alarms, creating massive "alarm fatigue." When a generic siren goes off, nobody knows what's wrong or how urgent it is. People freeze up, delaying response times. Standard robotic text-to-speech fails to convey real urgency.

## 💡 The Solution
EchoGuard bridges real-time sensor networks directly with Murf AI’s low-latency voice API. We dynamically translate raw environmental data into specific, spoken instructions. The core innovation is mapping the threat level to Murf AI's emotional voice profiles:
* **Routine Updates:** The API triggers a calm, authoritative voice model.
* **Critical Hazards:** The API instantly switches to a high-stress, urgent voice model to cut through background noise.

## ⚙️ Tech Stack
* **Backend:** Python
* **Voice Generation:** Murf AI API (FALCON Model)
* **Data Input:** Simulated IoT environmental sensors

*(Note: This repository is actively being structured for the Murf AI Voice Hackathon).*# EchoGuard-MurfAI
