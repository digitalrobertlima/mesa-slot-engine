# 🎰 M.E.S.A. Slot Engine

> **Mathematical Entertainment System Architecture**
>
> An open-source economic simulation engine built for academic research, interactive environments and transparent game mechanics.

---

## Overview

The **M.E.S.A. Slot Engine** is an open-source simulation platform designed to study the interaction between economic systems, user interfaces, environmental design and mathematical transparency.

Unlike traditional slot machines, the M.E.S.A. Engine is built around a simple principle:

> **Every monetary value displayed by the system must correspond to a real internal state.**

No fictitious jackpots.

No hidden balances.

No unexplained calculations.

Every financial transaction is deterministic, auditable and reproducible.

---

## Project Purpose

This project was created as part of an academic research initiative focused on:

* Environment Design
* Human-System Interaction
* Economic Simulation
* Interactive Installations
* Mathematical Transparency
* Software Architecture
* Open Source Engineering

Rather than reproducing a commercial gambling platform, the project investigates how transparent economic models and interactive systems can be designed, documented and analyzed.

---

## Core Principles

The architecture follows six fundamental principles.

### 1. Mathematical Transparency

Every value presented to the player is backed by an internal calculation.

There are no fake jackpots.

There are no hidden balances.

---

### 2. Auditability

Every financial movement generates an auditable record.

Nothing happens without being logged.

---

### 3. Separation of Responsibilities

Each module has exactly one responsibility.

Economy does not render the interface.

The interface does not calculate prizes.

The RNG does not modify balances.

---

### 4. Modular Architecture

Every subsystem can evolve independently.

---

### 5. Offline First

The engine must operate locally without requiring an internet connection.

---

### 6. Research First

All architectural decisions prioritize clarity, documentation and reproducibility over complexity.

---

# Features

* Transparent Economy Engine
* Prize Pool Management
* Profit Pool Management
* Real & Bonus Wallets
* Financial Audit System
* Modular Event Engine
* PlatformIO + ESP32 Support
* Vanilla HTML/CSS/JavaScript Front-End
* Responsive Interface
* Procedural Audio (Web Audio API)
* Research Dashboard
* Open Source (MIT)

---

# Architecture

The engine is organized into independent layers.

```text
                USER INTERFACE
         HTML • CSS • JavaScript

                    │

              EVENT ENGINE

                    │

                 RNG ENGINE

                    │

             ECONOMY ENGINE

                    │

             MEMORY ENGINE

                    │

              AUDIT SYSTEM
```

Each layer has a single responsibility and communicates through well-defined interfaces.

---

# Technology Stack

## Firmware

* ESP32
* Arduino Framework
* PlatformIO

## Front-End

* HTML5
* CSS3
* JavaScript (ES6)

## Tools

* Visual Studio Code
* Git
* GitHub

---

# Project Structure

```text
mesa-slot-engine/

├── assets/
├── data/
├── docs/
├── include/
├── lib/
├── src/
├── test/
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── platformio.ini
```

---

# Documentation

Project documentation is located inside the **docs/** directory.

Main documents include:

* VISION.md
* PROJECT_CONSTITUTION.md
* ARCHITECTURE.md
* MATHEMATICS.md
* CODE_GUIDE.md
* ROADMAP.md

Documentation is considered part of the source code.

Any architectural change must update the corresponding documentation.

---

# Development Workflow

Every feature follows the same engineering cycle.

```text
Idea

↓

RFC

↓

Architecture

↓

Implementation

↓

Testing

↓

Documentation

↓

Release
```

No feature skips this process.

---

# Versioning

The project follows Semantic Versioning.

```
MAJOR.MINOR.PATCH
```

Example:

```
11.0.0
```

---

# License

This project is licensed under the MIT License.

See the LICENSE file for details.

---

# Contributing

Contributions are welcome.

Before implementing any feature, please read:

* PROJECT_CONSTITUTION.md
* CODE_GUIDE.md
* CONTRIBUTING.md

Every contribution should preserve the project's architectural principles.

---

# Project Status

Current Version

```
11.0.0
```

Current Stage

```
Foundation
```

Development Status

```
Active
```

---

# Author

Robert Lima

Designer & Researcher

---

# Vision

The M.E.S.A. Slot Engine aims to become an open reference for transparent economic simulation, interactive environments and modular software architecture.

Its purpose is not simply to simulate a slot machine, but to demonstrate how complex interactive systems can be designed with mathematical clarity, engineering discipline and complete auditability.

---

**Architecture First. Code Second.**
