🍯 ParryKey
<div align="center">
🔐 Modern Enterprise Password Generator
Secure. Generate. Protect.
<img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /> <img src="https://img.shields.io/badge/HTML5-Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white" /> <img src="https://img.shields.io/badge/CSS3-Styled-1572B6?style=for-the-badge&logo=css3&logoColor=white" /> <img src="https://img.shields.io/badge/Platform-Web-lightgrey?style=for-the-badge" /> <img src="https://img.shields.io/badge/Status-Production_Ready-brightgreen?style=for-the-badge" /> <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

<br><br>

ParryKey is a modern, secure, client-side password generator built by ParrySecurity.
Designed with enterprise-grade UI/UX, real-time password analysis, QR export, history management, and strong cryptographic randomness.

</div>
<img width="1672" height="941" alt="ChatGPT Image May 20, 2026, 03_03_38 PM" src="https://github.com/user-attachments/assets/3181a371-c83e-4070-ae6b-9076d051717f" />

📑 Table of Contents
✨ Features
🛡️ Security Features
🖥️ Preview
🏗️ Architecture
🚀 Quick Start
📦 Installation
⚙️ Configuration
🎛️ Dashboard Components
🔐 Password Analysis Engine
📱 QR Export System
🕘 History System
📊 Feature Breakdown
📂 Project Structure
🧪 Testing
🌐 Browser Support
🚀 Deployment
🔧 Troubleshooting
🤝 Contributing
📄 License
💙 Acknowledgments
✨ Features
🔐 Secure Password Generation
Cryptographically secure password generation using crypto.getRandomValues()
Adjustable password length (4–128)
Real-time regeneration
One-click copy to clipboard
Hide/show password visibility
🎨 Modern Enterprise UI
Light-themed glassmorphism design
Professional cybersecurity branding
Fully responsive layout
Smooth animations & transitions
Enterprise dashboard appearance
⚡ Real-Time Security Analysis

ParryKey instantly analyzes generated passwords:

Feature	Description
Entropy Analysis	Measures password randomness
Crack Time Estimation	Calculates estimated brute-force time
Character Pool Analysis	Shows available charset size
Security Rating	Weak / Fair / Good / Strong / Excellent
Combination Count	Calculates total possible combinations
⚙️ Password Customization

Users can enable or disable:

✅ Uppercase letters
✅ Lowercase letters
✅ Numbers
✅ Symbols
✅ Exclude ambiguous characters (0 O I l 1)
📱 QR Code Export
Generate QR codes instantly
Download as PNG
Auto-expiring secure QR sessions
Temporary secure sharing
🕘 Password History
Local history storage
Stores recent generated passwords
One-click reuse & copy
Auto-deduplication
Persistent via LocalStorage
🛡️ Security Features
🔒 100% Client-Side

ParryKey runs entirely in the browser.

No:
❌ Server processing
❌ Cloud storage
❌ Password logging
❌ Third-party tracking
❌ Analytics collection
Yes:
✅ Local-only generation
✅ Browser cryptographic API
✅ Zero network transmission
✅ Secure randomness
🔑 Cryptographically Secure

ParryKey uses:

crypto.getRandomValues()

instead of insecure methods like:

Math.random()

This ensures enterprise-grade randomness.

🖥️ Preview
Main Interface Includes
🔐 Password Generator
📊 Security Analysis
⚙️ Configuration Panel
📱 QR Export
🕘 Password History
🏗️ Architecture
┌────────────────────────────────────────────┐
│                PARRYKEY                    │
│                                            │
│  ┌──────────────────────────────────────┐  │
│  │       Password Generation Engine     │  │
│  │     crypto.getRandomValues() API     │  │
│  └──────────────────────────────────────┘  │
│                     │                      │
│  ┌──────────────────▼──────────────────┐  │
│  │         Security Analysis Engine    │  │
│  │ Entropy • Crack Time • Strength     │  │
│  └──────────────────┬──────────────────┘  │
│                     │                      │
│  ┌──────────────────▼──────────────────┐  │
│  │           UI Dashboard Layer        │  │
│  │ HTML • CSS • JavaScript             │  │
│  └──────────────────┬──────────────────┘  │
│                     │                      │
│  ┌──────────────────▼──────────────────┐  │
│  │          Browser LocalStorage       │  │
│  │          Password History           │  │
│  └─────────────────────────────────────┘  │
└────────────────────────────────────────────┘
🚀 Quick Start
Clone Repository
git clone https://github.com/parrysecurity/parrykey.git
Open Project
cd parrykey
Launch

Simply open:

index.html

in your browser.

No installation required.

📦 Installation
Requirements
Requirement	Version
Browser	Modern Browser
JavaScript	ES6+
Internet	Optional
Backend	None
Local Setup
Linux / macOS
git clone https://github.com/parrysecurity/parrykey.git
cd parrykey
open index.html
Windows
git clone https://github.com/parrysecurity/parrykey.git
cd parrykey
start index.html
⚙️ Configuration

All settings are managed directly through the UI.

Password Options
Setting	Description
Length	4–128 characters
Uppercase	A–Z
Lowercase	a–z
Numbers	0–9
Symbols	Special characters
Exclude Ambiguous	Removes confusing characters
🎛️ Dashboard Components
🔐 Password Display
Secure password rendering
Copy functionality
Visibility toggle
Dynamic strength indicator
📊 Security Analysis Panel
Metric	Purpose
Entropy	Randomness strength
Crack Time	Estimated attack resistance
Character Pool	Charset size
Rating	Security level
Combinations	Total permutations
📱 QR Export Module
Generate QR from password
Save PNG locally
Auto-expiration timer
Secure temporary sharing
🕘 History Panel
Stores latest generated passwords
Local-only storage
Instant copy access
Automatic timestamping
🔐 Password Analysis Engine

ParryKey calculates password strength using entropy mathematics.

Entropy Formula

H=L×log
2
	​

(N)

Where:

Symbol	Meaning
H	Entropy
L	Password Length
N	Character Pool Size
Crack Time Estimation

Estimated using:

1 trillion guesses / second

to simulate modern GPU brute-force attacks.

📱 QR Export System
Features
Temporary QR sessions
Auto-expiry timer
PNG download support
Secure visual sharing
🕘 History System

Passwords are stored locally using:

localStorage
Features
Recent password history
Auto-remove duplicates
Maximum history limit
Persistent between sessions
📊 Feature Breakdown
Feature	Included
Secure RNG	✅
Entropy Analysis	✅
Crack Estimation	✅
QR Export	✅
Clipboard Copy	✅
Password History	✅
Responsive UI	✅
Dark Mode	❌
Cloud Sync	❌
Backend Required	❌
📂 Project Structure
parrykey/
│
├── index.html
├── README.md
│
├── assets/
│   ├── logo/
│   ├── screenshots/
│   └── icons/
│
└── LICENSE
🧪 Testing
Test Password Generation
Generate multiple passwords
Verify uniqueness
Check entropy calculations
Test Clipboard
Generate → Copy → Paste
Test QR Export
Generate Password → Generate QR → Download PNG
🌐 Browser Support
Browser	Supported
Chrome	✅
Edge	✅
Firefox	✅
Safari	✅
Brave	✅
🚀 Deployment
GitHub Pages
Push repository to GitHub
Go to:
Settings → Pages
Select:
Deploy from branch
Choose:
main / root
Netlify

Drag & drop the project folder into Netlify.

Vercel
vercel deploy
🔧 Troubleshooting
Problem	Solution
Clipboard not working	Use HTTPS or localhost
QR not generating	Generate password first
History missing	Enable browser LocalStorage
Weak passwords	Increase length & symbols
🤝 Contributing

Contributions are welcome.

Steps
# Fork repository
# Create feature branch
git checkout -b feature/amazing-feature

# Commit changes
git commit -m "Add amazing feature"

# Push branch
git push origin feature/amazing-feature

Then open a Pull Request.

📄 License

Distributed under the MIT License.

MIT License © ParrySecurity
💙 Acknowledgments

Built with:

HTML5
CSS3
Vanilla JavaScript
Web Crypto API

Inspired by:

Enterprise cybersecurity dashboards
Modern SaaS interfaces
Security-first design principles
<div align="center">
🔐 ParryKey
Passwords Built for the Modern Internet.

Built with 💙 by ParrySecurity
