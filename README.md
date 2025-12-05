# ARCH-HUB: AI-Assisted Archaeology Data Workflow Prototype
*A fully local, offline-capable web app for field archaeology documentation and FLL Innovation Project 2025.*

## 🚀 Overview
ARCH-HUB is a single-page, fully local HTML application designed to fix one of archaeology’s biggest challenges: **data workflow fragmentation** across surveying, digging, documenting, storing, and analyzing.

This prototype unifies:
- Image capture  
- Metadata structuring  
- Automatic context logging  
- AI-style image overlays  
- QR-based retrieval  

It was developed as part of a **FIRST LEGO League Innovation Project**, but the architecture is grounded in **real archaeological workflows**.

---

## 🧩 Features

### ✔ Unified Record Model
Supports four types of archaeological data:
- Artifacts
- Context Sheets
- GPR Records
- Stratigraphy Profiles  

All use the same:
- Data model  
- Storage model  
- Workflow pattern  

---

### ✔ Offline-First Architecture
- Runs entirely in the browser  
- No server required  
- Uses `localStorage` for persistent offline storage  
- Base64-encoded images survive full reloads  

Perfect for:
- Field locations with no signal  
- Rapid demos (FLL judging)  
- Privacy-sensitive research  

---

### ✔ AI-Style Image Augmentations
Simulated AI output improves clarity and understanding:

#### GPR:
- Anomaly overlays  
- Boundary detection  
- Adjustable opacity  
- Raw ↔ Overlay mode  

#### Stratigraphy:
- Auto layer separation  
- Feature highlights  
- Adjustable opacity  
- Raw ↔ Overlay mode  

All overlays are stored as structured metadata.

---

### ✔ Artifact & Context Sheet Capture
- Photo upload (base64 persisted)
- Voice-to-text via device keyboard
- Automatic GPS + timestamp capture
- Metadata fields for archaeology
- QR generation for retrieval

---

### ✔ QR Code System
Each record generates a QR payload:
```
ARCHHUB:ART:A-1764917542040
```

Used for:
- Artifact labeling
- Instant record lookup
- Organized physical workflows

---

## 🖥️ Technology Stack

| Component | Description |
|----------|-------------|
| HTML/CSS/JS | App logic & UI |
| localStorage | Offline persistence |
| SVG | System diagrams |
| qrcode.min.js | Local QR generation |
| Zero Dependencies | Everything runs offline |

---

## 📁 Repository Structure
```
/ (root)
├── arch-hub.html
├── qrcode.min.js
├── arch-hub-logo.svg
├── arch-hub-architecture-diagram-neutral.svg
├── arch-hub-architecture-diagram-earthy.svg
├── arch-hub-mini-core-diagram.svg
├── README.md
└── CONTRIBUTING.md
```

---

## 🧪 Running the App
Just open the file below in any browser:

```
arch-hub.html
```

No install, no server, no dependencies.

---

## 📦 Export / Import
Use the built-in buttons to:
- Export full app state as JSON  
- Import JSON to restore  

Includes:
- Images  
- Metadata  
- Overlays  
- QR payloads  

---

## 🔒 Privacy
- No data leaves the device  
- All processing is local  
- Safe for minors + education settings  
- Reliable for field archaeologists  

---

## 📜 License
This project is provided for **educational, research, and FLL Innovation Project use**.  
You may fork, modify, and extend.

---

## 🙌 Credits
Created by a **FIRST LEGO League team** exploring how AI can support archaeologists with better, unified workflows.

---

