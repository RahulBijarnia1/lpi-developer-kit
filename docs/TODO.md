# Intern Program — Complete TODO List

Generated April 12, 2026. Prioritized by blocking order.

---

## BLOCKING — Must be done before sending to interns

### 1. Internal test results (Nikita, John, Bassel)
- [ ] Wait for their PRs (sent email tonight, deadline Monday)
- [ ] Did the GitHub Action auto-merge Level 1?
- [ ] Did auto-scoring post a comment on Level 2/3?
- [ ] What broke? What confused them? How long did each level take?
- [ ] Fix everything they flag

### 2. Align with Priyanka on "selection" framing
- [ ] She expects a "final selection" email with names
- [ ] Our model: "everyone who does Level 1 is in"
- [ ] Draft email to Priyanka explaining the new approach: pre-selection challenge, self-serve, everyone who participates is confirmed
- [ ] Get her buy-in before sending to students
- [ ] Confirm May 4 start date still works
- [ ] Confirm 8-week duration (May 4 — June 27)

### 3. Intern agreement / IP document
- [ ] 1-page document covering:
  - Work produced during program owned by WINNIIO AB
  - Code on personal repos: MIT licensed (open, we can use it)
  - Code merged into LifeAtlas repos: owned by WINNIIO AB
  - Content, research, designs: work-for-hire, owned by WINNIIO AB
  - NDA: no sharing internal LifeAtlas source code, credentials, customer data
  - Expected commitment: daily standups, weekly deliverables
  - Termination: either party can end participation at any time
- [ ] Review with Nicolas
- [ ] Priyanka/Amity may have their own template — check
- [ ] Must be signed before program starts (not before screening)

### 4. Teams channel
- [ ] Christalyn creates #lifeatlas-contributors
- [ ] Pin: link to repo, link to leaderboard, link to PROGRAM.md
- [ ] Set up: who can post (everyone), who are admins (Nicolas, Christalyn)

---

## BEFORE MAY 4 — Must be done before program starts

### 5. Sprint 0 backlog (real tasks, not placeholders)
- [ ] Track A tasks from the feature inventory:
  - [ ] Fix professional dashboard gate (activeRole === "PROFESSIONAL" needs self-serve)
  - [ ] Enable Strava/Oura feature flags in appConfig.ts
  - [ ] Write integration tests for chat endpoint
  - [ ] Build Telegram/WhatsApp bot using LPI + ZeroClaw
  - [ ] Extend LPI with longevity/biohacking knowledge domain (for Frank/Asprey)
  - [ ] Prompt injection testing on the chat system
  - [ ] Notification system MVP
  - [ ] Calendar integration MVP
  - [ ] Document manager MVP
- [ ] Track B tasks:
  - [ ] Transcribe 3 of Nicolas's existing presentations (Fireflies recordings)
  - [ ] Write case study: Indian manufacturing digital twin (research)
  - [ ] Write case study: Swedish smart buildings (from existing data)
  - [ ] Competitive analysis: 5 digital twin course/platform competitors
  - [ ] Draft Module 1 outline for the course ("What is a Digital Twin?")
  - [ ] Research 10 grant opportunities (Vinnova, Horizon EU, Indian DST)
  - [ ] Draft 10 LinkedIn posts about SMILE methodology
  - [ ] Build the case study database (50+ entries, tagged by industry + SMILE phase)
- [ ] Track C tasks:
  - [ ] Redesign SMILE 6-phase diagram as modern infographic
  - [ ] Design course landing page mockup
  - [ ] Design mobile-first health timeline view
  - [ ] Create investor pitch slide template
  - [ ] Design onboarding flow for new LifeAtlas users
  - [ ] Social media templates (LinkedIn post, story, carousel)
- [ ] Track D tasks:
  - [ ] Three.js widget: 3D building with sensor data hotspots (embed in React)
  - [ ] 3D human body model with clickable health metrics
  - [ ] SMILE phases as a spatial/animated journey (course content)
  - [ ] EquestRai: 3D horse model concept with training data viz
  - [ ] Conference demo scene (for investor/partner presentations)
- [ ] Track E tasks:
  - [ ] Security audit of backend (FastAPI endpoints, Supabase RLS)
  - [ ] OWASP ZAP scan of staging environment
  - [ ] Write 100 edge-case tests for chat endpoint
  - [ ] Accessibility audit (WCAG 2.2 AA) of frontend
  - [ ] Performance load test with k6
  - [ ] Audit all npm/pip dependencies for CVEs
  - [ ] Test multi-profile switching for data leakage

### 6. Auto-scoring for Tracks B-E
- [ ] Track A: already automated (GitHub Action checks code)
- [ ] Track B: content submissions need human or AI review
  - Option: code-reviewer agent reads the markdown, scores on structure/citations/depth
  - Option: team leads review manually in Week 1, automate later
- [ ] Track C: design submissions are images/Figma links
  - Option: UX-designer agent reviews (if feasible)
  - Option: Nicolas/Ahsan quick review of the top submissions
- [ ] Track D: 3D submissions are videos/builds
  - Option: manual review only (can't auto-score a 3D scene)
  - Option: checklist-based self-assessment submitted with the work
- [ ] Track E: security reports are documents
  - Option: security agent reviews methodology and findings
  - Partial auto: check if the report mentions OWASP categories, has structured findings

### 7. Leaderboard update for multi-track
- [ ] Current leaderboard only shows L1/L2/L3 from Track A
- [ ] Add track column to the leaderboard
- [ ] Track B-E submissions need a way to appear (not just code PRs)
- [ ] Impact column should show track-specific contributions
- [ ] Filter by track (not just by level)

### 8. Onboarding document (Day 1 — May 4)
- [ ] Welcome message (Christalyn sends to Teams channel)
- [ ] Tool setup checklist:
  - GitHub account added to Life-Atlas org (read access)
  - Teams channel joined
  - Dev environment running (if Track A/D)
  - Shared docs access (if Track B/C)
- [ ] Team assignments posted (based on screening results)
- [ ] Team lead introductions
- [ ] First standup time announced
- [ ] Sprint 0 backlog shared — pick your first task

### 9. Certificate template
- [ ] Design a completion certificate (Track C intern task? Meta.)
- [ ] Fields: name, track, dates, Nicolas signature, WINNIIO AB
- [ ] Letter of recommendation template (separate, for top performers)
- [ ] Priyanka/Amity may need specific wording — check their requirements

---

## NICE TO HAVE — Build during the program

### 10. Engagement agent
- [ ] Daily scan of GitHub activity per contributor
- [ ] Nudge messages for stuck/inactive interns
- [ ] Congratulations for milestones (first PR, first Level 3, etc.)
- [ ] Dropout detection (7+ days no activity)
- [ ] Weekly digest to Nicolas

### 11. Mentor agent
- [ ] Answers technical questions in Teams using LPI knowledge + docs
- [ ] Escalates to Nikita only when it can't answer
- [ ] Logs every question → feeds into FAQ/README improvements

### 12. LifeAtlas Professional View integration
- [ ] Embed leaderboard in Professional dashboard
- [ ] Contributor profiles as "clients" in the CRM view
- [ ] Sprint backlog as a kanban board inside LifeAtlas
- [ ] Meeting intelligence from standup transcripts (Fireflies)

### 13. Contributor program documentation
- [ ] "How we run 101 contributors with AI agents" — case study for the course
- [ ] Process documentation for running the next cohort
- [ ] Template for partner companies to run their own contributor programs

### 14. Partner-specific work streams
- [ ] Deri (Freedom Founders): longevity platform module — Track A + B
- [ ] Frank/Asprey: biohacking data integration — Track A
- [ ] Charlotta/CurifyLabs: personalized medicine twin concept — Track B research
- [ ] EquestRai/Mulawa: equine digital twin — Track A + D
- [ ] Careium: senior care predictive model — Track A + B
- [ ] SSIP/Paulo: space pharma simulation — Track B research

### 15. Advanced challenges (for interns who crush Levels 1-3)
- [ ] Level 4: Own a module — define scope, build it, ship it
- [ ] Level 5: Lead a team — run standups, review PRs, mentor others
- [ ] Level 6: Design the next challenge — evolve the program itself
- [ ] A2A protocol implementation between intern agents
- [ ] LangGraph multi-agent workflows
- [ ] Security hardening challenges (CTF-style)

---

## TRACKING

| Item | Owner | Status | Deadline |
|------|-------|--------|----------|
| Internal test (Nikita/John/Bassel) | Nicolas | Sent | Mon Apr 14 |
| Priyanka alignment | Nicolas/Christalyn | Not started | By Apr 18 |
| Intern agreement | Nicolas | Not started | By Apr 28 |
| Teams channel | Christalyn | Not started | By Apr 18 |
| Sprint 0 backlog | Nicolas + Claude | Not started | By May 2 |
| Track B-E scoring | Claude | Not started | By May 2 |
| Leaderboard multi-track | Claude | Not started | By May 2 |
| Day 1 onboarding doc | Christalyn + Claude | Not started | By May 3 |
| Certificate template | Track C intern? | Not started | By Jun 20 |
| Engagement agent | Claude | Not started | Sprint 1 |
| Mentor agent | Claude | Not started | Sprint 1 |
| LifeAtlas integration | Track A interns | Not started | Sprint 2+ |
