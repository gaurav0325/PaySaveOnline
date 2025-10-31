# System Overview – PaySaveOnline Architecture

PaySaveOnline consists of a lightweight browser extension and an optional backend service.

**Frontend (Extension):**

* Content script detects checkout pages and extracts currency / total.
* Popup UI (React) lets users manage cards and view savings.
* Service worker syncs FX rules and sends updates.

**Backend (FastAPI):**

* Fetches daily FX rates from ECB / Open Exchange Rates.
* Stores rule sets (DCC, surcharge patterns) in DynamoDB.
* Provides JSON endpoint for updates.

**Security:** All local storage encrypted (AES‑256). No PII transmitted.

**Deployment:** AWS Lambda + API Gateway + CloudFront.







FX \& Fee Module:



fx\_engine.js handles rate lookup and delta computation.



rules\_engine.js flags DCC and surcharge patterns.



popup\_ui.jsx displays summarised advice.

All calculations run client-side; backend provides rate and rule updates only.

