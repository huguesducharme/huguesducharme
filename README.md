# Hi there, I'm Narek Khachatryan 🛡️

### Junior Application Security Engineer (AppSec / DevSecOps)

I am a 3rd-year Cybersecurity student at Russian New University (RosNOU) specializing in **Application Security (AppSec)** and backend infrastructure. My engineering philosophy is simple: security should be built-in, not bolted on. I focus on securing Go applications, containerized environments, and CI/CD pipelines through automated analysis and architecture hardening.

### 📫 Let's Connect
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/codesnf)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bobkiask@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/huguesducharme)
[![SourceCraft](https://img.shields.io/badge/SourceCraft-181717?style=for-the-badge&logo=github&logoColor=white)](https://sourcecraft.dev/lct-hackaton-2026/case-18-repo-health-score-team-58/)

---

### 🛠️ Tech Stack & Security Tooling

**Languages & Infrastructure:**
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
`Docker Compose` `Git`

**AppSec, DAST/SAST & Offensive Tools:**
![Semgrep](https://img.shields.io/badge/Semgrep-5A5A5A?style=for-the-badge&logo=semgrep&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-000000?style=for-the-badge&logo=aquasecurity&logoColor=00B4E6)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=Wireshark&logoColor=white)
`Nmap` `tcpdump` `Threat Modeling`

**Incident Response & Monitoring:**
`Windows Event Log` `Sysmon` `PowerShell`

**Standards & Methodologies:**
`OWASP Top 10` `OWASP ASVS` `CWE Top 25` `CVSS v3.1/v4.0` `EPSS` `SBOM (CycloneDX/SPDX)` `BOLA/IDOR`

---

### 🚀 Featured Security Projects & Contributions

#### 🔒 [Open-Source Security Hardening: Tufin/oasdiff](https://github.com/Tufin/oasdiff)
*Independent security audit of a popular Go-based infrastructure tool (1400+ stars).*
* **SAST/SCA Triage:** Analyzed automated findings from **Semgrep** and **Trivy**, successfully filtering out False Positives in mock data and building robust `.semgrepignore` profiles.
* **Container Security (Hardening):** Implemented the Principle of Least Privilege in the `Dockerfile` using multi-stage builds and non-root execution environments to mitigate `missing-user-entrypoint` risks.
* **CI/CD Supply Chain Security:** Mitigated RCE vectors by removing unsafe `curl | bash / python` piping in GitHub Actions and pinned dependencies to exact cryptographic SHAs using `ratchet`.

#### 📊 SourceCraft Repo Health Score (Hackathon)
*Designed the backend and database architecture for a comprehensive repository security scoring service.*
* Built with **Go**, **PostgreSQL**, and **Docker**.
* Developed algorithms to calculate a Security Health Score based on static analysis metrics, CI/CD misconfigurations, and code vulnerabilities.

#### 🐦 Kanary Server (Threat Intelligence)
*A custom honeytoken and threat intelligence service developed from scratch.*
* Developed the backend in **Go** and **PostgreSQL**, deployed via **Docker**.
* Configured accurate extraction of attacker attributes (Origin IP, User-Agent, Referer) by parsing `X-Forwarded-For` headers through L7-proxies/load balancers.
* Implemented strict UUID validation at the DBMS level to protect against DoS attacks from automated scanners.
* Designed asynchronous Telegram incident alerting via goroutines to eliminate time-based attack vectors.

#### 🛡️ API Security Scanner (SAST/DAST Tool)
*A concurrent CLI scanner for automated vulnerability hunting in web applications.*
* Built in **Go**, utilizing worker-pool concurrency for high-performance static secret scanning (JWT, AWS tokens, API keys).
* Integrated a DAST module to test Rate Limiting, CORS configurations, security headers, and basic logical vulnerabilities (BOLA/IDOR).
* Exports JSON reports for seamless CI/CD pipeline integration, packaged in a multi-stage Docker container.

#### 🕵️ Crypto-Phishing Investigation & OSINT (March 2026 - April 2026)
*Academic security research into active threat actors.*
* Leveraged **Burp Suite** to intercept and modify traffic, discovering and exploiting a **PHP Type Juggling** vulnerability in JSON payloads on a live crypto-phishing platform.
* Conducted blockchain forensics via TRONSCAN to track stolen assets and map attacker infrastructure.
* Presented findings on defense mechanisms at a specialized security conference.

---

### 🎓 Education & Training
* **Russian New University (RosNOU)** (2024–2028)
  * Bachelor's Degree, 3rd year. Full-time.
  * Major: Computer Science and Engineering. Specialization: Cybersecurity.
* **Certifications:** Certified Network Defender (CND) *(In Progress)*.
* **Practical Platforms:** TryHackMe, LetsDefend, PortSwigger Web Security Academy.

### ⚡ Beyond the Terminal
When I'm not writing Go code or hunting for vulnerabilities, you can find me training in the boxing gym (2 years) 🥊, working out at home/gym (5+ years), or hand-carving small objects out of phenolic resin.
