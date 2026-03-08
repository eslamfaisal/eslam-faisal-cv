# Eslam Faisal Ali Emara

**Senior Mobile Engineer**

---

**Location:** Cairo, Egypt
**Phone:** +20 106 745 7665
**Email:** eslam.faisal.ef@gmail.com
**LinkedIn:** [linkedin.com/in/eslam-faisal-b01321312](https://linkedin.com/in/eslam-faisal-b01321312)
**GitHub:** [github.com/eslamfaisal](https://github.com/eslamfaisal)
**StackOverflow:** [stackoverflow.com/users/9313214](https://stackoverflow.com/users/9313214/eslam-faisal)
**YouTube:** [youtube.com/@EslamFaisal-BlueThunder](https://www.youtube.com/@EslamFaisal-BlueThunder)

---

## Professional Summary

Senior Mobile Engineer with **8+ years** of hands-on experience building production-grade mobile applications across **Android** (Java, Kotlin, Jetpack Compose), **Flutter** (Dart, BLoC), and backend systems (Spring Boot, Firebase). Currently leading mobile development at **AlgoDriven**, where I architect and maintain **EvalExpert** — a large-scale vehicle appraisal platform serving automotive dealers across **Australia and GCC markets** (version 17+, 7800+ builds). Proven track record in migrating legacy codebases, designing scalable Clean Architecture systems, integrating AI/ML features, real-time data pipelines, and leading cross-functional teams. Published open-source contributor on pub.dev and Google Play Store.

---

## Core Competencies

| Area | Technologies |
|------|-------------|
| **Mobile Development** | Flutter (Dart, BLoC, Provider) · Android (Java, Kotlin, Jetpack Compose) · iOS Deployment |
| **Architecture & Patterns** | Clean Architecture · MVVM · MVI · BLoC · Feature-First Modularization · SOLID · DRY |
| **State Management** | flutter_bloc · HydratedBloc · bloc_concurrency · rxdart · Kotlin Coroutines & Flow |
| **Backend & Cloud** | Firebase (Firestore, RTDB, Cloud Functions, Auth, Crashlytics, Messaging) · Spring Boot · REST APIs |
| **Networking & Data** | Dio · Retrofit · dartz (Functional Error Handling) · JSON Serialization · Isolate-Based Parsing |
| **AI & ML** | Google ML Kit (Barcode Scanning, Text Recognition) · Damage AI · Pricing AI |
| **Real-Time Systems** | Firestore Streams · Firebase Realtime Database · SendBird Chat SDK · WebSockets · Pusher |
| **DevOps & Monitoring** | CI/CD · Datadog · Firebase Crashlytics · OneSignal · Pretty Dio Logger |
| **Third-Party SDKs** | Stripe Payments · SendBird Chat · Intercom · Algolia Search · Huawei HMS · ArcGIS Maps |
| **Dependency Injection** | get_it · injectable · Dagger/Hilt (Android) |
| **Testing** | Unit Testing · Integration Testing · UI Testing · bloc_test · mocktail · JUnit4 · Mockito · Espresso |
| **Tools** | Git · Cursor AI · Android Studio · Xcode · VS Code · Figma |

---

## Professional Experience

### Senior Mobile Engineer

**AlgoDriven** — Cairo, Egypt
*January 2022 – Present*

- Architect and maintain **EvalExpert**, the world's most advanced vehicle appraisal platform used by automotive dealers across Australia and GCC, delivering **7800+ production builds** across Flutter and native Android.
- Designed and implemented **feature-first Clean Architecture** with **20+ feature modules** (evaluations, marketplace, auctions, price check, stock analysis, chat, notifications, VIN scanning) using BLoC pattern and injectable DI.
- Built a centralized **ApiManager** abstraction on top of Dio with typed Failure classes, FailureHandler, and FirebaseFailureHandler — enforcing `Either<Failure, SuccessType>` return types across all **18+ repository implementations**.
- Engineered **real-time auction bidding system** using Firebase Realtime Database streams with `emit.forEach` in BLoC, supporting live price updates and concurrent bid handling via `sequential()` transformers.
- Integrated **Google ML Kit** for VIN barcode scanning and license plate text recognition with `droppable()` event transformer to skip stale camera frames, achieving smooth **60fps scanning** experience.
- Implemented **AI-powered damage detection** overlay system — processing upload responses for damage analysis results and rendering crossfade overlays for 6 vehicle body types.
- Built conditional **Pricing AI module** with dynamic BLoC creation based on dealer preferences and subscription tier.
- Offloaded heavy Firestore document parsing to **Dart isolates** using `compute()`, reducing UI frame drops from **~200ms to under 16ms** on mid-range devices.
- Designed **parallel image download system** (max 2 concurrent) for evaluation details, cutting page load time by **40%**.
- Implemented **optimistic UI updates** for pricing workflows with pending state tracking and server-response merging, eliminating perceived latency on slow networks.
- Built custom `debounceRestartable()` bloc_concurrency transformer combining debounce with restart logic for real-time price input fields.
- Integrated **SendBird Chat SDK** with connection lifecycle management, temporary connections, FCM push token synchronization, and theme-aware dark/light mode support.
- Implemented **HydratedBloc** for offline state persistence (auth session, dealer preferences, app settings) with automatic serialization/deserialization.
- Built comprehensive **design system** with theme-aware AppColors, AppSpacing, AppRadius, AppShadows, and **68+ reusable components**.
- Delivered **multi-language support** (English, Arabic, French) with full RTL layout support.
- Migrated the native Android version of EvalExpert from **Java to Kotlin** with Jetpack Compose and MVVM architecture.
- Integrated **Datadog** for production monitoring, achieving **99.2%+ crash-free rate** via Firebase Crashlytics.

> **Tech Stack:** Flutter, Dart, Kotlin, Java, Jetpack Compose, BLoC, Firebase, Firestore, RTDB, Cloud Functions, Dio, SendBird, Google ML Kit, Datadog, OneSignal, Intercom, Algolia, Stripe, go_router, get_it, injectable, dartz, rxdart, hydrated_bloc, bloc_concurrency

---

### Mobile App Developer

**EgyptianSaudi** — Giza, Egypt
*November 2020 – January 2022*

- Developed and maintained multiple mobile applications serving **POS systems** and accounting workflows, integrating with **Odoo ERP** backend systems.
- Built E-Commerce applications with complex order management, inventory tracking, and real-time synchronization with ERP data.
- Implemented Flutter-based cross-platform solutions reducing development time by **50%** compared to native dual-platform approach.
- Integrated REST APIs with Odoo backend services, handling complex data transformation and offline-first synchronization patterns.

> **Tech Stack:** Java, Kotlin, Flutter, Dart, Python, Odoo ERP, REST APIs, Firebase

---

### Android Developer

**Urgent Solutions** — Cairo, Egypt
*March 2020 – November 2020*

- Maintained and enhanced a production E-Commerce application serving thousands of daily active users.
- Migrated legacy Java codebase to Kotlin, improving code readability and reducing null-pointer crashes by **35%**.
- Implemented modern Android architecture components (ViewModel, LiveData, Room) for improved data persistence and lifecycle management.

> **Tech Stack:** Java, Kotlin, Android Jetpack, MVVM, REST APIs

---

### Android Developer

**Silicon Unions** — Maadi, Egypt
*September 2018 – March 2020*

- Developed educational mobile applications from scratch, working across the full development lifecycle from requirements gathering to Play Store deployment.
- Built interactive learning features with multimedia content delivery, quiz engines, and progress tracking.
- Collaborated with UI/UX designers to implement pixel-perfect interfaces following Material Design guidelines.

> **Tech Stack:** Java, Android SDK, SQLite, Firebase, REST APIs

---

### Android Developer

**YelloCo.com** — Nasr City, Egypt
*January 2018*

- Contributed to the YelloCo e-commerce platform, implementing product catalog features and search functionality.

> **Tech Stack:** Java, Android SDK, REST APIs

---

### Freelance Software Engineer

**Remote**
*September 2016 – January 2018*

- Delivered **5+ mobile applications** for clients across different domains including e-commerce, education, and social networking.
- Managed full project lifecycle independently — requirements, design, development, testing, and deployment.

> **Tech Stack:** Java, Android SDK, Firebase, REST APIs

---

## Notable Projects

### EvalExpert — Vehicle Appraisal Platform

**AlgoDriven** | Flutter & Android Native | *2022 – Present*

World's most advanced vehicle appraisal system for automotive dealers. Features include real-time auctions, AI damage detection, VIN scanning with ML Kit, SendBird chat, marketplace with private tenders, and comprehensive price check analytics with Syncfusion charts. **20+ feature modules, 68+ reusable components, 3-language support.**

---

### SmartCaf — Government Services Platform

**Flutter** | *2021*

Italian market Flutter application enabling citizens to order government services digitally. Integrated **Stripe payment processing**, **Pusher** for real-time updates, and RESTful API consumption with secure document handling.

---

### Tar2 (طارئ) — Emergency Social Application

**Android Native (Huawei)** | *2021*

Social application for emergency situations, built exclusively for Huawei devices using **AGCConnect and HMS** services. Utilized Firestore for real-time database operations and Huawei Cloud DB for device-specific features.

---

### Cell Info Flutter Package

**Open Source** | [pub.dev/packages/flutter_cell_info](https://pub.dev/packages/flutter_cell_info)

Published open-source Flutter package for retrieving SIM cell information. Bridges native Android platform channels with Flutter, demonstrating platform-specific integration expertise.

---

### Muslim Way — Islamic Lifestyle App

**Flutter** | *2020*

Flutter application featuring prayer time notifications, Quran reading, and Islamic content. Integrated RESTful APIs, local SQLite database for offline access, Firebase Firestore, FCM push notifications, and Crashlytics.

---

## Education

### Bachelor's Degree in Computer Science

**6th October University** — Giza, Egypt

---

## Certifications

- **Android Developer Nanodegree** — Google & Udacity
- **Java Developer Nanodegree** — Udacity
- **Flutter & Dart Complete Developer Course** — Udemy
- **Web Developer Certification**
- **Android Developer Nanodegree by Google** — Udacity

---

## Languages

| Language | Proficiency |
|----------|-------------|
| **Arabic** | Native |
| **English** | Professional Working Proficiency |
