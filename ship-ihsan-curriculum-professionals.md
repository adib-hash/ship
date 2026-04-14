---
tags:
  - AI fluency
  - prompting
  - web development
  - APIs
  - full-stack development
people:
  - Adib Choudhury
tools:
  - Claude
  - ChatGPT
  - Gemini
  - GitHub
  - Vercel
---
# Ship.Ihsan — Curriculum (Professionals Edition)
### Six 90-minute sessions + weekly drop-in office hours

**Format:** Live on Zoom · Small cohort (10–12) · No prior coding experience required
**Tech stack:** Claude · ChatGPT · Gemini · GitHub · Vercel · Namecheap · Supabase · Claude Code · Capacitor

Six sessions. One per week. Each pairs one "think & plan" skill with one "build & ship" deliverable — so you leave every session with something real, not just notes.

---

## Session 1 — AI Fluency + Your First Website (Live in 90 Minutes)
**Goal:** Ship something to the live internet on day one.

**What you'll build:** A professional landing page — a portfolio, consulting one-pager, or project microsite — deployed to a real custom domain.

**What you'll learn:**
- Getting set up: Claude, ChatGPT, and Gemini accounts; GitHub; Vercel; Namecheap
- The AI landscape: what each model is good at, when to use which
- The analyst mental model: treat AI like a brilliant new hire who needs a precise brief — the quality of your prompt determines the quality of the output
- Prompting fundamentals: being specific, being objective, avoiding sycophancy, iterating to the truth
- Context is everything: sharing files, screenshots, and past work so AI understands your world
- Buying and configuring a custom domain
- Creating a GitHub repo and connecting it to Vercel for automatic deployments
- Using Claude to generate a complete HTML/CSS site from a single prompt
- Iterating with Claude: refining design, redeploying in seconds

**By the end:** A live professional website at your own domain, a push-to-deploy workflow you'll reuse forever, and a gut-level understanding of what makes AI output good or bad.

---

## Session 2 — Planning Like a Builder + Interactive Apps
**Goal:** Move beyond static pages. Build something you'll actually open every week.

**What you'll build:** An interactive web app solving a real work problem — a deal tracker, a weekly review tool, a decision framework, a prep checklist for recurring meetings — saved to your phone home screen as a Progressive Web App.

**What you'll learn:**
- Planning with AI: writing a simple PRD (product requirements doc) before you build — same discipline that separates a clean spec from a vague brief
- Thinking through UI/UX upfront: wireframing in words, user flows, "what happens when"
- The `CLAUDE.md` file: giving Claude persistent context about your project so you don't re-explain yourself every session
- The "interview me" technique: having Claude ask *you* the right questions before it writes a line of code
- Designing for mobile-first UI and touch interactions
- Color palette, typography, and spacing — visual consistency without needing a designer
- Dark mode and accessible color contrast
- Saving a web app to your phone home screen as a PWA (no App Store required)

**By the end:** A mobile-friendly tool you'll actually open every week, built from a real plan — not a vibe.

---

## Session 3 — Working With APIs
**Goal:** Build apps that pull live data from the world.

**What you'll build:** A data-driven app connected to a public API — a market data dashboard, a competitor news aggregator, a live financial visualizer, a sports or research tool tailored to your interests.

**What you'll learn:**
- What APIs are and how they work (requests, responses, keys) — in plain English, not engineering speak
- Finding and evaluating free public APIs
- Securely storing API keys with Vercel environment variables (no secrets in your code)
- Displaying and visualizing live data
- Prompting Claude to write API integration code
- **Debugging as a core skill:** reading error messages, using browser dev tools, diagnosing problems methodically
- Common failure patterns: CORS errors, rate limits, malformed requests — and how to resolve them with Claude's help

**By the end:** An app connected to the real world, plus a debugging playbook you'll use for the rest of your life — and a new appreciation for why "the data is stale" is always someone's fault.

---

## Session 4 — Full-Stack Apps With Supabase
**Goal:** Give your apps memory. Users, saved data, persistent state.

**What you'll build:** A full-stack app that stores real data — a personal CRM for your network, a deal or opportunity tracker, a shared team dashboard, a research knowledge base.

**What you'll learn:**
- Setting up a Supabase project (database, auth, storage)
- Designing simple database tables and relationships — no SQL expertise required
- Reading from and writing to a database from your front end
- User authentication basics: sign-up, login, sessions — so multiple people can use the same tool
- Using Claude to generate Supabase queries and integration code
- How Vercel + Supabase + GitHub fit together as a unified stack
- Environment variables across the stack; keeping secrets out of your codebase
- `localStorage` vs. database: when to store on-device vs. in the cloud

**By the end:** Apps that remember things. Users. Data. State across devices. The difference between a toy and a real product.

---

## Session 5 — Claude Code, the Claude API + Claude Skills
**Goal:** Level up to a professional developer workflow, add real AI features to your apps, and package your own repeatable workflows as Claude Skills.

**What you'll build:** Enhancements to a previous project using a real developer workflow — plus a new AI-powered feature using the Claude API (e.g., an email drafting assistant, a meeting notes summarizer, a proposal generator, a natural-language search interface for your own data).

**What you'll learn:**
- Installing and using Claude Code (the CLI) — the same tool professional engineers use to build serious software
- Working with a local codebase instead of copy-pasting in the browser
- `CLAUDE.md` in practice: project-level context and conventions Claude can reference automatically
- Making targeted edits, generating code directly in your project files
- Proper commits, changelogs, and version control — because "it broke and I don't know what I changed" is a fixable problem
- What the Claude API is and how it differs from Claude in the chat UI
- Making API calls from your app; handling responses and streaming text
- Designing effective system prompts for a specific use case
- Managing API keys and usage costs
- Practical patterns: summarization, Q&A over custom content, structured data extraction, turning unstructured input into clean output
- **When AI adds genuine value to an app vs. when it's just a feature that pads a demo**
- **Claude Skills:** packaging repeatable workflows — a proposal review checklist, a weekly report template, a writing voice — into reusable commands Claude Code loads on demand
- Where skills live, how they're structured, and how Claude decides when to invoke one
- Writing your first skill: turning a prompt you keep retyping into a one-command workflow
- Browsing community skills and adapting them to your own work

**By the end:** A real developer workflow, apps that can reason — not just display — and a library of reusable skills that make your Claude Code session feel like a team.

---

## Session 6 — Shipping a Native iOS App
**Goal:** Put your name on something that runs on your phone. Demo day.

**What you'll build:** A native iOS app, wrapped from one of your web apps using Capacitor. Plus a short demo to the cohort — think of it as a two-minute pitch to a room of peers.

**What you'll learn:**
- Introduction to Capacitor and how it wraps web apps for native deployment (without the App Store gatekeeper)
- Building and running your app locally on your own iPhone
- Free deployment via Apple Developer account (7-day re-sign cycle) — no annual fee required to start
- Paid deployment with an Apple Developer license ($99/year) for persistent installs and TestFlight distribution
- Using TestFlight to share your app with colleagues, clients, or beta users
- Polishing for release: app icons, splash screens, metadata
- **Demo day:** each participant gives a 2-minute walkthrough of their favorite build from the cohort — because shipping without showing it to someone doesn't count

**By the end:** A native iOS app running on your own phone, a project you can point anyone to, and the skills to keep building long after the program ends.

---

## Weekly Office Hours
**Format:** Drop-in, 45–60 min, same Zoom link every week.

Used for:
- Finishing builds that got stuck mid-week
- Debugging together
- Getting feedback on side projects you've started on your own
- Deeper questions about AI, building, or where this takes you professionally

---

## Running Themes — Every Session, Every Week

These aren't standalone lessons — they're habits that get reinforced every session:

1. **Spec before you build.** The clearer the input, the better the output. This is true for AI and for the people who work for you.
2. **Iterate, don't restart.** Targeted feedback beats re-prompting from scratch. Same principle as a good edit, not a full rewrite.
3. **Read the errors.** Error messages are directions, not walls. Professionals who can diagnose problems calmly are valuable everywhere.
4. **Ship early, improve later.** A rough live tool teaches more than a perfect unshipped one — and the people using it will tell you what actually matters.
5. **Build things you actually need.** The best tools solve problems you live with. Your frustration is the brief.
6. **Stay objective.** AI will flatter you. Evaluate output critically — same standard you'd apply to an analyst's first draft.

---

## Who This Is For

Professionals who have good instincts, clear mental models, and ideas for tools they wish existed — but no background in engineering. Operators, investors, consultants, lawyers, finance professionals, and anyone who's ever thought *I could automate this* or *there should be an app for this* and never had a path to making it real.

No coding background required. The only prerequisites are a specific problem you want to solve and a willingness to iterate.

---

## At a Glance

| Session | Focus | Key New Skill | What You Ship |
|--------:|-------|---------------|----------------|
| 1 | AI fluency + first site | Prompting, deploy pipeline | Live professional website |
| 2 | Planning + interactive apps | PRDs, `CLAUDE.md`, PWAs | A work tool on your home screen |
| 3 | APIs + debugging | External data, env vars, errors | API-powered data app |
| 4 | Full-stack + Supabase | Databases, auth, persistence | App with users & saved data |
| 5 | Claude Code + Claude API + Skills | Dev workflow, embedded AI, reusable skills | AI-powered feature + a custom Claude Skill |
| 6 | Native iOS with Capacitor | Capacitor, TestFlight, demo day | Native iOS app on your phone |

---

*Built by Adib Choudhury · [ihsan.build](https://ihsan.build)*
