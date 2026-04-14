# Ship.Ihsan — Curriculum v3
### Six 90-minute sessions + weekly drop-in office hours

**Format:** Live on Zoom · Small cohort (10–12) · No prior coding experience required
**Tech stack:** Claude · ChatGPT · Gemini · GitHub · Vercel · Namecheap · Supabase · Claude Code · Capacitor

This is the v2 curriculum (9 modules) compressed into 6 sessions without cutting the native iOS app finale. Each session pairs one "think & plan" skill with one "build & ship" deliverable, so students leave every session with something real.

---

## Session 1 — AI Fluency + Your First Website (Live in 90 Minutes)
**Goal:** Ship something to the live internet on day one.

**What they'll build:** A personal website (portfolio, landing page, or bio site) deployed to a real custom domain.

**What they'll learn:**
- Getting set up: Claude, ChatGPT, and Gemini accounts; GitHub; Vercel; Namecheap
- The AI landscape: what each model is good at, when to use which
- The intern-to-analyst mental model: treat AI like a new hire whose value grows with how you manage it
- Prompting fundamentals: being specific, being objective, avoiding bias, iterating
- Context is everything: sharing files, screenshots, and examples
- Buying and configuring a custom domain
- Creating a GitHub repo and connecting it to Vercel for automatic deployments
- Using Claude to generate a complete HTML/CSS site from a single prompt
- Iterating with Claude: refining design, redeploying instantly

**By the end:** A live personal website at their own domain, a repeatable "push-to-deploy" workflow, and a gut feel for prompting that actually works.

---

## Session 2 — Planning Like a Builder + Interactive Apps
**Goal:** Move beyond static pages. Build something people can actually play with.

**What they'll build:** An interactive web app (e.g., a browser game like Snake, a flashcard app, or a personal utility tool) saved to their iPhone home screen as a Progressive Web App.

**What they'll learn:**
- Planning with AI: writing a simple PRD (product requirements doc) before you build
- Thinking through UI/UX upfront: wireframing in words, describing layouts, user flows
- The `CLAUDE.md` file: giving Claude persistent context about your project
- The "interview me" technique: having Claude ask *you* the right questions
- Designing for mobile-first UI and touch interactions
- Color palette, typography, and spacing consistency
- Dark mode and accessible color contrast
- Saving a web app to your iPhone home screen as a PWA

**By the end:** A mobile-friendly interactive app that lives on their phone's home screen, built from a real plan — not a vibe.

---

## Session 3 — Working With APIs
**Goal:** Build apps that feel alive. Real-world data, real debugging.

**What they'll build:** A data-driven app pulling from a public API (e.g., a music discovery tool, a sports stats dashboard, a live weather visualizer).

**What they'll learn:**
- What APIs are and how they work (requests, responses, keys)
- Finding and evaluating free public APIs
- Securely storing API keys with Vercel environment variables
- Displaying and visualizing live data
- Prompting Claude to write API integration code
- **Debugging as a core skill:** reading error messages, using browser dev tools, diagnosing problems
- Common failure patterns: CORS errors, rate limits, malformed requests — and how to resolve them with Claude's help

**By the end:** An app connected to the real world, plus a debugging playbook students will use for the rest of their lives.

---

## Session 4 — Full-Stack Apps With Supabase
**Goal:** Give apps memory. Users, logins, saved state.

**What they'll build:** A full-stack app with persistent data (e.g., a reading tracker, a personal CRM, a habit logger, or a voting/ranking tool).

**What they'll learn:**
- Setting up a Supabase project (database, auth, storage)
- Designing simple database tables and relationships
- Reading from and writing to a database from your front end
- User authentication basics: sign-up, login, sessions
- Using Claude to generate Supabase queries and integration code
- How Vercel + Supabase + GitHub fit together as a unified stack
- Environment variables across the stack; keeping secrets out of your codebase
- `localStorage` vs. database: when to store on-device vs. in the cloud

**By the end:** Apps that remember things. Users. Data. State across devices.

---

## Session 5 — Claude Code, the Claude API + Claude Skills
**Goal:** Level up the workflow, add real AI features to your apps, and start packaging your own repeatable workflows as Claude Skills.

**What they'll build:** Enhancements to a previous project using a professional developer workflow — plus a new AI-powered feature powered by the Claude API (e.g., a writing assistant, a personalized recommender, a natural-language search box).

**What they'll learn:**
- Installing and using Claude Code (the CLI)
- Working with a local codebase instead of copy-pasting in the browser
- `CLAUDE.md` in practice: project-level context for codebase conventions
- Making targeted edits, generating code in your own project files
- Proper commits, changelogs, and version control
- What the Claude API is and how it differs from Claude in the chat UI
- Making API calls from your app; handling responses and streaming text
- Designing effective system prompts for a specific use case
- Managing API keys and usage costs
- Practical patterns: summarization, Q&A over custom content, structured data extraction
- **When AI adds genuine value to an app vs. when it's just noise**
- **Claude Skills:** packaging repeatable workflows (a design review, a deploy checklist, a writing voice) into reusable skills Claude Code loads on demand
- Where skills live, how they're structured (a folder with a `SKILL.md` and any supporting files), and how Claude decides when to invoke one
- Writing your first skill: turning a prompt you keep retyping into a one-command workflow
- Browsing community skills and adapting them to your own projects

**By the end:** A real developer workflow, plus apps that can think — not just display.

---

## Session 6 — Shipping a Native iOS App
**Goal:** Put your name on something that runs on your own phone. Demo day.

**What they'll build:** A native iOS app, wrapped from an existing web app using Capacitor. Plus a short demo to the cohort and (optionally) family.

**What they'll learn:**
- Introduction to Capacitor and how it wraps web apps for native deployment
- Building and running your app locally on your iPhone
- Free deployment via Apple Developer account (7-day re-sign cycle)
- Paid deployment with an Apple Developer license ($99/year) for persistent installs
- Using TestFlight to share your app with friends, family, or beta testers
- Polishing for release: app icons, splash screens, metadata
- **Demo day:** each student gives a 2-minute walkthrough of their favorite build from the cohort

**By the end:** A native iOS app running on their own phone, a portfolio link they can share anywhere, and the skills to keep shipping long after the program ends.

---

## Weekly Office Hours
**Format:** Drop-in, 45–60 min, same Zoom link every week.

Used for:
- Finishing exercises that got stuck mid-week
- Debugging together
- Getting feedback on side builds students start on their own
- Deeper questions about AI, building, college, or careers

---

## Running Themes — Every Session, Every Week

These aren't standalone lessons; they're habits that get reinforced every session:

1. **Plan before you build.** The clearer the input, the better the output.
2. **Iterate, don't restart.** Targeted feedback beats re-prompting from scratch.
3. **Read the errors.** Error messages are directions, not walls.
4. **Ship early, improve later.** A rough live app teaches more than a perfect unshipped one.
5. **Build things you actually want.** Motivation comes from solving your own problems.
6. **Stay objective.** Don't let AI flatter you — evaluate output critically.

---

## Who This Is For

Curious 7th–12th graders who have ideas for tools, apps, or projects they wish existed — and who are ready to stop waiting and start building. No coding background required. No math prerequisite. Just curiosity and a willingness to iterate.

---

## At a Glance

| Session | Focus | Key New Skill | What They Ship |
|--------:|-------|---------------|----------------|
| 1 | AI fluency + first site | Prompting, deploy pipeline | Live personal website |
| 2 | Planning + interactive apps | PRDs, `CLAUDE.md`, PWAs | Interactive app on home screen |
| 3 | APIs + debugging | External data, env vars, errors | API-powered app |
| 4 | Full-stack + Supabase | Databases, auth, persistence | App with users & saved data |
| 5 | Claude Code + Claude API + Skills | Dev workflow, embedded AI, reusable skills | AI-powered feature + a custom Claude Skill |
| 6 | Native iOS with Capacitor | Capacitor, TestFlight, demo day | Native iOS app on their phone |

---

*Built by Adib Choudhury · [ihsan.build](https://ihsan.build)*
