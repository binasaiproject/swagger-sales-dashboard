# Bina Shah · Swagger Inside Sales Manager — Interview Hub

A single-page microsite I bring into the SmartBear interview process for the
**quota-carrying Sales Manager, Swagger Inside Sales (North America)** role.

It's organized so I can pull up the right section live with each person I meet:

| Section | Tuned for the conversation with |
|---|---|
| **The Role** | Keith — pipeline, outbound, business-justification, Pactflow |
| **Why Me** | Anyone — proof points + four anchor stories |
| **Leading the Team** | Chris — people-first, "how you know someone's getting it," performance management |
| **Operating Model** | Keith — forecast rhythm, inspection cadence, gamification, the stack |
| **30·60·90** | Hiring panel — my first-90-days plan, built from the role + conversations with Keith |
| **Market & Vision** | Steve — big-picture growth thesis for Swagger |
| **Values & Fit** | Kate — SmartBear values, people philosophy, "why I'll stay" |

It's one self-contained `index.html` — no build step, no external asset paths
that can break when presenting live.

---

## Deploy: GitHub → Vercel

**1. Push to GitHub**

```bash
git add index.html README.md vercel.json
git commit -m "Swagger inside sales interview hub"
git branch -M main
# create the repo on github.com first (e.g. smartbear-swagger), then:
git remote add origin https://github.com/<your-username>/smartbear-swagger.git
git push -u origin main
```

**2. Connect to Vercel**

- Go to [vercel.com/new](https://vercel.com/new) and **Import** the GitHub repo.
- Framework preset: **Other**. Build command: *(none)*. Output directory: `./` (root).
- Click **Deploy** — you'll get a `https://<project>.vercel.app` URL in ~20 seconds.
- Every future `git push` to `main` auto-redeploys.

> Already have the Vercel CLI? From this folder just run `vercel --prod`.

---

*Operating model and metrics reflect my own prior results; team figures and
forecasts referenced are illustrative for discussion. Contains no
SmartBear-confidential or compensation data.*

— Bina Shah
