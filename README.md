<p align="center">
  <img src="preview.png" alt="INTI Virtual Tour Preview" width="800"/>
</p>

<p align="center">
  <a href="https://chong-kai-juan03.github.io/unity-virtual-tour/">
    <img src="https://img.shields.io/badge/View%20Live%20Tour-Click%20Here-brightgreen?style=for-the-badge" alt="View Live Tour"/>
  </a>
</p>

# 🏫 INTI Virtual Tour (Unity WebGL Build)

### 🎮 Overview
This repository contains the **Unity WebGL build files** for the **INTI International College Penang Virtual Tour** project.  
The build allows visitors to explore the INTI campus through an interactive 360° virtual environment.

These files are **compiled output** from the Unity project (not editable source files).  
They are optimized for hosting on **GitHub Pages**, allowing anyone to experience the virtual tour directly in their browser.

---

### 📦 Repository Contents

| Folder / File | Description |
|----------------|-------------|
| **Build/** | Unity-generated runtime files — `.data`, `.wasm`, `.framework.js`, `.loader.js` — required for WebGL execution. |
| **StreamingAssets/** | Contains additional Unity assets used during runtime (e.g., videos, textures). |
| **TemplateData/** | Unity WebGL template resources such as icons, CSS, and loader styles. |
| **index.html** | Main entry point that initializes and runs the Unity WebGL player. |
| **firebase-config.js** | Firebase connection script used for dynamic scene data retrieval. |
| **.gitattributes** | Git LFS (Large File Storage) configuration for managing large Unity build assets. |
| **debug.log** | Logs generated during the Unity build process. |
| **README.md** | This file — project overview and documentation. |

---

### 🌐 Live Demo

Experience the virtual tour online here:  
🔗 **[https://chong-kai-juan03.github.io/unity-virtual-tour/](https://chong-kai-juan03.github.io/unity-virtual-tour/)**

---

### 🧰 Technology Stack
- **Unity Engine (WebGL Build)** – Developed the virtual 3D campus environment.  
- **Firebase Realtime Database** – Stores and retrieves dynamic scene and image data.  
- **GitHub Pages** – Hosts the final build for web access.  
- **Git LFS (Large File Storage)** – Handles large Unity asset files efficiently.

---

### ⚙️ Deployment Workflow
1. The Unity project is built using the **WebGL** target platform.  
2. The exported files (`Build/`, `StreamingAssets/`, `TemplateData/`, `index.html`) are uploaded to this repository.  
3. GitHub Pages automatically serves the files as a static website.  
4. The Firebase SDK connects to the database for live scene data retrieval.  

---

### 🧩 Notes
- This repository contains **only the WebGL build files**.  
  The original Unity project (C# source, prefabs, and scenes) is hosted separately.  
- To modify the virtual environment or logic, refer to the **main Unity source project** below.

---

### 👨‍💻 Author
**Chong Kai Juan**  
INTI International College Penang  
Bachelor of Science (Hons) in Computer Science  

---

### 📎 Related Project
To view the **complete Unity source project**, visit:  
🔗 [https://github.com/Chong-Kai-Juan03/inti-virtual-hub](https://github.com/Chong-Kai-Juan03/inti-virtual-hub)

---

<p align="center">
  <sub>© 2025 INTI International College Penang — Virtual Reality Enhancement Project</sub>
</p>
