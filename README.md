# Prairos — README

**Human judgment, precisely placed.**
A tech-enabled, human-centered AI-readiness tool that helps underrecognized professionals turn hidden judgment into visible proof.

Last updated for **version 0.9**.

---

## THE ONLY FILES YOU NEED RIGHT NOW

Everything is at version **0.9**. Use these three and ignore the rest:

| File | Who it's for | Publish? |
|------|-------------|----------|
| **`index.html`** | Your beta testers (this is the v0.9 tester build, ready to host) | Yes — this is your live site |
| **`prairos-v0.9-internal.html`** | You only (facilitator / founder) | Private link only — keep to yourself |
| **`prairos-v0.9-participant.html`** | Future paid/free pilot participants | When you start pilots |

`index.html` and `prairos-v0.9-tester.html` are the same file — `index.html` is just the name hosting services use for a homepage.

The matching `.jsx` files are the editable source. The `.html` files are what you open/publish. You normally only touch the `.html`.

---

## WHAT EACH VERSION CONTAINS

| Build | Workflow + Dashboard | Proof Loop | Facilitator Console | Founder View + Grant | Sample data | Results auto-send |
|-------|:--:|:--:|:--:|:--:|:--:|:--:|
| **Tester** (`index.html`) | yes | yes | no | no | none | yes (to your Google Sheet) |
| **Participant** | yes | yes | no | no | none | no |
| **Internal** | yes | yes | **yes** | **yes** | yes (for demos) | no |

- **Tester** is the clean, public build. No internal notes, no example answers, no founder dashboards. Sends each finished session to your Google Sheet.
- **Participant** is the same clean experience, kept for paid/free pilots later.
- **Internal** is your private cockpit: everything the others have, plus the Facilitator Console (live-call prompts, tags, signals, boundaries, call structure) and the Founder/Grant dashboards and Swimlane.

---

## HOW TO USE THE FILES

**To preview any build:** double-click the `.html` file, or right-click → Open With → your browser. It runs with no install.

**To publish the tester build (your live site):**
1. Open `index.html` locally first and click all the way through to confirm it works.
2. Commit `index.html` to your GitHub repo. Netlify auto-deploys to `prairos.netlify.app`.
3. Share `prairos.netlify.app` with testers. Same link forever — when you publish a new `index.html`, everyone gets the update on their next visit. No new link needed.

**To use the internal build:** publish `prairos-v0.9-internal.html` as a *separate, private* Netlify site (or just open it on your own computer during calls). Do not share that URL. Optionally add Netlify's free password protection (Site settings → Visitor access).

---

## RESULTS COLLECTION (tester build)

When a tester clicks **Finish & Send My Results**, their full session is sent to your Google Sheet automatically — free, no third party.

- Setup steps are in **`SHEET-SETUP-GUIDE.md`**.
- The Sheet URL is already wired into the current tester build.
- Each tester's data stays on their own device until they hit Finish.
- New fields (like the Understanding Check) appear automatically as new columns in your Sheet.

---

## THE WORKFLOW (what a user does)

1. **Home** — orientation, privacy notice, the Proof Loop preview
2. **Info & FAQ**
3. **Get Started** — intake (situation, AI, self-talk, energy check-in)
4. **Where You Are Now** — baseline 1–5 self-scores
5. **Your Strengths** — rate kinds of thinking (plain language)
6. **Name the Pattern** — precision statement
7. **Show Your Judgment** — judgment evidence map
8. **Working With AI** — where AI helps vs. where you stay accountable
9. **Your Judgment Story** — a usable story
10. **Your Next Move** — placement plan + **Check for Understanding**
11. **Track Your Progress** — proof-pace actions
12. **Own Your Work** — milestones (Drafted → Reviewed → I own this)
13. **Finish & Reflect** — after-scores, testimonial, would-pay, feedback
14. **My Dashboard** — Proof Loop status, what to do next, export report

Everything runs offline; all AI-style drafts are generated locally from the user's own words. Nothing requires a subscription.

---

## CONFIGURATION (in the .jsx source, near the top)

- `CONTACT_EMAIL` = `prairostherelaymethod@gmail.com` (the feedback button)
- `SHEET_URL` = your Google Apps Script endpoint (results collection)
- `VERSION` = the label shown in the header

To change any of these, edit the `.jsx`, then rebuild the `.html`. Or just ask and I'll do it.

---

## VERSION HISTORY

| Version | What changed |
|---------|-------------|
| v0 | First full 16-section build |
| v0.1 | Storage fallback, async save, standalone HTML |
| v0.2 | Version stamping |
| v0.3 | Corrected logo, plain language, Info/FAQ moved up, split into Internal + Participant |
| v0.4 | Round "i" dot, Founder/Grant stripped from participant, responsive mobile |
| v0.5 | Dark/light mode, progress bar, welcome-back, accessibility, clean tester build |
| v0.6 | Tech-enabled / human-centered positioning, new FAQs |
| v0.7 | Free Google Sheet backend, contact email wired |
| v0.8 | The Prairos Proof Loop — Understanding Check, loop visual, status badge, swimlane (internal) |
| **v0.9** | Facilitator Console (internal), scripted-guide "feel seen" prompts (tester + participant) |

---

## OLD FILES — SAFE TO IGNORE OR DELETE

Every file numbered v0 through v0.8, plus `prairos.jsx`, `prairos-v0.jsx`, and `prairos-v0-backup.jsx`, is a previous iteration. They're kept only as history. If you want a clean folder, the only files you need to keep are:

- `index.html`
- `prairos-v0.9-internal.html` and `.jsx`
- `prairos-v0.9-participant.html` and `.jsx`
- `prairos-v0.9-tester.jsx`
- `README.md`
- `SHEET-SETUP-GUIDE.md`

Tell me if you'd like me to clear out the old versions for you.

---

## DISCLAIMERS (built into the tool)

Prairos is a professional-development prototype. It is not legal, HR, clinical, hiring, medical, crisis, or employment-selection advice. It does not guarantee employment, income, promotion, wage, or business outcomes. All generated drafts come from the user's own words for them to edit and own.
