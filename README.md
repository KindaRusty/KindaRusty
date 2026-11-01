<div align="center">

# Hello, I'm KindaRusty!

[![GitHub followers](https://img.shields.io/github/followers/KindaRusty?style=social)](https://github.com/KindaRusty)
[![Discord](https://img.shields.io/badge/Discord-kindarusty-7289DA?style=flat&logo=discord&logoColor=white)](https://discord.com/users/YOUR_NUMERIC_ID)

**Computer Science Student · AI Enthusiast · Problem Solver**

_Swinburne University of Technology — Da Nang Campus_

</div>

---

## About Me

Third-year Computer Science student with a passion for **Artificial Intelligence** and challenging programming problems. I thrive on building innovative solutions and exploring cutting-edge technologies.

- Currently focusing on **Computer Vision**, **Deep Learning** and **End-to-end ML systems**
- Leading a 4-person team building **SmartAttend**, a real-time face recognition attendance system with liveness and emotion detection
- Building a strong foundation in Computer Science fundamentals
- Always eager to tackle complex problems and learn new technologies
- Goal: Become proficient in AI development and contribute to impactful projects

---

## Tech Stack

**Programming Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=c-sharp&logoColor=white)

**AI / ML & Data Science**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006400?style=for-the-badge&logo=xgboost&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**Frameworks & Tools**

![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## Featured Projects

### SmartAttend — Facial Recognition with Emotion & Liveness

> **COS30082 · Applied Machine Learning — Team Project (Team Leader)** · _In progress_

A real-time, webcam-based attendance system that verifies identity, rejects spoofing attacks and detects emotion. All models are trained or fine-tuned by the team.

- **Pipeline:** camera → face detection → liveness → recognition → emotion, with early stop for spoofed faces (printed photos, screen replays)
- **My role:** led a 4-person team; designed the shared module interfaces and central config; built the per-frame pipeline, the PyQt5 GUI and the threaded webcam loop; set up the Git workflow, docs and test suite
- **Recognition:** ResNet-18 embeddings compared across Softmax, Triplet and ArcFace losses. Softmax baseline: **AUC 0.951 / EER 10.8%** on 8,805 verification pairs (4,000 identities, 380K training images)
- **Emotion:** Mini-Xception on FER-2013 (7 classes). **Test accuracy 59.9%, macro-F1 0.56**
- **Engineering:** interface-based design with dummy models, so each member's module plugs in independently; unit tests run without a camera

**Stack:** `Python` `PyTorch` `timm` `OpenCV` `MediaPipe` `PyQt5` `scikit-learn` `pytest`

🔗 [View repository](https://github.com/KindaRusty/Testing-Facial-Recognition-with-Emotion-and-Liveness)

---

### TBRGS — Traffic-Based Route Guidance System

> **COS30019 · Introduction to Artificial Intelligence — Assignment 2B**

A traffic prediction and intelligent route guidance system integrating machine learning with graph-based pathfinding.

- **ML Models:** LSTM, GRU (deep learning) and XGBoost trained on real SCATS sensor data from Boroondara, Melbourne (Oct 2006)
- **Routing:** Yen's K-Shortest Paths algorithm on a dynamic road network graph built from OpenStreetMap data
- **Pipeline:** End-to-end system: raw data ingestion → feature engineering → model training → traffic-aware routing → Flask web app with Folium map visualization
- **Testing:** 10+ automated test scenarios covering model accuracy, route validity, and integration

**Stack:** `Python` `TensorFlow/Keras` `XGBoost` `Flask` `Folium` `pandas` `scikit-learn`

---

### Music Event Management System

> **ASP.NET Core · Razor Pages Web Application**

A full-stack web application for managing music events with complete user authentication and event registration workflows.

- **Features:** Event CRUD, user registration & login (ASP.NET Identity), tiered pricing, email notifications, admin dashboard
- **Architecture:** ASP.NET Core Razor Pages with Entity Framework Core and SQL Server
- **Auth:** Role-based access control (Admin / User), secure authentication via Identity framework
- **Models:** `MusicEvent`, `EventRegistration`, `PricingTier`, `UserPreference`, `ApplicationUser`

**Stack:** `C#` `.NET` `ASP.NET Core` `Entity Framework Core` `SQL Server` `Razor Pages`

---

## Languages

| Language      | Proficiency                            |
| ------------- | -------------------------------------- |
| 🇻🇳 Vietnamese | Native                                 |
| 🇺🇸 English    | Proficient (6.5 IELTS or 120 Duolingo) |
| 🇯🇵 Japanese   | Learning (Currently N5 aiming for N4)  |

---

## Connect With Me

<div align="center">

[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/902697307101884416)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KindaRusty)

</div>
