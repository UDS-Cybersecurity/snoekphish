# 🛡️ UDS Phishing Detector Project - snoekphish

Welcome to the official project for the **UDS Cyber Security Division Phishing Detector**. This project aims to build a smart, privacy-conscious **phishing detection browser extension** powered by a hybrid detection engine (rule-based and ML).  

Version 1 will ship as a **browser extension** for detecting phishing attempts in real-time across websites and webmail clients.

---

## 🚀 Project Roadmap

### ✅ Phase 1: Planning & Research (Week 1)
- Define phishing indicators for browser-based attacks
- Research datasets and phishing signatures
- Explore extension APIs (Chrome/Firefox)
- Set up GitHub Organization and Repositories

### ✅ Phase 2: Architecture Design (Week 2)
- Define component architecture:
  - Browser extension (HTML/JS)
  - Detection engine (Python backend / WASM call)
  - Communication between extension & backend (e.g., local API or in-extension logic)
- Finalize tech stack & data flow

### 🛠️ Phase 3: Development (Weeks 3–6)

#### 🔹 Browser Extension (Frontend)
- DOM scanner: Scan links, inputs, and text for phishing traits
- Visual indicators (red flag icon, warnings)
- UI/UX: Popup UI + Settings page

#### 🔹 Detection Engine (Backend - Python)
- Rule-based logic (regex, domain match, content)
- ML model (TF-IDF, phishing word frequency, classifier)
- Create scoring/reporting mechanism

#### 🔹 Communication Layer
- Interface between JS and Python (e.g., REST API or WASM if needed)

#### 🔹 Output / Alerting
- Show safe/suspicious flags
- Provide risk scores and explain why a site is flagged

### ✅ Phase 4: Integration & Testing (Week 7)
- Connect browser extension to the backend engine
- Perform functional and phishing case testing
- Compatibility testing (Chrome, Firefox)

### ✅ Phase 5: Documentation & Deployment (Week 8)
- Finalize README files and user documentation
- Package extension for browser stores
- Launch GitHub pages or docs site

---

## 👥 Team Roles (10 Members)

| Name / Alias    | Role                             | Responsibility                                               |
|-----------------|----------------------------------|--------------------------------------------------------------|
| **Lead (You)**  | Project Coordinator              | Timeline, GitHub management, integration                     |
| Member 1        | Frontend Dev                     | Browser Extension UI, popup, DOM injection                   |
| Member 2        | Frontend Dev                     | Browser API interaction, site scanning logic                 |
| Member 3        | Detection Dev (Rule-Based)       | Regex patterns, keyword match, domain logic                  |
| Member 4        | Detection Dev (ML-Based)         | Build + train ML classifier for phishing detection           |
| Member 5        | Feature Extractor Dev            | Extract links, domains, content from visited pages           |
| Member 6        | Communication Layer Dev          | Connect extension with Python backend (API, messaging)       |
| Member 7        | Test Engineer                    | Test extension with phishing samples, report issues          |
| Member 8        | DevOps & Packaging               | Build system, package extension, CI/CD (e.g., GitHub Actions)|
| Member 9        | Documentation & Outreach         | Write docs, create guides, assist in deployment              |

---

## 🛠 Tech Stack

| Component       | Technology                |
|----------------|---------------------------|
| Extension       | JavaScript, HTML, CSS     |
| Backend Engine  | Python (scikit-learn, Flask/FastAPI) |
| Communication   | Web APIs, possibly local API or WASM bridge |
| CI/CD           | GitHub Actions, Webpack   |
| Testing         | Selenium, Jest, Custom scripts |

---

## 📚 Resources
- [PhishTank Datasets](https://phishtank.org/)
- [Chrome Extension Dev Guide](https://developer.chrome.com/docs/extensions/mv3/)
- [Mozilla Extension Guide](https://extensionworkshop.com/)
- [scikit-learn for ML](https://scikit-learn.org/)
- [OWASP Phishing Resources](https://owasp.org/www-community/phishing)

---

## 📌 Contributing
- Fork relevant repos and open PRs
- Use issue templates for bugs and features
- Weekly sync meetings on [platform TBD]

---

## 📃 License
MIT License – see individual repos for details.

---

Let's make the web safer — one click at a time.

