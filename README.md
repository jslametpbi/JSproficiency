# JS Proficiency Passport AI — Field Testing Edition (78 Participants)

This package is a cloned field-testing edition of the JS Proficiency Passport AI platform prepared for a 78-participant institutional field test.

## Main field-testing additions

- 78 anonymized participant records preloaded.
- Integrated participant registration codes using the official `EPP-FT-2026-###` format.
- 78 certificate records using `EPP-CERT-FT-2026-###`.
- Field Testing Dashboard added for Admin/Lecturer review.
- CSV export for all 78 participant records.
- Diagnostic, practice, mock, real-test, score report, proctoring, analytics, and certificate modules remain integrated.
- Real test follows an institutional ITP-style structure: Listening 50 items, Structure and Written Expression 40 items, Reading 50 items; total 140 items / 115 minutes.
- Listening control behavior remains separated by mode: Diagnosis/Practice/Mock have Play, Replay, Stop; Real Test has one-time listening only.
- Reading passages and clickable reading answer options are included.
- Certificate verification is available through the public `#verify/` page.

## Access

### Admin

PIN: `JS2026`

### Demo candidate

Email: `joko.demo@proficiency.local`  
Password: `demo12345`

### Field-test participants

Use this pattern:

- Email: `field.p001@proficiency.local` to `field.p078@proficiency.local`
- Password: `field12345`

Example:

- `field.p001@proficiency.local`
- `field12345`

## Deployment to GitHub Pages

Upload these files directly to the repository root:

- `index.html`
- `styles.css`
- `app.js`
- `manifest.json`
- `README.md`

Then activate GitHub Pages from `Settings → Pages → Deploy from branch → main → /root`.

## Important disclaimer

This is a static field-testing prototype. It stores data locally in the browser for demonstration and field simulation. For high-stakes official testing, deploy a protected backend, encrypted authentication, server-side database, proctoring storage, and validated item-bank governance.
