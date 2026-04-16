# Netflix System Design & Architectural Analysis 📺

A comprehensive logical blueprint of the Netflix streaming ecosystem, analyzing end-to-end workflows and system interactions through structured and object-oriented design.

## High-Level Architecture
The system follows a multi-tier architecture to ensure high availability, security, and scalability for millions of concurrent users.

![Architecture Diagram](assets/architecture%20diagram.png)

## System Modeling (Assets Inventory)
All architectural assets are organized in the `assets/` folder. Each diagram serves a specific purpose in the system's logical design:

* **Context Diagram:** Defines the system boundaries and primary interactions with external entities like Users and Payment Gateways.
* **DFD (Level 1 & 2):** Illustrates the internal decomposition of processes, showing how data flows between User Management, Content Streaming, and Payment modules.
* **UML Class Diagram:** Maps the static structure of the system, including `UserAccount`, `Subscription`, `Content`, and `WatchHistory` classes.
* **Sequence Diagram:** Documents the dynamic step-by-step interaction between the User, Auth Server, and Content Server during a streaming session.
* **Activity Diagram:** Visualizes the step-by-step operational workflow, from login to content delivery via CDN.
* **State Machine & State Flow:** Tracks the various states of the streaming player (Idle, Buffering, Playing, Paused, Stopped).
* **Use Case Diagram:** Outlines the core functional requirements from the perspective of the User and the System.

## Requirements & Quality Assurance
* **Functional Requirements:** User registration, multi-profile management, and auto-quality streaming.
* **Non-Functional Requirements:** Focus on 99.9% uptime, data encryption, and cross-platform compatibility.
* **Testing Framework:** Includes detailed Test Cases for core features and White Box Testing logic for internal authentication and search sanitization.

## Project Team
* Maryam Khalid
* Sabahat
* Rohan Munir

---
*Developed as part of the Software Engineering curriculum at Bahria University.*
