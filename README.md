# 🔐 ParryKey

<div align="center">

![ParryKey Banner](https://password-generator.parrysecurity.online/banner.png)

### Enterprise-Grade Password Generator by ParrySecurity

**Generate ultra-secure passwords instantly with a beautiful modern UI, real-time security analysis, QR export, and zero server logging.**

<br>

![HTML5](https://img.shields.io/badge/HTML5-Frontend-orange?style=for-the-badge\&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Modern_UI-blue?style=for-the-badge\&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge\&logo=javascript)
![Security](https://img.shields.io/badge/Security-Client_Side-green?style=for-the-badge\&logo=shield)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)
## 🌐 Live Demo

🚀 Try ParryKey Live Here:

[![Live Website](https://img.shields.io/badge/Launch-ParryKey-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://password-generator.parrysecurity.online/)

🔗 https://password-generator.parrysecurity.online/

<br>

🚀 **Fast • Secure • Beautiful • Private**

</div>

---
<img width="1672" height="941" alt="ChatGPT Image May 20, 2026, 03_03_38 PM" src="https://github.com/user-attachments/assets/12906f80-ac69-4e75-a0fa-3cf0650284bc" />

# 📖 Table of Contents

* [Overview](#-overview)
* [Live Features](#-live-features)
* [Preview](#-preview)
* [Core Functionalities](#-core-functionalities)
* [Technology Stack](#-technology-stack)
* [Installation](#-installation)
* [How It Works](#-how-it-works)
* [Password Security Analysis](#-password-security-analysis)
* [QR Export System](#-qr-export-system)
* [Password History](#-password-history)
* [Responsive Design](#-responsive-design)
* [Project Structure](#-project-structure)
* [Security Advantages](#-security-advantages)
* [Customization](#-customization)
* [Browser Support](#-browser-support)
* [Future Roadmap](#-future-roadmap)
* [Contributing](#-contributing)
* [License](#-license)
* [About ParrySecurity](#-about-parrysecurity)

---

# 🎯 Overview

**ParryKey** is a modern, enterprise-style password generator developed by **ParrySecurity**.

Built with a strong focus on **security**, **privacy**, and **user experience**, ParryKey generates highly secure passwords directly inside the browser using cryptographically secure random generation.

No data is sent to servers.
No tracking.
No logging.
100% client-side.

---

# ✨ Live Features

## 🔐 Advanced Password Generation

✅ Cryptographically secure password generation
✅ Custom password lengths (4–128 characters)
✅ Uppercase letters support
✅ Lowercase letters support
✅ Numbers support
✅ Special symbols support
✅ Exclude ambiguous characters
✅ One-click regeneration
✅ Instant copy to clipboard

---

## 📊 Real-Time Security Analysis

ParryKey automatically analyzes every generated password and provides:

* Entropy score
* Crack-time estimation
* Security rating
* Character pool size
* Combination calculation
* Live strength meter

### Security Ratings

| Rating    | Meaning                |
| --------- | ---------------------- |
| Weak      | Easily guessable       |
| Fair      | Moderate protection    |
| Good      | Strong for regular use |
| Strong    | Enterprise-grade       |
| Excellent | Maximum security       |

---

## 🎨 Modern Enterprise UI

### Beautiful Design Includes:

* Light professional interface
* Glassmorphism effects
* Soft shadows
* Enterprise dashboard styling
* Responsive layouts
* Animated interactions
* Modern typography using Geist font
* Professional navbar and cards

---

## 📱 QR Code Export

Generate a QR-style export for passwords:

✅ QR generation
✅ PNG download
✅ Auto-expiry timer
✅ Secure temporary preview

---

## 🕘 Password History

ParryKey stores recent generated passwords locally:

* LocalStorage support
* Recently generated passwords
* One-click recopy
* Time indicators
* Clear history option

---

# 🖥️ Preview

## Main Dashboard Includes

* Password display area
* Live strength analysis
* Configuration controls
* Security metrics
* QR export panel
* Password history manager

---

# ⚡ Core Functionalities

## 🔄 Secure Password Engine

Uses:

```javascript
crypto.getRandomValues()
```

This ensures:

* Cryptographically secure randomness
* Unpredictable password generation
* Enterprise-grade security standards

---

## 📈 Entropy Calculation

ParryKey calculates password entropy using:

```text
Entropy = Length × log₂(Character Pool Size)
```

This helps estimate password strength scientifically.

---

## ⏱️ Crack Time Estimation

Estimates attack resistance against:

* Brute-force attacks
* Dictionary attacks
* GPU cracking systems

Includes realistic cracking speeds.

---

## 🎛️ Fully Customizable

Users can control:

| Setting                    | Supported |
| -------------------------- | --------- |
| Password Length            | ✅         |
| Uppercase Letters          | ✅         |
| Lowercase Letters          | ✅         |
| Numbers                    | ✅         |
| Symbols                    | ✅         |
| Exclude Similar Characters | ✅         |

---

# 🛠️ Technology Stack

| Technology         | Purpose           |
| ------------------ | ----------------- |
| HTML5              | Structure         |
| CSS3               | Styling           |
| Vanilla JavaScript | Logic             |
| Web Crypto API     | Secure randomness |
| LocalStorage       | History           |
| Canvas API         | QR rendering      |
| Geist Font         | Typography        |

---

# 📥 Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/parrykey.git
```

---

## 2️⃣ Open Project

```bash
cd parrykey
```

---

## 3️⃣ Run Locally

Simply open:

```bash
index.html
```

No backend required.

No dependencies required.

---

# ⚙️ How It Works

## Password Generation Flow

```text
User Settings
      ↓
Build Character Pool
      ↓
Generate Secure Random Values
      ↓
Create Password
      ↓
Analyze Security
      ↓
Display Results
```

---

# 📊 Password Security Analysis

## Metrics Included

### 🔹 Entropy

Measures randomness in bits.

### 🔹 Crack Time

Estimates how long attackers would need.

### 🔹 Combination Count

Shows total possible combinations.

### 🔹 Character Pool

Displays active character range.

### 🔹 Security Rating

Overall password quality assessment.

---

# 📦 QR Export System

The QR system allows secure temporary sharing.

## Features

* Dynamic QR rendering
* Auto-expiration
* PNG export
* Canvas-based rendering

---

# 🧠 Password History

Recent passwords are stored locally in the browser only.

## Privacy Features

✅ No cloud sync
✅ No external database
✅ No telemetry
✅ No tracking

---

# 📱 Responsive Design

ParryKey works perfectly on:

| Device  | Supported |
| ------- | --------- |
| Desktop | ✅         |
| Laptop  | ✅         |
| Tablet  | ✅         |
| Mobile  | ✅         |

---

# 📂 Project Structure

```bash
parrykey/
│
├── index.html
├── README.md
│
├── assets/
│   ├── screenshots/
│   ├── icons/
│   └── logos/
│
└── LICENSE
```

---

# 🛡️ Security Advantages

## Why ParryKey is Secure

### ✅ 100% Client-Side

Passwords never leave the browser.

### ✅ Zero Logging

No server communication.

### ✅ Secure Randomness

Uses browser cryptographic APIs.

### ✅ Offline Compatible

Works without internet.

### ✅ No Third-Party Analytics

Completely private.

---

# 🎨 Customization

Developers can easily customize:

* Colors
* Fonts
* Shadows
* Border radius
* Character sets
* Security rules
* Layouts
* Components

Using CSS variables.

---

# 🌐 Browser Support

| Browser | Supported |
| ------- | --------- |
| Chrome  | ✅         |
| Edge    | ✅         |
| Firefox | ✅         |
| Safari  | ✅         |
| Brave   | ✅         |

---

# 🚀 Future Roadmap

Planned features:

* Dark mode
* Real QR library integration
* Password breach checking
* Cloud sync
* Password vault
* Browser extension
* Multi-language support
* PWA support

---

# 🤝 Contributing

Contributions are welcome.

## Steps

```bash
1. Fork repository
2. Create new branch
3. Commit changes
4. Push updates
5. Open pull request
```

---

# 📄 License

Distributed under the MIT License.

---

# 🏢 About ParrySecurity

### ParrySecurity

Building modern cybersecurity tools focused on:

* Privacy
* Security
* Threat Intelligence
* Enterprise Protection
* Secure-by-design software

---

<div align="center">

# 🔐 ParryKey

### Secure Passwords. Zero Compromise.

Built with ❤️ by **ParrySecurity**

</div>
