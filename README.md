<h1 align="center">Hi, I'm Mangesh Vivek Sarde</h1>
<h3 align="center">
Electronics & Communication Engineering Undergraduate · RCOEM Nagpur<br/>
Full-Stack Development • Embedded Firmware • AI/ML Systems • Wireless Sensing
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/mangesh-sarde">LinkedIn</a> •
  <a href="mailto:mangeshsarde6@gmail.com">Email</a> •
  <a href="https://profile-henna-delta.vercel.app">Portfolio & Live Demos</a> •
  <a href="https://github.com/Mangesh46">GitHub</a>
</p>

---

## 🧑‍💻 About Me

Pre-final year **ECE undergraduate** building at the intersection of  
**embedded firmware, wireless sensing, AI/ML, and full-stack development**.

I ship real-world systems end-to-end — from **bare-metal C firmware on ESP-IDF**  
to **Wi-Fi CSI signal pipelines, YOLOv8 inference servers, React dashboards, and production REST APIs** —  
with focus on **reliability, low latency, and measurable outcomes**.

- 📡 **Wireless & RF:** Wi-Fi CSI sensing, 5G core concepts, RF-based passive detection, network slicing  
- 🔨 **Embedded Firmware:** ESP32, ESP-IDF, BLE GATT, ESP-NOW, FreeRTOS, bare-metal C  
- 🤖 **AI / ML:** YOLOv8, CNN-BiLSTM, TensorFlow, PCA, Scikit-learn, Groq LLM (Llama 3.3 70B)  
- 🌐 **Full-Stack:** MERN stack, REST APIs, JWT auth, real-time SSE streaming, React dashboards  
- 🏆 Recognized at **IIT BHU · IIT Indore · VNIT Nagpur · IIT Bombay** — 4 awards, 12+ competitions  
- 💼 6-month internship building production IoT firmware + biosensor backend at Sarvaksh Communications

> **Live demos, architecture diagrams, and source code for all projects:** [profile-henna-delta.vercel.app](https://profile-henna-delta.vercel.app)

---

## 🛠️ Technical Skills

### AI / ML & Data Science
`YOLOv8` • `TensorFlow` • `CNN-BiLSTM` • `Scikit-learn` • `PCA` • `Time-Series Classification`  
`Groq LLM (Llama 3.3 70B)` • `NDVI/EVI Index Computation` • `Signal Processing` • `FFT`

### Wireless & Embedded
`Wi-Fi CSI` • `RF Passive Sensing` • `C (ESP-IDF / Bare-metal)` • `ESP32` • `BLE GATT` • `ESP-NOW`  
`FreeRTOS` • `Concurrency & Semaphores` • `MQTT` • `5G Network Slicing`

### Full-Stack & APIs
`JavaScript (ES6+)` • `React.js` • `Node.js` • `Express.js` • `Flask` • `FastAPI`  
`MongoDB` • `REST APIs` • `JWT Authentication` • `SSE` • `Flutter (Dart)` • `HTML5` • `CSS3`

### DevOps & Tools
`Git` • `GitHub Actions` • `Docker` • `Linux` • `GCP (Certified)` • `Vercel` • `Render` • `Hugging Face Spaces`

---

## 🚀 Projects

### 🛣️ Crackathon — Road Damage Detection with YOLOv8
**Python · YOLOv8s · FastAPI · React · Docker · Hugging Face Spaces · Leaflet | 2025–2026**

Built for the Crackathon competition at IIT Bombay (Team sardemv).

- Trained **YOLOv8s at 1024×1024 resolution** on NVIDIA Tesla P100 — 5 damage classes (longitudinal/transverse/alligator cracks, potholes, other corruption)
- Key insight: standard 640px training causes thin cracks to disappear; pushing to 1024px was the biggest accuracy lever
- Deployed **FastAPI inference server on Hugging Face Spaces** (Docker); inference validated on RTX 2050
- Built **Nagpur Road Inspector** — interactive Leaflet map with 75 GPS inspection points across 8 city zones, Mapillary street-level imagery, auto-scan, real-time bounding box overlay, and 0–100 condition severity scores

🔒 Main repo private · Frontend live at [mangesh46.github.io/crackathon-frontend](https://mangesh46.github.io/crackathon-frontend/nagpur_inspector.html)

---

### 📡 CSISense v1.0 — Wi-Fi CSI Passive Intrusion Detection
**C · ESP-IDF · ESP32 · Wi-Fi CSI · PCA · Supervised ML · Python | 2025**

- Wrote **bare-metal C firmware on ESP-IDF** for dual ESP32 nodes capturing Wi-Fi Channel State Information
- Designed a **7×7 RF sensing grid** (49 monitoring points) with Tx–Rx node pairs
- CSI amplitude/phase data piped to a Python ML pipeline (PCA + supervised classification)
- Achieved **92%+ intrusion detection accuracy** with no cameras — pure RF passive sensing
- Privacy-first: no visual data, no faces — only radio wave disturbance analysis

🔒 Private repository — architecture & demo at [profile-henna-delta.vercel.app](https://profile-henna-delta.vercel.app)

---

### 👟 AirShoes v1.0 — Edge-Aware Smart Wearable with Real-Time Dashboard
**C · ESP32 · React · Flask · MongoDB · TensorFlow · CNN-BiLSTM | 2024–2025**

- **ESP32 bare-metal firmware** for IMU + optical sensor fusion (gait, SpO₂, heart-rate, proximity collision)
- **CNN-BiLSTM model** for 6-class real-time activity recognition under power and latency constraints
- WiFi RSSI Kalman filter with 10-sample rolling variance for pre-contact proximity detection (elderly safety)
- 3-tier intent framework (Alert · Health · Telemetry) simulating 5G network slicing at the application layer
- Real-time React dashboard with live telemetry and conditional UI state
- 🥈 **2nd Prize — VNIT Nagpur 5G Lab Summer School 2025 (50+ participants)**

🔒 Private repository — architecture & demo at [profile-henna-delta.vercel.app](https://profile-henna-delta.vercel.app)

---

### 🔬 GlucoVision v3.1 — Non-Invasive Glucose Biosensor Platform
**C · ESP-IDF · ESP-NOW · BLE GATT · Python Flask · Flutter · Raspberry Pi | 2025–2026**

Built during internship at Sarvaksh Communications Technologies Pvt. Ltd.

- Bare-metal **ESP32-C3 firmware** with ESP-NOW mesh + BLE GATT protocol bridging across 3 embedded devices
- RGB LED (470/525/625 nm) sequential illumination + dual photodiode ADC + 12MP Pi Camera for colorimetric sweat glucose detection (GOx/HRP/TMB chemistry) — target LOD 0.01 mM
- Designed 12-stage async capture pipeline; resolved 4 firmware bugs (race condition, thread blocking, packet mismatch, duplicate capture)
- Achieved **<5% packet loss** under high-concurrency BLE traffic; **cut latency from 17 s → under 2 s**
- Flask REST API + SSE real-time dashboard; Flutter Android app for live plantar-pressure heatmap visualization

---

### 🏥 DHIMS v2.0 — Digital Healthcare Information Management System
**Node.js · Express.js · React 18 · MongoDB Atlas · Groq LLM · SHA-256 · Vercel + Render | 2024–2025**

- Secure full-stack MERN platform deployed on **Vercel + Render + MongoDB Atlas** for student university healthcare
- **SHA-256 tamper-evident hashing** on every prescription and certificate: any field alteration invalidates the 8-character verification code — cryptographically auditable docs
- **41-endpoint Express REST API** with JWT role-based access (student/doctor), OTP email verification, rate limiting
- Integrated **Groq Llama 3.3 70B AI health chatbot** with conversation history and patient context (14,400 req/day free tier)
- 🏁 **National Finalist — IIT Indore Fluxus 2025**
- 🎤 **International Conference Presenter — IIT BHU Spirit 2025**

🌐 Live at [dhims-hgbe.vercel.app](https://dhims-hgbe.vercel.app) · Public repo

---

### 🌾 Crop Health Dashboard — AI Agricultural Monitoring
**React · Flask · Python · Scikit-learn · Chart.js · REST APIs | 2025**

- Computes **NDVI, EVI, and NDWI** vegetation indices from standard RGB field photos
- ML health classifier at **92% accuracy**, <5 s processing — deployable on a regular server without drones or multispectral cameras
- Full-stack dashboard with interactive Chart.js visualizations and smart irrigation scheduling recommendations
- 🥉 **3rd Rank Nationally — Pratikruti 2024, YCCE Nagpur**

🔒 Private repository — demo at [profile-henna-delta.vercel.app](https://profile-henna-delta.vercel.app)

---

## 🏆 Achievements

| Award | Event | Year |
|---|---|---|
| 🥈 2nd Prize | VNIT Nagpur 5G Lab Summer School | 2025 |
| 🏁 National Finalist | IIT Indore Fluxus 2025 | 2025 |
| 🎤 Conference Presenter | IIT BHU Spirit 2025 (Health-Tech & AI) | 2025 |
| 🥉 3rd Rank National | Pratikruti 2024, YCCE Nagpur | 2025 |
| 🤝 Participant | IIT Bombay Crackathon (Team sardemv) | 2025–26 |
| ✅ Participant | BITS Pilani · HP · EY · IIT Delhi · ISEA · PRAGYAN | 2024–26 |

---

## 📜 Certifications

- 📘 **Applied Linear Algebra for Signal Processing, Data Analytics & ML** — NPTEL (Jul–Oct 2025)
- 📘 **AI and Machine Learning on Google Cloud** — GCP Certified
- 📘 **5G and 6G Wireless Technologies** — NIT Warangal

---

## 📫 Contact

- 📧 **mangeshsarde6@gmail.com**
- 🌐 **[profile-henna-delta.vercel.app](https://profile-henna-delta.vercel.app)** — portfolio, live demos & architecture
- 📍 Nagpur, Maharashtra, India
- 💼 **[linkedin.com/in/mangesh-sarde](https://www.linkedin.com/in/mangesh-sarde)**

---

> *From RF sensing grids to YOLOv8 inference servers — building systems that work in the real world.*
