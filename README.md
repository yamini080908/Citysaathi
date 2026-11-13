# CitySaathi MVP starter

A beginner-friendly responsive website / installable PWA prototype.

## Run locally
1. Install Node.js (optional) or use VS Code's Live Server extension.
2. Open this folder in VS Code.
3. Install the **Live Server** extension.
4. Right-click `index.html` → **Open with Live Server**.
5. Test the site in your browser.

You can also use Python's built-in server from this folder:
`python -m http.server 8000`
Then open `http://localhost:8000`.

## Included
- Responsive citizen interface for phone and desktop
- Water connection, property tax and public complaint request forms
- Demo request reference numbers
- Local browser-based status tracking
- Officer dashboard with demo status updates
- English, Kannada, Hindi, Tamil and Telugu hero text
- Basic PWA manifest and service worker

## Important limitations
This is a front-end demonstration, NOT a production municipal system.
- Requests are stored only in the current browser's localStorage.
- There is no real account/login, server database, officer authentication, Gemini integration, WhatsApp, UPI payment, document OCR, municipal API, or real submission.
- The file picker does not upload documents.
- Do not enter real Aadhaar, bank, or other sensitive citizen data.

## Production architecture to build next
- Frontend: React / Next.js
- Backend: Python FastAPI on Cloud Run
- Database/auth: Firebase Authentication + Firestore
- AI: Gemini API through a secure backend (never expose API keys in browser code)
- Document storage: private Cloud Storage with consent, retention and access controls
- Messaging: WhatsApp Business Platform after business verification
- Payments: authorized payment gateway / official municipal payment integration
- Municipal submissions: approved APIs or a controlled, auditable browser workflow
- Security: role-based access, encryption, audit logs, DPDP compliance, human approval for uncertain/high-impact actions

Before public launch, obtain municipal authorization and security/privacy review.
