# biometric-web
Web-based Face Biometric System for Multiple User Enrollment &amp; Verification

# Biometric Web Demo (Face Recognition)

This is a **Web-based Face Biometric System** for **Multiple User Enrollment & Verification**.

## Features

- Multiple users enrollment
- Face verification (1:N matching)
- Mobile-friendly UI
- CDN-only (face-api.js & models loaded online)
- Vercel-ready (HTTPS compatible)

## How to Use

1. Open `index.html` → Enter name → Press **Enroll Face** → Face template saved
2. Open `verify.html` → Show face → Verified alert if match found
3. Camera permission required
4. Works on Mobile Chrome / PC Chrome

## Deployment

- Push folder to GitHub repo
- Deploy on [Vercel](https://vercel.com) → HTTPS URL generated
- No local models required (all CDN)

## Notes

- Distance threshold: 0.6 (adjustable in verify.html)
- LocalStorage used to store face templates (for demo only)
- Production: use server + encrypted database
