<!--
  GitHub PROFILE README — recruiter-grade.
  Setup:
    1. Create a PUBLIC repository named exactly: MdShabazS  (must match your username).
    2. Add this file as README.md at the repo root.
    3. Replace the email/LinkedIn badges below if you want different colors.
    4. (Optional) Replace the "stats" section image URLs once your repo username is public.
-->

<h1 align="center">Mohammed Shabaz S</h1>

<p align="center">
  <b>Embedded Systems &middot; Automotive Electronics &middot; Applied ML</b><br/>
  <sub>ECE Undergraduate &middot; Ballari Institute of Technology and Management &middot; CGPA 8.52 / 10</sub>
</p>

<p align="center">
  <a href="mailto:md.shabaz.2005@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-md.shabaz.2005%40gmail.com-0A66C2?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://linkedin.com/in/shabaz17"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-shabaz17-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/MdShabazS"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-MdShabazS-181717?style=flat-square&logo=github&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Based_in-Ballari,_India-555?style=flat-square">
</p>

---

### About

I design and build **embedded systems and automotive firmware**, with a growing focus on applied computer vision and on-device ML. My recent work spans an ESP32 Body Control Module modeled on production ECU patterns, a multi-projector floor-plan visualization system shipped during my AI Research internship, and a real-time TFLite currency-detection tool for visually impaired users.

Currently exploring the intersection of **automotive electronics, real-time firmware, and edge AI** — and looking for internship and full-time opportunities where embedded engineering meets intelligent systems.

---

### Experience

**AI Research Intern — Deep Learning &amp; Model Development** &middot; *iHelp Robotics, Bangalore (Remote)* &middot; `Mar 2026 — Present`
End-to-end ownership of two production tools: **NexCast Pro** (multi-projector floor-plan visualization) and **VisionPay** (real-time currency detector for the visually impaired). Dataset preparation, model training, computer-vision pipeline, and packaging for offline CPU deployment.

**Virtual Intern — SmartBridge / AICTE** &middot; *Google Cloud Generative AI Track* &middot; `Jul 2025 — Sep 2025`
Structured program on Google Cloud generative AI fundamentals with hands-on cloud labs.

---

### Tech Stack

<table>
<tr><td><b>Embedded</b></td><td>STM32 (CubeIDE, HAL, CubeMX) &middot; ESP32 &middot; ESP8266 &middot; Arduino &middot; Raspberry Pi &middot; FreeRTOS</td></tr>
<tr><td><b>Protocols</b></td><td>UART &middot; I²C &middot; SPI &middot; CAN bus &middot; BLE &middot; Wi-Fi &middot; LoRa</td></tr>
<tr><td><b>Languages</b></td><td>C &middot; C++ &middot; Embedded C &middot; Python</td></tr>
<tr><td><b>ML / Vision</b></td><td>TensorFlow / Keras &middot; MobileNetV2 fine-tuning &middot; TFLite quantization &middot; OpenCV (Hough transforms) &middot; Tesseract OCR &middot; scikit-learn</td></tr>
<tr><td><b>Backend / Web</b></td><td>Flask (REST APIs) &middot; HTML / CSS / JS single-page UIs</td></tr>
<tr><td><b>Cloud / Tools</b></td><td>Google Cloud Platform &middot; Firebase &middot; Linux (bash) &middot; Git &middot; MATLAB / Simulink &middot; STM32CubeIDE</td></tr>
</table>

---

### Featured Work

> **[Automotive Body Control Module — ESP32](https://github.com/MdShabazS/Automotive-Body-Control-Module-ESP32)**
> `ESP32` &middot; `Embedded C/C++` &middot; `State Machines`
> A working ESP32 BCM modeled on production automotive ECU design. Implements a 3-state ignition machine (`OFF` / `ACC` / `ON`), brake-light gating, left/right indicators, hazard mode, audible feedback, and an SSD1306 OLED instrument cluster — all driven by a fully **non-blocking `millis()` event loop** with edge-triggered logging.

> **[NexCast Pro — Intelligent Floor-Plan Projection System](https://github.com/MdShabazS/NexCast_Pro)** &nbsp; *(@ iHelp Robotics)*
> `Python` &middot; `Flask` &middot; `OpenCV` &middot; `Tesseract OCR` &middot; `pygame`
> Web tool that ingests floor plans (PDF / DXF / DWG / image) and runs an OpenCV pipeline (auto-crop, Hough-line wall detection, Hough-circle door-swing detection) plus Tesseract OCR for dimensions and room labels, then projects calibrated 1920 × 1080 zones across **1–12 projectors** through a Flask REST API and a hardened pygame multi-display layer.

> **[VisionPay — Real-Time Currency Detector for the Visually Impaired](https://github.com/MdShabazS/visionpay)** &nbsp; *(@ iHelp Robotics)*
> `TensorFlow` &middot; `MobileNetV2` &middot; `TFLite` &middot; `OpenCV`
> Fine-tuned MobileNetV2 on a custom Indian-banknote dataset (~300 imgs/class) reaching **~93% validation accuracy**, then quantized to TFLite for **~30 FPS real-time CPU inference**. Webcam loop with confidence + margin gating, majority-vote frame smoothing, and offline TTS feedback. Runs fully offline — no GPU, no cloud.

> **[Smart Wellness Desk Assistant — STM32 Nucleo-L476RG](https://github.com/MdShabazS/Smart-Wellness-Desk-Assistant)**
> `STM32` &middot; `HAL` &middot; `Embedded C` &middot; `I²C`
> Embedded wellness monitor on STM32 with ultrasonic posture sensing, ambient light/temperature monitoring, OLED display, and buzzer alerts — built in STM32CubeIDE with HAL drivers and clean modular peripheral abstraction.

---

### Selected Achievements

- **Top 17 Nationally** — NIDAR National Innovation Challenge for Drone Applications and Research *(led electronics integration &amp; payload-release mechanism)*
- **Top 15** — Agent Hack, 8-hour National-Level Hackathon (2025)
- **Google Student Ambassador 2025**
- **Vice Chair** *(Present)* &amp; **Ex-Treasurer**, IEEE Circuits &amp; Systems Society (IEEE CAS), BITM
- **Treasurer**, BITM Robotics Club &middot; **Student Member**, IEEE

---

### Stats

<p align="center">
  <a href="https://github.com/MdShabazS">
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=MdShabazS&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true&count_private=true&hide=issues" />
  </a>
  <a href="https://github.com/MdShabazS">
    <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MdShabazS&layout=compact&theme=transparent&hide_border=true&langs_count=8" />
  </a>
</p>

---

### Contact

Open to **embedded / firmware / automotive** internships and new-grad roles, and to research collaborations in **applied ML on edge devices**.

📧 **[md.shabaz.2005@gmail.com](mailto:md.shabaz.2005@gmail.com)** &middot;
💼 **[linkedin.com/in/shabaz17](https://linkedin.com/in/shabaz17)**

<sub><i>“Bridging embedded systems with the future of automotive intelligence.”</i></sub>
