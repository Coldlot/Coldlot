# Andrei Sergeev

**Application Security Engineer**

[andrei.sergeev.job@gmail.com](mailto:andrei.sergeev.job@gmail.com) | [LinkedIn](https://linkedin.com/in/andrei-sergeev-sec) | [GitHub](https://github.com/Coldlot) | +995 591 759 674 | UTC+4

---

## Professional Summary

Application Security Engineer with 6+ years of mobile development experience and 1+ year focused on product security. Worked in a high-risk fintech environment, responsible for authentication, authorization, and cryptography for a mobile banking app serving millions of users. I understand the full development lifecycle — from requirements and architecture to release and post-release support. I can work autonomously, take ownership of features, and drive them end-to-end. Worked with Agile, Scrum, and Kanban. Comfortable talking to stakeholders, gathering requirements, and shaping the backlog.

Released multiple apps to the App Store, including a banking app serving millions of users. Built a fully automated iOS security pipeline using Semgrep, CodeQL, GitLeaks, and MobSF — blocking vulnerabilities and secrets before merge. Worked in teams of any size — from solo projects to 3-person startups to large distributed teams in banking. I compete in CTFs, build open-source security tooling, and stay active in the security community. Passionate about IT, always learning, never standing still. Looking to grow in AppSec / Product Security, build secure systems from the ground up, and share experience with the team.

---

## Core Competencies

**Mobile Security & Reverse Engineering**

Reverse Engineering (Frida, Ghidra, Hopper, JADX), Runtime Protection & Bypass, Jailbreak & Root Detection, Static & Dynamic Analysis, SSL Pinning Bypass, Cryptographic APIs (Keychain, Keystore), Secure Data Storage, Secure Authentication & Authorization, OWASP Mobile Top 10 / MASVS

**Application Security & DevSecOps**

SSDLC, Threat Modeling (STRIDE, DREAD), SAST/DAST Integration, CI/CD Pipeline Security (fastlane, Jenkins, Tuist), SCA, Secure Code Review, Vulnerability Management, Supply Chain Security, SBOM

**Mobile Development**

iOS (Swift, Objective-C), Android (Java, Kotlin), Cross-Platform (Flutter, Dart), Architectural Patterns (VIPER, TCA, MVVM, MVP), XCTest, Networking & Persistence

---

## Professional Experience

### iOS Developer (Security Champion) | Raiffeisenbank
*Aug 2025 – Apr 2026*

- Hardened authentication and authorization for a mobile banking app serving 1M+ users, reducing re-authentication support tickets by 7.4%.
- Co-designed a next-generation auth system based on OAuth 2.0 / PKCE, biometric login, and MFA — improving login speed by 5.8%.
- Integrated a trusted device framework enabling secure session persistence across app reinstalls, cutting related support tickets by 4.6%.
- Implemented cryptographic key management using Keychain and Secure Enclave, ensuring compliance with financial industry standards.
- Led security-focused code reviews and SAST/DAST/SCA triage for authentication flows, identifying and remediating 6+ vulnerabilities before production release.
- Applied STRIDE threat modeling and SCA to new authentication features (fast login, trusted cards), identifying 4+ architectural flaws at the design stage.

### iOS Developer / Security Engineer | WE53
*Aug 2022 – Mar 2025*

- Led a supply chain security initiative after a near-miss incident with a compromised third-party dependency — establishing a policy of forking and auditing all external libraries before integration.
- Integrated Apple Pay and Keychain-based secure storage for user payment data, ensuring compliance with PCI DSS requirements for in-app transactions.
- Served as feature lead for a customer-facing mobile application — owning the full cycle from spec to App Store release, including features handling personal data and financial transactions.
- Reduced app cold-start time from 10s to 4s and improved crash-free rate by 71.3% by profiling, refactoring critical legacy modules, and rebuilding the test suite from 11.5% to 56.7% coverage.
- Integrated SAST, DAST, and SCA into the security review workflow for authentication flows, catching vulnerabilities and vulnerable dependencies before production.

### iOS Developer | UmbrellaIT
*Oct 2020 – Aug 2022*

- Redesigned the local persistence layer using Realm — introduced thread-safe database access, data migration strategies, and encrypted cache storage, reducing database-related crashes from 325/day to 2–3/month and raising crash-free rate from 83.2% to 98.1%.
- Strengthened the network layer for a large-scale e-commerce app, implementing SSL pinning and secure OAuth token management to protect against man-in-the-middle attacks.
- Built a secure real-time communication channel between customers and consultants for a cosmetics brand using WebSockets (Starscream), enabling an interactive remote shopping experience with encrypted messaging.
- Developed and maintained internal SDKs, including a voice assistant and chat framework — ensuring secure data transmission for user voice and text inputs.
- Contributed to a banking loyalty program module (business lounge access), handling authentication flows without exposing sensitive user credentials.

### Mobile Application Developer | Early Career
*Jun 2019 – Oct 2020*

- Built an MVP for a telemedicine platform from the ground up — delivering two separate apps (patient and doctor) in 7 months, 2 months ahead of schedule, by developing a flexible, reusable design system and core UI components.
- Implemented secure payment flows including Apple Pay, Google Pay, and direct card input — handling sensitive financial data with encryption and tokenization.
- Ensured secure real-time data exchange between patient and doctor apps — including chat, video calls, medical records, and document sharing — with role-based access control protecting sensitive health data.
- Developed multiple applications across logistics, retail, and entertainment — integrating Apple Pay and Keychain-based secure storage for a major Moscow concert hall app, achieving 99.1% crash-free rate and increasing purchase conversion by 27.4%.

---

## Projects

### [ThreatModelDemo Pipes](https://github.com/Coldlot/threatmodeldemo-pipes) | DevSecOps Pipeline for iOS

- Built a fully automated CI/CD security pipeline for iOS applications using GitHub Actions — integrating SAST (Semgrep, CodeQL), DAST (MobSF), secret scanning (GitLeaks, GitGuardian), and dependency monitoring (Dependabot).
- Developed a deliberately vulnerable iOS app (Swift) featuring jailbreak detection, SSL pinning, Keychain token storage, and hardcoded secrets — serving as a test bench for security tooling and pipeline validation.
- Configured branch protection rules requiring all security checks to pass before merge — preventing vulnerable code from reaching main or dev branches, even for administrators.
- Integrated MobSF for IPA binary analysis, detecting insecure APIs, hardcoded URLs, and tracking libraries in compiled artifacts.

---

## Education

**Bachelor of Science in Software Engineering**
Peter the Great St. Petersburg Polytechnic University | 2017 – 2021

---

## Certificates

- **MobileHackingLab:** iOS Application Security Fundamentals, Android Application Security Fundamentals, Mobile Forensics Fundamentals
- **Cisco:** CCNA Cybersecurity Operations
