## Hi there 👋 Kriangkai Khatsom

**plang007kiku-svg** · ectico_hackers@wearehackerone.com  
Independent Cyber Security Researcher | APT Hunters | Threat Intelligence Architect

---

# 🐉 OMEGA SOC LIVE DASHBOARD DISPLAY

<svg width="800" height="300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 5px #00f2ff) drop-shadow(0 0 10px #00f2ff); }
        50% { filter: drop-shadow(0 0 15px #00f2ff) drop-shadow(0 0 20px #00d9ff); }
      }
      @keyframes pulse {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.6; }
      }
      @keyframes slideIn {
        from { opacity: 0; transform: translateX(-20px); }
        to { opacity: 1; transform: translateX(0); }
      }
      .neon-header { 
        font-family: 'Courier New', monospace;
        font-size: 28px; 
        font-weight: bold;
        fill: #00f2ff;
        animation: glow 2s ease-in-out infinite;
      }
      .neon-text {
        font-family: 'Courier New', monospace;
        font-size: 14px;
        fill: #00f2ff;
      }
      .stat-label {
        font-family: 'Courier New', monospace;
        font-size: 12px;
        fill: #4caf50;
      }
      .stat-value {
        font-family: 'Courier New', monospace;
        font-size: 24px;
        font-weight: bold;
        fill: #ff1744;
        animation: glow 2s ease-in-out infinite;
      }
      .live-dot {
        fill: #4caf50;
        animation: pulse 1.5s ease-in-out infinite;
      }
      .bg-rect {
        fill: #0a0e27;
        stroke: #00f2ff;
        stroke-width: 2;
      }
      .separator {
        stroke: #00f2ff;
        stroke-width: 1;
        opacity: 0.3;
      }
    </style>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0e27;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1a1f3a;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="300" fill="url(#bgGradient)"/>
  <rect x="10" y="10" width="780" height="280" rx="10" class="bg-rect"/>
  
  <!-- Main Header -->
  <text x="400" y="45" text-anchor="middle" class="neon-header">🐉 OMEGA SOC</text>
  
  <!-- Live Status -->
  <circle cx="350" cy="65" r="4" class="live-dot"/>
  <text x="370" y="68" class="neon-text">LIVE TELEMETRY</text>
  
  <!-- Separator -->
  <line x1="30" y1="85" x2="770" y2="85" class="separator"/>
  
  <!-- Stat 1: Total IOCs -->
  <rect x="30" y="110" width="170" height="160" rx="5" fill="rgba(15, 23, 42, 0.6)" stroke="rgba(0, 242, 255, 0.2)" stroke-width="1"/>
  <text x="115" y="135" text-anchor="middle" class="stat-label">TOTAL IOC</text>
  <text x="115" y="165" text-anchor="middle" class="stat-value">782K+</text>
  <text x="115" y="252" text-anchor="middle" class="neon-text" font-size="10">Indicators Tracked</text>
  
  <!-- Stat 2: Events -->
  <rect x="215" y="110" width="170" height="160" rx="5" fill="rgba(15, 23, 42, 0.6)" stroke="rgba(0, 242, 255, 0.2)" stroke-width="1"/>
  <text x="300" y="135" text-anchor="middle" class="stat-label">EVENTS</text>
  <text x="300" y="165" text-anchor="middle" class="stat-value">54.9K</text>
  <text x="300" y="252" text-anchor="middle" class="neon-text" font-size="10">Events Processed</text>
  
  <!-- Stat 3: APT Groups -->
  <rect x="400" y="110" width="170" height="160" rx="5" fill="rgba(15, 23, 42, 0.6)" stroke="rgba(255, 23, 68, 0.3)" stroke-width="1"/>
  <text x="485" y="135" text-anchor="middle" class="stat-label" fill="#ff1744">APT TRACKED</text>
  <text x="485" y="165" text-anchor="middle" class="stat-value">13</text>
  <text x="485" y="252" text-anchor="middle" class="neon-text" font-size="10" fill="#ff1744">Groups Active</text>
  
  <!-- Stat 4: Critical Vulns -->
  <rect x="585" y="110" width="185" height="160" rx="5" fill="rgba(15, 23, 42, 0.6)" stroke="rgba(255, 23, 68, 0.3)" stroke-width="1"/>
  <text x="677" y="135" text-anchor="middle" class="stat-label" fill="#ff1744">VULNS</text>
  <text x="677" y="165" text-anchor="middle" class="stat-value">12</text>
  <text x="677" y="252" text-anchor="middle" class="neon-text" font-size="10" fill="#ff1744">Unpatched CVSS≥9</text>
</svg>

---

## 📊 System Status Overview

```
┌────────────────────────────────────────────────────────────┐
│                   🐉 OMEGA SOC METRICS                      │
├────────────────────────────────────────────────────────────┤
│                                                              │
│  ✅ Status: OPERATIONAL                                    │
│  📡 Mode: LIVE TELEMETRY (Real-time Display)               │
│  🔒 Security: READ-ONLY | ANTI-TAMPERING ENABLED           │
│  ⚡ Update: Every 3 seconds (mock refresh)                  │
│                                                              │
│  THREAT METRICS:                                            │
│  ▌▌▌▌▌▌▌▌░░ 82% Critical Threats Detected                  │
│  ▌▌▌▌░░░░░░ 41% High Priority Events                       │
│                                                              │
│  DEFENSE COVERAGE:                                          │
│  ▌▌▌▌▌▌▌▌▌▌ 100% APT Monitoring                            │
│  ▌▌▌▌▌▌▌░░░ 78% Vulnerability Coverage                     │
│                                                              │
└────────────────────────────────────────────────────────────┘
```

---

## 🎯 Dashboard Components

### 🔴 Real-Time Threat Stream
- **Latest IoC:** `c2-malware-12.ru` (CRITICAL)
- **Last Detection:** 2 minutes ago
- **Source:** OTX, Shodan, NVD

### 👥 APT Groups Under Watch
| Group | Status | Last Seen |
|-------|--------|-----------|
| APT28 | 🔴 ACTIVE | 2 hours ago |
| APT32 | 🔴 ACTIVE | 5 hours ago |
| Lazarus | 🔴 ACTIVE | 12 hours ago |
| Wizard Spider | 🔴 ACTIVE | 6 hours ago |
| FIN7 | 🔴 ACTIVE | 8 hours ago |
| Turla | 🔴 ACTIVE | 3 hours ago |
| Fancy Bear | 🔴 ACTIVE | 4 hours ago |
| Cozy Bear | 🔴 ACTIVE | 6 hours ago |
| APT36 | 🟠 MONITORING | 1 day ago |
| Darkhotel | 🟠 MONITORING | 3 days ago |
| Seedworm | 🟡 INACTIVE | 5 days ago |
| Carbanak | 🟠 MONITORING | 2 days ago |
| Equation Group | 🟡 INACTIVE | 1 week ago |

### 🔴 Critical Vulnerabilities (Top 6)
| CVE | CVSS | Severity |
|-----|------|----------|
| CVE-2024-45678 | 9.8 | 🔴 CRITICAL |
| CVE-2024-56789 | 9.6 | 🔴 CRITICAL |
| CVE-2024-67890 | 9.5 | 🔴 CRITICAL |
| CVE-2024-78901 | 9.3 | 🔴 CRITICAL |
| CVE-2024-89012 | 9.1 | 🔴 CRITICAL |
| CVE-2024-90123 | 8.9 | 🟠 HIGH |

### ☁️ Infrastructure Exposure
```
MongoDB:       45.56.162.192:27017 [UNAUTH]
Elasticsearch: 193.29.56.122:9200  [UNAUTH]
Redis:         113.212.70.104:6379 [UNAUTH]
MySQL:         5.167.68.114:3306   [WEAK_CREDS]
FTP:           203.150.199.27:21   [UNAUTH]
SSH:           223.24.62.44:22     [WEAK_CREDS]
```

---

## 🛡️ Cloud Security Alliance (CSA)

| Role | Working Group |
|------|--------------|
| ✅ **Reviewer (Key Spr)** | 🔑 Quantum-Safe Security — PQC Key Management |
| 🛡️ **Reviewer** | 🤖 Security Controls Catalog — AI Controls |

---

## 🔗 Connect With Me

| Platform | Link |
|----------|------|
| 🆔 **ORCID** | [0009-0008-5395-8526](https://orcid.org/0009-0008-5395-8526) |
| 💼 **LinkedIn** | [kriangkai-khatsom](https://www.linkedin.com/in/kriangkai-khatsom-790140229/) |
| 💻 **GitHub** | [plang007kiku-svg](https://github.com/plang007kiku-svg) |
| 🏛️ **CSA** | Quantum-Safe Security Reviewer |
| 🇹🇭 **THNCA** | Certified Participant |

---

## 📄 Copyright & Legal Notice

```
╔════════════════════════════════════════════════════════════════╗
║                   CLASSIFIED INFORMATION                        ║
╠════════════════════════════════════════════════════════════════╣
║                                                                  ║
║  © 2026 Kriangkai Khatsom - All Rights Reserved                ║
║                                                                  ║
║  DISPLAY: PUBLIC (UI Demonstration Only)                        ║
║  SOURCE CODE: PRIVATE (CLASSIFIED)                              ║
║                                                                  ║
║  ⚠️ WARNING ⚠️                                                   ║
║  - For Authorized Government & Personnel Use Only              ║
║  - Unauthorized access, use, or disclosure prohibited by law   ║
║  - All backend logic & threat data is CONFIDENTIAL              ║
║  - This display shows mock metrics for capability demo         ║
║                                                                  ║
║  AUTHORIZED USE ONLY - NOT FOR PUBLIC DISTRIBUTION             ║
║                                                                  ║
╚════════════════════════════════════════════════════════════════╝
```

---

## ✨ Features

✅ **Live Animated Dashboard** - Displays real-time metrics  
✅ **Neon Glowing Effects** - Cybersecurity aesthetic  
✅ **SVG Rendering** - Fast, scalable display  
✅ **Read-Only Display** - No data modification possible  
✅ **Anti-Tampering** - Protected interface  
✅ **Public Showcase** - System capability demonstration  
✅ **Copyright Protected** - All logic classified  
✅ **Mobile Responsive** - Works on all devices  

---

*"I don't follow standards. I help create them."* 🔥

**Status:** ✅ OPERATIONAL | **Uptime:** 99.9% | **Security:** VERIFIED

---

**Last Updated:** August 17, 2026  
**Visibility:** PUBLIC (UI Only)  
**Sensitivity:** UNCLASSIFIED (Display) | CLASSIFIED (Source Code)
