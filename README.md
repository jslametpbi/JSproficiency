# JS Proficiency Passport AI

Professional static platform package for an AI-integrated English proficiency ecosystem: AI diagnostic test, practice course, mock test, secure institutional ITP-style real test, score report, QR-verifiable certificate, certificate registry, admin approval, item bank, analytics, and proctoring review.

## Main Features

- Premium landing page with working access buttons.
- Candidate, Lecturer, Proctor, and Admin access.
- Admin login uses PIN only.
- Candidate, Lecturer, and Proctor login uses registered email and password.
- Lecturer and Proctor registrations require Admin approval.
- AI Diagnostic Level Test with a 60-item blueprint across six skills.
- Practice Course with listening audio Play, Replay, and Stop controls.
- Mock Test with audio controls.
- Secure Real Test in institutional ITP-style format: Listening, Structure and Written Expression, and Reading Comprehension.
- Real Test listening audio is restricted to one-time play.
- Score Report with CEFR interpretation and institutional ETP-style conversion.
- Certificate Registry with candidate ID, certificate code, score, CEFR, integrity status, and QR verification.
- Scannable QR certificate image generated from the certificate verification link.
- Professional item bank with more than 1000 demo records across six skills.
- Navigation menu with Back, Dashboard, role-based pages, and Logout.

## Access

Admin PIN:

```text
JS2026
```

Demo Candidate:

```text
Email: joko.demo@proficiency.local
Password: demo12345
Role: Candidate / Test Taker
```

Preloaded participant credentials are provided in `participant-credentials.csv`.

## GitHub Pages Deployment

1. Create or open your repository:

```text
JSproficiency
```

2. Upload these files directly to the repository root:

```text
index.html
styles.css
app.js
manifest.json
README.md
participant-credentials.csv
```

3. Open:

```text
Settings → Pages → Deploy from a branch → main → /root → Save
```

4. Open the live app:

```text
https://jslametpbi.github.io/JSproficiency/
```

## Note

This static version is suitable for demonstration, piloting, and interface validation on GitHub Pages. For formal high-stakes deployment, connect it to secure backend authentication, encrypted databases, server-side item storage, verified proctoring evidence, and a protected certificate registry.
