# 🎭 Between Threads

**A real-time interactive system that turns hand movements into physical motion.**

Between Threads is an experimental platform that bridges **computer vision**, **real-time systems**, and **physical actuation** to create a new form of interaction — where your fingers become a control interface for the physical world.

![Between Threads Poster](/resources/photo.jpeg)

---

## ✨ What is it?

Between Threads transforms **hand gestures into live-controlled servo motors**, creating a digital-to-physical feedback loop.

Think of it as a **modern puppet system**, powered by:

- Real-time hand tracking
- Low-latency communication
- Physical motor control
- Live monitoring interface

---

## 🚀 Key Features

### 🎯 Real-Time Hand Tracking

- High-precision finger tracking
- Ultra-low latency processing
- Natural, intuitive control

### ⚙️ Physical Actuation

- Servo motors controlled in real time
- Smooth and responsive movement
- Modular hardware integration

### 🌐 Live Unity + Dashboard Interface

- Real-time visualization of the system
- Control and monitoring
- Interactive dashboard

### 🔌 Modular Architecture

- Fully decoupled services
- Scalable and maintainable system

---

## 📦 Repositories

The project is split into multiple repositories for clarity and scalability:

- [`Hand-Recognition`](https://github.com/Between-Threads-Project/Hand-Recognition) → Vision & gesture processing
- [`RaspberryPi-Software`](https://github.com/Between-Threads-Project/RaspberryPi-Software) → Motor control & dashboard backend
- [`Dashboard`](https://github.com/Between-Threads-Project/Dashboard) → Dashboard & user interaction
- [`Orchestrator`](https://github.com/Between-Threads-Project/Orchestrator) → Installer for the whole project
- [`Unity`](https://github.com/Between-Threads-Project/Unity) → Unity interface application
- [`Hardware`](https://github.com/Between-Threads-Project/Hardware) → Cable connection and printed parts files
- [`Live-Streaming`](https://github.com/Between-Threads-Project/Live-Streaming) → Live video streaming of the system

---

## 🧩 System Overview

The project is built around a **distributed architecture**, composed of multiple independent services:

- **Hand Tracking** → Captures and processes finger movements
- **Raspberry Pi Software** → Controls the physical motors & the dashboard back-end
- **Web Dashboard** → Provides an interface to lauch the project
- **Unity Interface** → Provides real-time visualization and control

Each module is designed to be:

- Replaceable
- Scalable
- Easy to extend

---

## ⚡ Why Between Threads?

This project explores the intersection of:

- **Human-computer interaction**
- **Embedded systems**
- **Real-time software architecture**

It demonstrates how software can **directly manipulate the physical world** in a seamless and responsive way.

---

## 🛠 Tech Stack

- **Computer Vision**: Hand tracking pipeline using [MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/guide?hl=fr)
- **Website Backend**: Python / FastAPI / WebSockets
- **Frontend**: React / Next.js
- **Hardware**: Raspberry Pi + Servo Motors
- **Communication**: UDP + WebSockets

---

## 🔭 Vision

Between Threads is more than a project — it's a **prototype for future interaction systems**, where:

- Interfaces become invisible
- Movements replace inputs
- Software directly controls reality

---

## 🤝 Contributors

Built as part of an engineering project at [**IFT (Institue for Futures Technologies)**](https://ift.devinci.fr) by [Jolann Narcisse](https://marmalade-timer-d9d.notion.site/Jolann-NARCISSE-Future-Engineer-in-Creative-Technologies-Portfolio-2b3e0ce5338a804096b2d609686c9e7e) & [Julien Fernandes](https://julien-fernandes.vercel.app).

---

## ⭐️

If you find this project interesting, feel free to explore the repos and follow its evolution.
