# 💳 PaySaveOnline  
### Smarter checkouts. No hidden fees.

**PaySaveOnline** is a privacy-first browser extension that protects shoppers from hidden foreign-exchange mark-ups, Dynamic Currency Conversion (DCC), and card surcharges — directly at checkout.

---

## 🧭 Overview
Millions of online shoppers quietly lose 3–5 % every time they pay in the wrong currency or with the wrong card.  
PaySaveOnline analyses checkout pages in real time and gives a short, accurate nudge:
> “Pay in EUR to save £3.20.”  
> “Avoid Amex — this merchant adds a 1.5 % surcharge.”

No personal data leaves the user’s device. Advice is generated locally, in under a second.

---

## 📁 Folder Structure

| Folder | Description |
|--------|--------------|
| **01_Requirements** | Functional, non-functional, and compliance requirements. |
| **02_ProjectPlan** | Milestones, sprint plans, risks, and team roles. |
| **03_Competition** | Market positioning and competitor analysis. |
| **04_Architecture** | System design, frontend and backend overviews, security model. |
| **06_Privacy_and_Compliance** | Privacy, GDPR, security audits, disclaimers. |
| **07_BusinessPlan** | Market opportunity, revenue model, pricing, monetisation strategy. |
| **08_Marketing** | Launch plan, SEO, outreach, and referral programmes. |
| **09_Advertising** | Ad campaigns, creatives, budgets, and performance tracking. |
| **10_Financials** | Forecasts, expenses, funding, and investor deck summary. |
| **11_Market_and_CustomerResearch** | User personas, pain points, surveys, and analytics approach. |
| **12_Operations** | Support, feedback loops, monitoring, and incident management. |
| **13_Pitch_and_Presentations** | Pitch narrative, hooks, deck outline, and investor Q&A. |
| **14_Documentation** | API docs, user manual, developer guide, changelogs. |
| **15_Roadmap_and_Strategy** | MVP plan, partnerships, expansion roadmap. |

---

## 💡 Key Features
- Detects checkout pages automatically.  
- Identifies FX, DCC, and surcharge risks.  
- Works entirely offline — no account or data tracking.  
- Provides monthly “you saved” summaries.  
- Built with **React + FastAPI + AWS serverless stack**.

---

## 🧱 Architecture Summary
**Frontend:**  
Browser extension (Chrome/Edge/Firefox) built on Manifest V3, React, and IndexedDB for local storage.  

**Backend:**  
FastAPI micro-service providing FX rates and rule updates, deployed via AWS Lambda and API Gateway.  

**Security:**  
- AES-256 encryption for local data.  
- HTTPS-only communication.  
- GDPR-compliant “no data shared” design.

---

## 💰 Business Model
Freemium + Affiliate + White-Label  
- Free: one saved card, basic alerts.  
- Plus (£2.99 / month): unlimited cards, savings dashboard.  
- Partner: co-branded or licensed versions for fintechs and travel platforms.  

Target Market: UK & EU cross-border shoppers, travellers, and expats.  

---

## 🚀 Roadmap
| Phase | Timeline | Objective |
|--------|-----------|-----------|
| **MVP** | Months 0–3 | Chrome extension with FX/DCC alerts. |
| **Beta** | Month 4 | User testing + feedback loop. |
| **Public Launch** | Month 6 | Chrome Store + Product Hunt release. |
| **Growth** | Year 1 | 25 K users + first B2B integration. |
| **Expansion** | Year 2–3 | Mobile app + merchant SDK + AI recommendations. |

---

## 🔒 Compliance & Trust
- Outside PCI-DSS scope (no card data stored).  
- GDPR compliant (local processing only).  
- Transparent privacy policy and third-party security audit planned before launch.  

---

## 📣 How to Contribute
Pull requests are welcome. Please open an issue first to discuss changes.  
Follow [DeveloperGuide.md](14_Documentation/DeveloperGuide.md) for setup and coding standards.

---

## 🧑‍💼 Contact
**Founder & Architect:** Gaurav Agarwal  
📧 info@paysaveonline.com  
🌐 [www.paysaveonline.com](https://www.paysaveonline.com) *(placeholder)*  

---

> “You compare prices before you buy. We protect you from the hidden costs when you pay.”
