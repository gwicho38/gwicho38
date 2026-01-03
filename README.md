# 👋 Hi, I'm Luis (@gwicho38)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lefv-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lefv)
[![Website](https://img.shields.io/badge/Website-lefv.info-00ADD8?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.lefv.info)
[![Email](https://img.shields.io/badge/Email-luis@lefv.io-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luis@lefv.io)

**SWE | MS in CS @ UIUC | JD @ NYU Law | CS @ FSU | ECON @ FIU**

</div>

---

## 🚀 Featured Projects

### ⚡ [Outlet](https://www.outlet.rent) - EV Charging Marketplace

> *P2P Electric Vehicle Charging*

[![Outlet Tests](https://github.com/EverlongTechnologies/Outlet/actions/workflows/test-validation.yml/badge.svg)](https://github.com/EverlongTechnologies/Outlet)
[![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?logo=flutter)](https://flutter.dev)
[![Phoenix](https://img.shields.io/badge/Phoenix-1.7-FF6600?logo=phoenixframework)](https://phoenixframework.org)

A full-stack peer-to-peer marketplace connecting EV drivers with charging station hosts. Built with **Flutter** (iOS/Android/Web) and **Phoenix/Elixir** backend.

**🎯 Key Features:**

- 📍 Google Maps integration with real-time location search
- 💳 Stripe Connect payment processing with host payouts
- 🔐 JWT authentication with OAuth (Google, Apple)
- ⏱️ Real-time charging session monitoring via WebSockets
- 📊 Analytics dashboard for hosts and guests
- 🚗 Smart vehicle integration (Smartcar API)

**🛠️ Tech Stack:**

- **Frontend:** Flutter, Dart, Provider, GoRouter, Material Design 3
- **Backend:** Phoenix/Elixir, PostgreSQL + PostGIS, Redis, Oban
- **Infrastructure:** Fly.io, Docker, GitHub Actions
- **Integrations:** Stripe, Google Maps, Firebase, Tigris Storage

[🔗 Try Outlet](https://www.outlet.rent)

---

### 🏛️ [GovMarket.trade](https://govmarket.trade) - Politician Trading Tracker

[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://python.org)

A transparency platform that tracks and analyzes stock trades made by politicians worldwide using public disclosure data.

**✨ Features:**

- 📈 Real-time politician stock trade tracking with ML-powered signals
- 🌍 Global coverage: US Congress, UK Parliament, EU Parliament, US States
- 📊 Interactive dashboard with portfolio tracking and order management
- 🔍 Comprehensive scrapers for official government sources
- 🤖 Automated data collection with scheduling and monitoring

**🛠️ Tech Stack:**

- **Frontend:** React, TypeScript, Tailwind CSS
- **Backend:** Supabase (PostgreSQL + Edge Functions)
- **Data Pipeline:** Python scrapers, ML preprocessing
- **Sources:** US House/Senate, UK Parliament, EU Parliament, State disclosures

[🔗 Live Platform](https://govmarket.trade) | [📱 View Code](https://github.com/gwicho38/politician-trading-tracker)

---

### 🔐 [lsh-framework](https://www.npmjs.com/package/lsh-framework) - Encrypted Secrets Manager

[![npm](https://img.shields.io/npm/v/lsh-framework?logo=npm)](https://www.npmjs.com/package/lsh-framework)
[![npm downloads](https://img.shields.io/npm/dt/lsh-framework)](https://www.npmjs.com/package/lsh-framework)
[![Node.js CI](https://github.com/gwicho38/lsh/actions/workflows/node.js.yml/badge.svg)](https://github.com/gwicho38/lsh/actions)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://typescriptlang.org)

The simplest way to sync `.env` files across all your machines. AES-256 encrypted secrets with IPFS storage.

**✨ Features:**

- 🔒 AES-256-CBC encryption for all secrets
- ☁️ Zero-config IPFS sync via Storacha network
- 🔄 Multi-environment support (dev, staging, prod)
- 👥 Team collaboration with shared encryption keys
- ⏰ Automatic secret rotation with built-in daemon
- 📤 Export to JSON, YAML, TOML, or shell exports

```bash
npm install -g lsh-framework
lsh init && lsh sync
```

[📚 View on NPM](https://www.npmjs.com/package/lsh-framework) | [📱 View Code](https://github.com/gwicho38/lsh)

---

### 🐍 [mcli-framework](https://pypi.org/project/mcli-framework/) - Universal Script Runner

[![PyPI](https://img.shields.io/pypi/v/mcli-framework?logo=pypi&logoColor=white)](https://pypi.org/project/mcli-framework/)
[![PyPI downloads](https://static.pepy.tech/badge/mcli-framework/month)](https://pepy.tech/project/mcli-framework)
[![Tests](https://github.com/gwicho38/mcli/actions/workflows/ci.yml/badge.svg)](https://github.com/gwicho38/mcli/actions)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://pypi.org/project/mcli-framework/)

Run any script, anywhere, with intelligent tab completion. Transform scripts into versioned, schedulable workflows.

**✨ Features:**

- 🚀 Zero-config script execution (Python, Shell, Jupyter notebooks)
- 📦 Portable workflows stored in `~/.mcli/workflows/`
- 🔄 IPFS cloud sync for immutable workflow sharing
- ⏰ Built-in scheduler and daemon support
- 🔗 Lockfile versioning for reproducibility
- 🤖 AI chat integration (OpenAI, Anthropic, Ollama)

```bash
pip install mcli-framework
mcli run ./script.py  # Run any script instantly
```

[📚 View on PyPI](https://pypi.org/project/mcli-framework/) | [📱 View Code](https://github.com/gwicho38/mcli)

---

### 🔌 [mcli-framework](https://marketplace.visualstudio.com/items?itemName=gwicho38.mcli-framework) - VS Code Extension

[![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/gwicho38.mcli-framework?logo=visual-studio-code&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=gwicho38.mcli-framework)
[![VS Code Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/gwicho38.mcli-framework)](https://marketplace.visualstudio.com/items?itemName=gwicho38.mcli-framework)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

Visual Studio Code extension for mcli-framework with Jupyter-like workflow editing.

**✨ Features:**

- 📝 Cell-based editing interface for workflow JSON files
- ⚡ Live code execution (Python, Shell, Bash, Zsh, Fish)
- 🎯 Monaco editor with IntelliSense
- 📊 Rich markdown documentation cells

[📚 View on Marketplace](https://marketplace.visualstudio.com/items?itemName=gwicho38.mcli-framework)

---

### 🖥️ [Nativefier](https://github.com/gwicho38/nativefier) - Maintained Fork

[![npm](https://img.shields.io/badge/npm-v53.0.0-CB3837?logo=npm&logoColor=white)](https://www.npmjs.com/package/nativefier)
[![Electron](https://img.shields.io/badge/Electron-39.0.0-47848F?logo=electron&logoColor=white)](https://electronjs.org)
[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?logo=node.js&logoColor=white)](https://nodejs.org)

A maintained fork of the archived Nativefier project. Wrap any web app into a native desktop application.

**✨ Features:**

- 🌐 Convert any website to a desktop app (macOS, Windows, Linux)
- 🎨 Automatic icon and name retrieval
- 💉 Custom JS & CSS injection support
- 🐳 Docker support for cross-platform builds

```bash
npm install -g nativefier
nativefier 'web.whatsapp.com'
```

[📱 View Code](https://github.com/gwicho38/nativefier)

---

## 💻 Tech Stack

### Languages

![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

### Frameworks & Tools

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Phoenix](https://img.shields.io/badge/Phoenix-FF6600?style=flat-square&logo=phoenixframework&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Cloud & DevOps

![Fly.io](https://img.shields.io/badge/Fly.io-7B3FF2?style=flat-square&logo=fly.io&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

---

## 🎓 About Me

- 🎓 **Currently:** Pursuing MS in Computer Science @ **UIUC**
- ⚛ **Role:** Software Engineer, Founder
- 🔨 **Working on:** [Outlet](https://www.outlet.rent) - EV Charging Marketplace
- 👀 **Primary stack:** Flutter, Elixir/Phoenix, TypeScript, Python
- ⏳ **Experience with:** C, C++, Java, distributed systems
- 💞️ **Passion:** Building accessible technology and spreading knowledge
- 🌱 **Interests:** Clean energy, civic tech, data transparency, mobile development

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gwicho38&theme=radical)
![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gwicho38&theme=radical)

</div>

---

## 🏆 Highlights

- 🚀 Built and deployed production full-stack marketplace app (iOS/Android/Web)
- ⚡ Architected real-time EV charging platform with Phoenix/Elixir backend
- 💳 Integrated Stripe Connect for multi-party payment processing
- 🗺️ Implemented geospatial search with PostgreSQL + PostGIS
- 🧪 Achieved 100+ automated tests with CI/CD pipeline
- 📱 Shipped cross-platform mobile apps to App Store and Google Play
- 🏛️ Created civic transparency tools for public accountability
- 📦 Published open-source packages to NPM, PyPI, and VS Code Marketplace
- 🔌 Developed VS Code extension for CLI workflow management

---

## 🤝 Let's Connect

I'm always happy to collaborate and spread access to technology! Whether you're interested in:

- 🚗 EV infrastructure and clean energy tech
- 🏛️ Civic tech and government transparency
- 📱 Mobile app development
- ⚡ Real-time systems and distributed architectures
- 📦 Open source package development
- 🎓 Computer science education

**Feel free to reach out:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/lefv)
[![Email](https://img.shields.io/badge/Email-luis@lefv.io-D14836?style=for-the-badge&logo=gmail)](mailto:luis@lefv.io)
[![Website](https://img.shields.io/badge/Website-lefv.info-00ADD8?style=for-the-badge&logo=google-chrome)](https://www.lefv.info)

---

<div align="center">

### 💡 "Building technology that makes a difference"

![Profile Views](https://komarev.com/ghpvc/?username=gwicho38&color=blueviolet&style=flat-square)

</div>

---

<!---
gwicho38/gwicho38 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
