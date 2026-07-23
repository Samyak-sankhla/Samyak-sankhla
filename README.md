<div align="center">

# Samyak Sankhla

### `Computer Vision & Edge AI Engineer` · `Robotics` · `Embedded ML`

**Building intelligent systems that run on the edge — from the model to the metal.**

<br/>

![B.Tech CS](https://img.shields.io/badge/B.Tech-Computer%20Science-4B0082?style=for-the-badge&logo=googlescholar&logoColor=white)
![CGPA](https://img.shields.io/badge/CGPA-9.07%2F10-8A2BE2?style=for-the-badge&logo=academia&logoColor=white)
![Location](https://img.shields.io/badge/Bengaluru-India-6A0DAD?style=for-the-badge&logo=googlemaps&logoColor=white)

<a href="https://www.linkedin.com/in/samyak-sankhla/"><img src="https://img.shields.io/badge/LinkedIn-4B0082?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:samyaksankhla3@gmail.com"><img src="https://img.shields.io/badge/Email-6A0DAD?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/Samyak-sankhla"><img src="https://img.shields.io/badge/GitHub-1a0033?style=for-the-badge&logo=github&logoColor=8A2BE2" /></a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Samyak-sankhla&label=Profile%20Views&color=8a2be2&style=flat-square)
![Followers](https://img.shields.io/github/followers/Samyak-sankhla?label=Followers&style=flat-square&color=6a0dad)
![Stars](https://img.shields.io/github/stars/Samyak-sankhla?label=Stars&style=flat-square&color=4b0082)

</div>

---

## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> About Me

```typescript
const samyak = {
  role: "Computer Vision & Edge AI Engineer",
  focus: ["Real-Time Perception", "Embedded ML", "Robotics", "Distributed Systems"],
  currentlyBuilding: "Intelligent systems that run on the edge",
};
```

I'm a **software engineer** specializing in **Computer Vision, Edge AI, and Robotics**, with a strong foundation in **full-stack development** and a **product engineering mindset**. My work spans real-time multi-sensor detection pipelines, autonomous robotic control, and edge-ML systems deployed on constrained hardware.

I focus on shipping **production-grade, end-to-end systems** — from deep learning models and embedded firmware to distributed sensor fusion and ROS2 robotics stacks. I care about performance, reliability, and building things that work in the real world.

**AI/ML expertise:** deep learning (PyTorch), computer vision (OpenCV, YOLOv8, RF-DETR), classical ML pipelines, and edge model optimization for microcontroller inference.

**🚀 Open To:** Software Engineering · AI/ML Engineering · Robotics · Full-Stack roles and collaborations.

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> Tech Stack

#### Languages
![Languages](https://skillicons.dev/icons?i=python,java,c&theme=dark)
![SQL](https://img.shields.io/badge/SQL-4B0082?style=flat-square&logo=postgresql&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-6A0DAD?style=flat-square&logo=arm&logoColor=white)

#### Frontend
![Frontend](https://skillicons.dev/icons?i=react,html,css,tailwind,js&theme=dark)

#### Backend & Databases
![Backend](https://skillicons.dev/icons?i=flask,mysql,mongodb&theme=dark)

#### AI / ML & Robotics
![AIML](https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,ros,sklearn&theme=dark)

#### Cloud, DevOps & Tooling
![Tooling](https://skillicons.dev/icons?i=git,github,linux,vscode&theme=dark)

---

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="28"> AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:------|:-----------:|:--------|
| **Computer Vision** | ⭐⭐⭐⭐⭐ | Object detection (YOLOv8, RF-DETR), tracking (CSRT), ArUco pose estimation, camera-to-world transforms |
| **Edge / Embedded ML** | ⭐⭐⭐⭐⭐ | PyTorch CNNs reimplemented in C for on-device inference (Teensy 4.1), model optimization |
| **Robotics & Control** | ⭐⭐⭐⭐ | ROS2 (Humble), Gazebo simulation, autonomous control, sensor fusion |
| **Classical ML** | ⭐⭐⭐⭐ | Feature engineering, PCA, cross-validation, statistical validation, benchmarking |
| **Remote Sensing** | ⭐⭐⭐⭐ | Supervised LULC classification, Landsat imagery, Google Earth Engine |
| **DSP & Signal Fusion** | ⭐⭐⭐⭐ | TDOA localization, multi-microphone bearing estimation, LoRa fusion |

</div>

---

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28"> Featured Projects

<details>
<summary><b>🎯 Distributed Acoustic Event Detection & Localization Network</b></summary>
<br/>

An end-to-end edge-ML sensor network for real-time gunshot detection and source localization, spanning ML, embedded firmware, DSP, and distributed sensor fusion.

| Attribute | Detail |
|:----------|:-------|
| **Stack** | C, Python, PyTorch, LoRa, Teensy 4.1, Raspberry Pi |
| **Scale** | Multi-node distributed sensor network |
| **Performance** | Real-time on-device CNN inference on microcontrollers |
| **Security** | On-device inference — no raw audio leaves the node |
| **Impact** | Field-tested prototype for acoustic event localization |
| **Repository** | [acoustic-gunshot-localization](https://github.com/Samyak-sankhla/acoustic-gunshot-localization) |

Built a PyTorch CNN and reimplemented it in C for real-time inference on Teensy 4.1 microcontrollers. Estimated direction-of-arrival via multi-microphone TDOA, then fused bearings from multiple nodes over LoRa to triangulate source position at a Raspberry Pi base station.

</details>

<details>
<summary><b>🚁 Autonomous Drone Landing on a Moving Platform</b></summary>
<br/>

A vision-guided autonomous landing system that tracks and lands a drone on a moving platform using only a downward-facing camera — no ground-truth pose.

| Attribute | Detail |
|:----------|:-------|
| **Stack** | Python, C++, ROS2 Humble, OpenCV, Gazebo |
| **Scale** | Multi-package ROS2 stack + custom C++ physics plugin |
| **Performance** | Latency-compensated moving-target pursuit |
| **Security** | Fully onboard vision — no external positioning dependency |
| **Impact** | Robust landing on moving platforms via vision alone |
| **Repository** | [DroneLanding](https://github.com/Samyak-sankhla/DroneLanding) |

Used OpenCV ArUco pose estimation with a camera-to-world transform for localization. Designed a 6-state landing controller with velocity feedforward and linear position prediction to compensate for control latency, implemented across a multi-package ROS2 stack with a custom C++ Gazebo physics plugin.

</details>

<details>
<summary><b>🧠 ChaosNet-Based ML for Autism Spectrum Disorder Prediction (Capstone)</b></summary>
<br/>

A leakage-free ML pipeline coupling ChaosFEX chaotic feature extraction with a large classifier benchmark on the ABIDE-I rs-fMRI dataset. *(In progress — paper drafted for publication.)*

| Attribute | Detail |
|:----------|:-------|
| **Stack** | Python, Scikit-learn, NumPy, Pandas |
| **Scale** | ABIDE-I dataset (988 participants), 23 classifiers, 6 PCA configs |
| **Performance** | 79.8% accuracy (AUC 0.832) — beats 5 prior baselines |
| **Security** | Leakage-free, stratified 10-fold cross-validation |
| **Impact** | Interpretable region-level biomarkers, statistically validated |
| **Repository** | *In progress — coming soon* |

Built a benchmark across 23 classifiers and 6 PCA configurations under stratified 10-fold cross-validation. Identified interpretable region-level biomarkers via ensemble feature importance and FDR-corrected significance testing, with results validated using bootstrap CIs and Wilcoxon signed-rank tests.

</details>

---

## <img src="https://media.giphy.com/media/W5eoZHPpUp8pKdJhBb/giphy.gif" width="28"> Experience

**Computer Vision / Robotics Intern** · *Wraith-Int Tech Solutions Pvt Ltd*
`06/2026 – 08/2026` · *Hyderabad (On-site)*

Contributed to the software stack of a real-time multi-sensor drone detection and tracking platform for a defense application.

- Developed a dual-pipeline detection system: YOLOv8 (thermal) + RF-DETR (RGB) with CSRT-based tracking
- Led data collection and annotation feeding the detection models; engineered ROS2 simulations
- Built **AutoAnnotate**, an automated dataset annotation pipeline (Python, OpenCV)

`YOLOv8` `RF-DETR` `ROS2` `OpenCV` `Python` `Sensor Fusion`

<br/>

**Teaching Assistant** · *PES University*
`08/2025 – 05/2026` · *Bengaluru*

Supported Python Programming and MPCA courses for ~260 students.

- Ran labs and vivas, developed course content and slides, graded assessments
- Provided academic support across two semester-long courses

`Python` `Teaching` `Curriculum Design`

<br/>

**Research Intern** · *CCBD Lab, PES University*
`06/2025 – 08/2025` · *Bengaluru*

Remote sensing research on land use transformation.

- Performed supervised LULC classification on Landsat 8–9 imagery across five Karnataka districts using a Maximum Likelihood Classifier — 88.5% overall accuracy (κ = 0.81)
- Co-authored a paper accepted at ISDIA 2026, Dubai

`Remote Sensing` `Google Earth Engine` `Classification` `Research`

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Achievements

<div align="center">

| Recognition | Details |
|:------------|:--------|
| 🏆 **Prof. CNR Rao Scholarship** | Awarded **6×** for academic excellence, PES University |
| 📄 **Publication — ISDIA 2026** | Paper accepted at 10th Intl. Conference on Information System Design and Intelligent Applications, Dubai |
| ♟️ **Club Head — Chess Club** | PES University |
| 🧩 **Logistics Head — Quotient Quiz Club** | PES University |

</div>

---

## <img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="28"> Publications

**Monitoring Regional Land Use Transformation Around the Bengaluru–Mysuru Expressway Using Remote Sensing and Buffer-Based Analysis**
*ISDIA 2026 — 10th Intl. Conference on Information System Design and Intelligent Applications, Dubai, UAE*
Authors: Aneesh Bharadwaj K S, **Samyak Sankhla**, Shama Hegde, Prafullata Auradkar · **Status: Accepted**

---

## <img src="https://media.giphy.com/media/dWesBcTqRZ4wJexrEZ/giphy.gif" width="28"> Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/KB4EU0EcKB/"><img src="https://img.shields.io/badge/LeetCode-1a0033?style=for-the-badge&logo=leetcode&logoColor=8A2BE2" /></a>
<a href="https://www.hackerrank.com/profile/PES1UG23CS511"><img src="https://img.shields.io/badge/HackerRank-6A0DAD?style=for-the-badge&logo=hackerrank&logoColor=white" /></a>

</div>

---

## <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="28"> GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Samyak-sankhla&show_icons=true&theme=react&title_color=8a2be2&icon_color=8a2be2&text_color=ffffff&bg_color=0d1117&hide_border=true&count_private=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Samyak-sankhla&layout=compact&theme=react&title_color=8a2be2&text_color=ffffff&bg_color=0d1117&hide_border=true" />

<br/>

<img src="https://streak-stats.demolab.com?user=Samyak-sankhla&theme=react&hide_border=true&background=0D1117&stroke=8a2be2&ring=8a2be2&fire=8a2be2&currStreakLabel=8a2be2" />

</div>

---

## <img src="https://media.giphy.com/media/vX9WcCiWwUF7needn7/giphy.gif" width="28"> GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Samyak-sankhla&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=7" />

</div>

---

## <img src="https://media.giphy.com/media/iPvVmZBQKKw3FYFPKe/giphy.gif" width="28"> Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Samyak-sankhla&theme=react-dark&bg_color=0d1117&color=8a2be2&line=8a2be2&point=ffffff&hide_border=true" width="100%" />

</div>

---

## <img src="https://media.giphy.com/media/QQXWSTQFtT8V2/giphy.gif" width="28"> Current Focus

```yaml
learning:
  - Advanced deep learning for real-time perception
  - Distributed systems & scalable ML infrastructure

building:
  - Edge-ML systems for constrained hardware
  - Autonomous robotics pipelines (ROS2)

exploring:
  - Product engineering & full-stack development
  - Neural network optimization for embedded inference

open_to:
  - Software Engineering roles
  - AI / ML & Robotics Engineering
  - Research collaborations & open source
```

---

## <img src="https://media.giphy.com/media/LMt9638dO8dftAjtco/giphy.gif" width="28"> Let's Connect

<div align="center">

<a href="mailto:samyaksankhla3@gmail.com"><img src="https://img.shields.io/badge/Gmail-6A0DAD?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/samyak-sankhla/"><img src="https://img.shields.io/badge/LinkedIn-4B0082?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Samyak-sankhla"><img src="https://img.shields.io/badge/GitHub-1a0033?style=for-the-badge&logo=github&logoColor=8A2BE2" /></a>

</div>

<br/>

<div align="center">

> *"Build systems that work in the real world — from the model to the metal."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8a2be2,50:4b0082,100:1a0033&height=120&section=footer" />

</div>
