# The Clubhouse Moorooka — Web Tools

Live site: **[clubhousemoorookatpt.netlify.app](https://clubhousemoorookatpt.netlify.app)**

---

## Tools

### The Ten Point Test
[clubhousemoorookatpt.netlify.app](https://clubhousemoorookatpt.netlify.app)

Score any idea against the five club principles — two points each, ten in total. Ideas must reach 5 or above to be considered by the President.

**Principles**
1. Community Counts
2. Beyond the Bar
3. Members Matter
4. Fill the Floor
5. Self-Sufficient

Features: per-principle notes, session tracking, CSV export, presentation slide view.

---

### Membership Sign-Up (Prototype)
[clubhousemoorookatpt.netlify.app/join](https://clubhousemoorookatpt.netlify.app/join)

Mobile-optimised sign-up page for bar and event use. Collects name, email, and mobile. Designed to be completed in under 60 seconds. Confirmation screen doubles as a drink voucher for bar staff. Form submissions are captured via Netlify Forms.

> **Prototype note:** Payment is handled manually at the bar. Stripe integration and confirmation email are pending before go-live.

---

## Deployment

Hosted on [Netlify](https://netlify.com), deployed automatically on every push to `main`.

To update either tool, edit the relevant file and push:

```bash
git add <file>
git commit -m "description of change"
git push
```

Netlify deploys within ~30 seconds of a push.

---

## Stack

Static HTML/CSS/JS — no build step, no dependencies beyond Google Fonts.
