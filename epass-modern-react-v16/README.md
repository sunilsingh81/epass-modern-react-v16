# ePASS Modern Design V16 — Applicant Experience Excellence

A **fictional demonstration**, not an official NC DHHS service. Use test data only. No real application is transmitted.

## Features
- Full V15 application sections, including voter registration, FNS guidance, expedited benefits, SSN/sponsor/marital status, address choices, household and financial questions.
- Two distinct signals: minimum filing readiness (name, address, demo signature) and additional-information completion.
- Context-aware optional questions; irrelevant follow-up fields remain hidden.
- Actionable review checklist with jump links; optional answers never block minimum filing.
- Why-are-we-asking explanations for sensitive questions.
- Browser-local draft persistence, including household members.
- Demo-only receipt and printable confirmation; no backend or agency transmission.
- Responsive desktop/mobile layout and keyboard-focus styles.

## Development
```sh
npm install
npm run dev
```

## Netlify deployment
Connect the repository to Netlify. Build command: `npm run build`. Publish directory: `dist`. Alternatively, run `npm install && npm run build` locally, then **upload the contents of `dist`** to Netlify's manual deploy screen. Do not upload the source ZIP as a manual deployment.

## Important limitations
- Drafts live in localStorage on the same browser/device; they are not secure server-side accounts or encrypted storage. Do not enter sensitive personal data.
- Demo signature, receipt, expedited screening and voter selection are simulations, not legally validated workflows.
- Filing rules, county DSS address routing, policy language, accessibility, multilingual content, and security require Division/legal and user testing before any production use.
- Progress is a heuristic of selected optional fields, not an eligibility or agency completeness determination.
