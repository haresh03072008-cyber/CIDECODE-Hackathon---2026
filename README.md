# ShadowTrace AI
### Explainable Behavioral Cybercrime Intelligence for Coordinated Identity Detection
> CIDECODE 2026 · 3rd Edition · CCITR Tech Hackathon · PES University, Bengaluru

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Available-00D4FF)](https://haresh03072008-cyber.github.io/CIDECODE-Hackathon---2026/)
[![License](https://img.shields.io/badge/Data-OSINT%20Only-green)]()
[![Compliance](https://img.shields.io/badge/IT%20Act%202000-Compliant-blue)]()

---

## 🔍 What is ShadowTrace AI?

ShadowTrace AI is a SOCMINT prototype that helps cybercrime investigators 
identify coordinated digital identities operating across multiple social 
media aliases. Unlike keyword or metadata tools, it operates on **behavioral 
patterns** — making it resilient to alias changes and account recycling.

---

## ⚙️ How It Works

1. Investigator submits two social media handles
2. Five behavioral signals are extracted and scored
3. A 0–100% Coordinated Activity Score is generated
4. XAI reasoning explains which signals triggered the verdict
5. A timestamped incident report is downloaded for handoff

---

## 🧠 Five Behavioral Signals

| # | Signal | Method | Weight |
|---|--------|--------|--------|
| 1 | Posting Timing Patterns | Cross-account temporal delta | 20% |
| 2 | Multilingual Phrase Similarity | Sentence-transformer embeddings (HI+EN) | 25% |
| 3 | Hashtag Cluster Overlap | Jaccard similarity | 20% |
| 4 | Stylometric Analysis | Punctuation, emoji, structure fingerprint | 20% |
| 5 | Payment Link Patterns | Shortened URL hash matching | 15% |

---

## 🎯 Risk Tiers

| Tier | Score | Action |
|------|-------|--------|
| 🔴 HIGH | 70–100% | Escalate to cybercrime unit |
| 🟡 MEDIUM | 40–69% | Place under active monitoring |
| 🟢 LOW | 0–39% | Archive for periodic review |

---

## ✅ Validation

- Evaluated on **200 anonymised, ethically collected public posts**
- Achieved **87% verdict agreement** against ground-truth annotations
- Deterministic scoring pipeline — reproducible across repeated analyses

---

## ⚖️ Legal Compliance

- IT Act 2000 §66C, §66D
- IPC §420
- CERT-In Incident Response Guidelines
- OSINT-only analysis — no private data accessed
- Outputs are investigative leads, not legal evidence

---

## 🚀 Run Locally

No installation required. Open `index.html` in any browser.

---

## 📄 Supporting Report

Full technical report available in `ShadowTrace_AI_Report.pdf`

---

## ⚠️ Disclaimer

Outputs are investigative leads only. Human investigator review 
is required before any escalation or legal action.
