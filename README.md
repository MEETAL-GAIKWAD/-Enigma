# 💓 VitalGuard AI — Predictive Health Monitoring System

> ⚠️ **This repository contains a UI/Frontend Demo only.**  
> Built for **Enigma 4.0 — Breaking Enigma Hackathon 2026** organized by ACM Student Chapter, VIT Pune.  
> The AI models, wearable integrations, and backend systems shown in the interface are simulated with mock data for demonstration purposes.

---

## 🚀 Live Demo

> Open `index.html` in any browser — no installation or server required.

---

## 💡 Project Concept

**VitalGuard AI** is a concept for a Predictive Health Monitoring System designed to solve a critical gap in chronic patient care:

> *Chronic patients are monitored only 3–4 times a year during doctor visits. That leaves 361 days completely unmonitored — and most health emergencies happen in between.*

VitalGuard AI proposes a **Digital Health Twin** — a personalized AI model per patient that:
- Continuously ingests vitals from wearables and smartphones
- Learns the patient's unique health baseline (not population averages)
- Detects anomalous trends **6–12 hours before a crisis** using an LSTM neural network
- Automatically alerts doctors, caregivers, and the patient with severity-scored notifications

**Tagline:** *"From Reactive Care to Predictive Health — Your Doctor, Always On."*

---

## 🖥️ What's in This Demo

This repository is a **pure frontend UI demo** built with HTML, CSS, and vanilla JavaScript. It demonstrates what the full product would look like with fully working backend and AI integration.

### Pages Included

| Page | File | Description |
|------|------|-------------|
| 🏠 Landing Page | `index.html` | Hero section, features overview, tech stack |
| 🧑‍⚕️ Patient Dashboard | `patient.html` | Live vitals, AI risk prediction, alert timeline |
| 👨‍⚕️ Doctor Dashboard | `doctor.html` | Patient list, critical alerts, alert feed |

### UI Features
- ⚡ Animated ECG/heartbeat line on hero
- 📊 Live-updating vitals charts (Chart.js)
- 🔮 AI Risk Prediction panel with animated confidence score
- 🚨 Critical alert modal with patient vitals
- 💊 Glassmorphism card design throughout
- 🌙 Dark theme with neon violet + cyan accents
- 📱 Fully responsive (mobile + desktop)
- 🔔 Toast notification system

> All vitals, patient names, and alert data shown are **hardcoded mock data** for demo purposes only.

---

## 🧠 Proposed Full System Architecture

> The following is the **planned/conceptual architecture** — not implemented in this demo.
