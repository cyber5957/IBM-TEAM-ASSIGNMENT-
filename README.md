# IBM-TEAM-ASSIGNMENT-
# Practicals — Team Repository

**Course / Instructor:** IBM Faculty Practice

**Team:** — Practicals

**Date:** [2025-10-10]

---

## Project overview

This repository contains practical, lab-based exercises performed as part of the IBM faculty practical sessions. Each team member implemented a different practical and added reports, scripts, and redacted evidence into their assigned folder.

**Purpose:** educational — to demonstrate concepts in phishing awareness, asymmetric cryptography (RSA), and controlled penetration-testing techniques in an isolated lab environment.

> **Important:** All activities in this repository were performed in a controlled lab environment with instructor authorization. Do not use these materials for unauthorized testing or against systems for which you do not have explicit written permission.

---

## Team & Assignments

* **Prateek Sahu** — `practice-01_zphisher-phishing` — simulated phishing page & campaign (Zphisher practice).
* **Adarsh Gupta** — `practice-02_rsa-encryption` — RSA key generation, encryption, decryption, and hybrid RSA+AES demo.
* **Vinayak Chauhan** — `practice-03_vstp-backdoor` — lab exercise demonstrating controlled backdoor/access techniques using Metasploitable (lab-only, for learning defensive and detection controls).

---

## Repo structure 

```
VAPT-Practicals-Team3/
├─ README.md
├─ practice-01_zphisher-phishing/PRATEEK SAHU PHISHING PAGE ibm assignment.pdf
├─ practice-02_rsa-encryption/ADARSH GUPTA RSA ENCRYPTION AND DECRYPTION ibm assignment.pdf
└─ practice-03_vstp-backdoor/
```

---

## How to use / run (high-level)

Each practice folder includes a `README.md` with exact commands and prerequisites. Below are high-level notes:

### General prerequisites

* Local machine or VM for testing (Ubuntu recommended), up-to-date packages.
* Install Git to clone the repository.
* For cryptography demos: Python 3.8+ and `pip install cryptography` (if running Python scripts).
* For OpenSSL examples: OpenSSL CLI available on your system.
* For Metasploitable lab: run Metasploitable and attacker VM (Kali) in an isolated lab network (VM network set to host-only or internal). Never expose vulnerable VMs to the public internet.

### Running RSA demos (Adarsh)

1. Open folder name :- `ADARSH GUPTA RSA ENCRYPTION AND DECRYPTION ibm assignment.pdf`
* Evidence screenshots are stored. Do not store or publish captured credentials.
### Viewing the phishing report (Prateek)

* Open `PRATEEK SAHU PHISHING PAGE ibm assignment.pdf` for findings, campaign metrics, and redacted screenshots.
* Evidence screenshots are stored. Do not store or publish captured credentials.

### Metasploitable lab notes (Vinayak)

* The `practice-03_vstp-backdoor/README.md` contains lab setup and defensive-learning objectives. **This folder intentionally avoids step-by-step exploit commands in the main repo README.** Use the lab only with instructor permission and inside an isolated lab network.

---

## Safety, Ethics & Authorization

* All exercises are **for educational purposes only** and must be performed only on machines and networks for which you have explicit written permission.
* Do NOT upload private keys, real credentials, or sensitive data to this repository. If any sensitive data was captured accidentally, it was redacted and securely deleted before committing.
* Keep vulnerable VMs (e.g., Metasploitable) offline from the internet — use an internal-only VM network.
* This repo includes demonstration code that should be used responsibly.

---

## Contribution & Collaboration rules

* Each member should add only their assigned practice folder and related files. Use clear commit messages, e.g.: `Add report: practice-02 (Adarsh Gupta)`.
* When editing shared files (README, CONTRIBUTING), create a branch: `git checkout -b <yourname>/update-readme`, push, and open a Pull Request for review.
* Keep the repo non-punitive — these exercises are for learning. If instructor requests changes, update the relevant `report.md` and evidence accordingly.

---

## Contact / Authors

* Prateek Sahu — practice-01 (Zphisher phishing)
* Adarsh Gupta — practice-02 (RSA encryption & decryption)
* Vinayak Chauhan — practice-03 (Metasploitable lab)

---

## License

This repository is for coursework. Choose an appropriate license (e.g., MIT) or follow your course/organization policy. Replace this section with your chosen license.

---

## Final notes

If you want, I can:

* Generate a `CONTRIBUTING.md` with exact commit/PR conventions and `.gitignore` entries.
* Produce per-practice `README.md` files with runnable commands tuned for DevLang or Replit.
* Create a one-page project summary (PDF) for submission to the instructor.

Tell me which of those you'd like next and I’ll add them right away.

