# 🎣 Phishing Awareness Simulation

> A hands-on cybersecurity awareness project demonstrating real-world phishing techniques through a controlled, ethical simulation — conducted by **Himanshu Soni** in association with **Naviotech Solution Pvt Ltd**.

---

## 📌 Project Overview

This project simulates a real phishing attack in a safe, educational environment to measure how susceptible users are to common social engineering tactics. Participants received a convincing phishing email, were led through a fake login portal, and were then educated on how to identify and avoid phishing attempts. Behavioral data was collected via a post-simulation feedback survey.

**Conducted by:** Himanshu Soni  
**Organization:** Naviotech Solution Pvt Ltd  
**Date:** June 2026  
**Participants:** 19 individuals (12 opened, 3 reported suspicious, 4 did not open)

---

## 🗂️ Repository Structure

```
phishing-awareness-simulation/
│
├── README.md                            ← You are here
│
├── report/
│   └── Phishing_Report_Final_v3_1.docx  ← Full project report
│
├── presentation/
│   └── PhishingAwarenessSimulation.pptx ← Slide deck
│
├── documentation/
│   └── phishing_image_documentation.pdf ← Annotated screenshot documentation
│
├── data/
│   ├── phishing_click_stats.html         ← Email open/click statistics (interactive charts)
│   └── phishing_survey_pie_charts.html   ← Participant feedback survey results (interactive charts)
│
└── screenshots/
    ├── Screenshot_2026-06-12_001247.png  ← Fig 1: Phishing email (Gmail sent box)
    ├── Screenshot_2026-06-12_001303.png  ← Fig 2: Informed consent screen
    ├── Screenshot_2026-06-12_001352.png  ← Fig 3: Simulated Google login page
    ├── Screenshot_2026-06-12_001445.png  ← Fig 4: Real credential warning triggered
    ├── Screenshot_2026-06-12_001522.png  ← Fig 5: Simulation complete (dummy credentials)
    ├── Screenshot_2026-06-12_001533.png  ← Fig 6: Awareness training completion screen
    ├── Screenshot_2026-06-12_001554.png  ← Fig 7: Participant feedback form
    ├── Screenshot_2026-06-12_125253.png  ← Google Forms responses overview
    ├── Screenshot_2026-06-12_125308.png  ← Survey Q1 & Q2 results
    ├── Screenshot_2026-06-12_125328.png  ← Survey Q3 results
    ├── Screenshot_2026-06-12_125344.png  ← Survey Q4: convincingness ratings
    ├── Screenshot_2026-06-12_125354.png  ← Survey Q5: prior awareness ratings
    └── Screenshot_2026-06-12_125308.png  ← Participant comments
```

---

## 🔬 Simulation Methodology

The simulation was conducted in three stages:

### Stage 1 — Phishing Email Delivery
A carefully crafted phishing email with subject line **"Password Reset"** was sent to 19 participants from a personal Gmail account, impersonating Google's support team. It included urgency tactics (30-minute expiry), a suspicious Netlify link, and social engineering cues (authority, fear, trust).

### Stage 2 — Fake Login Portal (MailSecure Training Portal)
Participants who clicked the link were taken to a simulated Google login page hosted at `stunning-beijinho-0c3b48.netlify.app`. The portal included:
- An informed consent screen before any phishing content
- A fake Google Sign-In page with annotated red flags
- Real-time detection of dummy vs. real credential entry
- Immediate educational feedback after form submission

### Stage 3 — Awareness Training & Feedback
After the simulation, all participants were shown an awareness training screen with 5 key security lessons and directed to a Google Form feedback survey.

---

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| Emails sent | 19 |
| Emails opened | 12 (63.2%) |
| Reported as suspicious | 3 (15.8%) |
| Clicked login button (of openers) | 83.3% |
| Almost entered real credentials | 41.7% |
| Noticed fake page immediately | 33.3% |
| Noticed only after looking closely | 50% |
| Avg. convincingness rating (1–5) | ~3.7 |
| Prior awareness rated 1/5 | 50% |

> **Critical finding:** 41.7% of participants who interacted with the fake page nearly entered their real credentials — despite multiple visible red flags and warning banners.

---

## 🔴 Red Flags Demonstrated

The simulation highlighted the following phishing indicators:

- **Fake domain:** `google-secure-login.com` ≠ `google.com`
- **Suspicious sender:** Personal Gmail address, not `@google.com`
- **Generic greeting:** "Dear User" instead of the recipient's actual name
- **Urgency tactic:** "Link expires in 30 minutes"
- **Unverified HTTPS:** No trusted certificate authority padlock
- **Slightly off branding:** Minor layout and font differences from real Google UI
- **Unsolicited email:** No prior password reset was requested

---

## 🛡️ Security Lessons Delivered

Every participant received these actionable takeaways at the end of the simulation:

1. ✅ Verify the URL before entering any credentials
2. ✅ Confirm the sender's identity in emails
3. ✅ Check for valid HTTPS and trusted certificates
4. ✅ Be cautious of urgent or alarming requests
5. ✅ Always use Multi-Factor Authentication (MFA)

> **Key lesson:** Never enter your real password on an unfamiliar website. When in doubt, go directly to the official site by typing the URL yourself.

---

## ⚖️ Ethical Considerations

This simulation was conducted with full ethical safeguards:

- All participants gave **informed consent** before viewing any simulated phishing content
- **No real data was stored or transmitted** at any point
- Participation was **entirely voluntary**; users could leave at any time
- The purpose was **purely educational** — to demonstrate phishing risks without real-world harm
- A full disclosure screen appeared immediately upon clicking the phishing link

---

## 💬 Participant Feedback (Selected Comments)

> *"I think this kind of training should be done more often — it's a practical way to learn about phishing without any real risk."*

> *"I didn't notice anything off until I saw the warning banner. This was a good reminder to always check the address bar before entering credentials."*

> *"Helpful demo. It made me realize how easy it is to overlook small details like domain names when you're in a hurry."*

> *"The fake login page looked surprisingly real at first glance — the logo and layout were very close to the actual Google sign-in page. The URL was the biggest giveaway once I checked it."*

---

## 📁 Deliverables

| File | Description |
|------|-------------|
| `Phishing_Report_Final_v3_1.docx` | Complete written project report |
| `PhishingAwarenessSimulation.pptx` | Presentation slide deck |
| `phishing_image_documentation.pdf` | Annotated visual evidence document |
| `phishing_click_stats.html` | Interactive email engagement statistics |
| `phishing_survey_pie_charts.html` | Interactive participant survey results |
| `screenshots/` | Full set of simulation screenshots (12 images) |

---

## 👤 Author

**Himanshu Soni**  
Cybersecurity Project — Major Project Submission  
Naviotech Solution Pvt Ltd | June 2026  
📧 himanshusoni86549@gmail.com

---

*This project was conducted solely for educational and awareness purposes. All simulated phishing content was designed to teach, not to deceive. No personal data was collected or stored at any stage.*
