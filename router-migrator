# MikroTik & UniFi Migration Tool

This project was built during my summer job at **Citymesh**.  
The tool automates migration and configuration management for large-scale MikroTik and UniFi networks.

---

## 🚀 What It Does
- **Backup configs:** Pulls and stores live device configurations locally.  
- **Safe changes:** Applies policy-driven changes with **dry-run**, **diff**, and **idempotency**.  
- **Validation:** Verifies changes against an internal **source of truth**.  
- **Rollback:** Tracks device state and supports **easy rollback** on failure.  

---

## 📊 Scale & Impact
- **Pilot:** ~300 devices, ~99.4% success (2–5 failures, all recovered).  
- **Rollout target:** ~2,500 devices.  
- **Performance:** Change time cut from **10–15 min → 15–30 sec/device** (≈ 30–40× faster).  
- **Time saved:** ~49–72.5 hours saved per 300-device batch.  

---

## 🛠️ Tech Stack
- **Python** (with `paramiko` for SSH/SFTP).  
- **RouterOS / MikroTik**.  
- **UniFi API**.  

---

## 📚 Lessons Learned
- **Latency bottlenecks:** SSH/SFTP latency dominates — solution: move to **async** (`asyncSSH` + bounded concurrency).  
- **Error handling:** Robust recovery and state cleanup are crucial (e.g., unreachable subnets).  
- **Scaling challenges:** From day one, design included **drift detection, monitoring, and automated rollback**.  

---

## 🖼️ Architecture Diagram
*(Insert migration flow diagram here once exported — PNG/SVG in `docs/` folder)*

---

## 🙏 Acknowledgements
- **Citymesh** — for the opportunity to work on real-world network automation at scale.  
- **Howest – Bachelor Multimedia en Creatieve Technologie** — for providing the foundation to tackle this project.  

---

## 🔖 Tags
`#networkautomation` `#python` `#mikrotik` `#unifi` `#netops` `#studentprojects`
