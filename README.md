# 🧠 Takweenak (تكوينك) — Telehealth & Mental Health Platform

**Takweenak** is a mental health consultation application built using **Kotlin Multiplatform (KMP)**. It connects patients with licensed therapists and mental health doctors, allowing seamless booking, appointment management, and remote therapy sessions.

The app shares core domain logic, data models, and network state management across platforms using **Kotlin Multiplatform**, while delivering fully native UI experiences using **Jetpack Compose** on Android and **SwiftUI** on iOS.

---

## 📱 App Showcase & User Journey

| Splash & Onboarding | Doctor Discovery | Doctor Profile & Info | Date & Time Booking | Available Services |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/a973a3df-aa9e-4911-9747-adee0969e665" width="190"> | <img src="https://github.com/user-attachments/assets/736bb4d6-3a82-4401-b146-6c20c6166415" width="190"> | <img src="https://github.com/user-attachments/assets/186e520c-8df6-40c9-9810-d6e7e1257619" width="190"> | <img src="https://github.com/user-attachments/assets/506bf4b5-7e16-4c67-abd2-c779b59e1ba9" width="190"> | <img src="https://github.com/user-attachments/assets/f73ab47a-b6b3-4d80-bacd-0a88394609f5" width="190"> |

---

## 💡 Key Features

- **Doctor & Therapist Discovery:** Browse specialized mental health practitioners by category, rating, and availability.
- **Detailed Profiles & Reviews:** View doctor qualifications, patient feedback, and session pricing.
- **Interactive Session Scheduling:** Integrated calendar picker with real-time time-slot selection for appointments.
- **Multi-Service Booking:** Choose between individual therapy sessions, psychological evaluations, and continuous follow-ups.
- **Dual-Role Capabilities (Doctor/Patient):** Specialized workflows allowing patients to join virtual sessions and practitioners to manage their schedules.

---

## 🛠 Tech Stack & KMP Architecture

- **Shared Architecture:** Kotlin Multiplatform (KMP)
- **Shared Layer (`/shared`):**
  - Business Logic & Domain Use Cases
  - Data Repositories & DTOs
  - Ktor Client for HTTP Networking
  - kotlinx.coroutines & Flow for reactive state management
- **Native UI Presentation Layer:**
  - **Android:** Native Jetpack Compose with Material 3 Design
  - **iOS:** Native SwiftUI Integration
- **Architecture Pattern:** Clean Architecture + MVI / MVVM Pattern
