# SKILL: Geopolitical Briefing Update

## Trigger

User says any of: "run the briefing," "news update," "what's happening," "briefing skill," "update the briefing," or otherwise asks for a framework-driven news assessment.

---

## Workflow

### Step 1: Load Framework Context

Search project knowledge for:
- "context.md" — orient to current project state
- "Analytical Notebook" — check for active empirical tests and open questions
- The most recent geopolitical briefing artifact — this is the baseline to update against

Identify: What were the last-tracked variables? What predictions were active? What scenario assessments were in place?

### Step 2: Gather Current Events

Run web searches (date-scoped, include year) across these domains:

**Iran/Gulf crisis (if active):**
- Iran conflict latest, Operation Epic Fury
- Hormuz strait shipping insurance
- Iran nuclear program status
- Gulf state diplomatic moves
- China response to Iran conflict
- Trump Iran negotiations

**Structural indicators:**
- Gold price (track against $5,100–5,400 threshold as de-dollarization signal)
- Oil price + supply disruption status
- BRICS institutional developments
- China EV/solar/battery trade data or policy
- US sanctions / SWIFT actions
- Alternative payment system developments (CIPS, bilateral swap lines)

**AI/Tech paradigm:**
- Open-source AI model releases or benchmarks
- US chip export controls developments
- Chinese semiconductor progress
- AI military/surveillance applications
- DeepSeek or other non-US frontier model news

**MANDATORY — Military force posture (run every briefing, separate from narrative layer):**
- US military deployments, redeployments, force movements (search defense-beat outlets: Defense One, War on the Rocks, USNI News — not wire services)
- Carrier strike group positions
- Airborne/ground force deployment orders
- Munitions production and stockpile reporting
- Allied force movements

This search must be run *separately* from the diplomatic/narrative search. Force movement stories appear in defense-beat outlets under different framing than diplomatic stories and will not surface through narrative-layer queries. The gap between stated narrative posture and material force movements is itself a primary analytical datum — track it as a distinct variable.

Use a minimum of 5–8 web searches. For complex or fast-moving situations, scale up to 10–15. Fetch full articles for the most significant developments.

### Step 3: Framework Analysis

For each significant development, apply the relevant frameworks. Do not list frameworks mechanically — show how each event *tests, confirms, complicates, or disconfirms* specific framework predictions.

**Mandatory framework applications:**

| Event type | Primary frameworks | What to assess |
|---|---|---|
| US military/coercive action | Hudson (protection racket), Calleo (fourth formula), Gramsci (consent collapse) | Is this extraction or stabilization? Does it accelerate defection? |
| Subordinate actor building alternatives | Rent-avoidance theory, Acharya (multiplex nodes) | What's being avoided? Does the alternative add a multiplex node? |
| Financial market stress | Kindleberger (cascade), Acharya (institutional density absorbs) | Which prediction gains evidence? |
| Technology development | Perez (Installation/Deployment), AI diffusion hypothesis | Does this serve old power structures or new productive deployment? |
| Alliance/coalition dynamics | Olson (free-rider), Gramsci (bloc coherence) | Who's free-riding? Is consent holding? |
| Energy transition data | Solar theology thesis, Perez (paradigm substrate) | Does this confirm un-monopolizability? |

**Flag convergence signals:** When multiple frameworks point to the same diagnosis from different angles, note it explicitly. This is the thesis's core method.

**Flag disconfirmation:** If an event contradicts a framework prediction, say so. Don't explain it away.

### Step 4: Update Tracking Variables

Revisit each variable from the previous briefing's watchlist. For each:
- What's changed since last assessment?
- What's the current read?
- Has any variable resolved (confirmed/disconfirmed)?
- Should any new variables be added?

### Step 5: Scenario Assessment

Reassess the three scenarios against current evidence:

1. **China-centered multipolar trade order** — probability, trend direction, key evidence
2. **America as New Rome** — probability, trend direction, key evidence  
3. **Systemic chaos / turbulence** — probability, trend direction, key evidence

Note if scenario probabilities have shifted since last briefing and *why*.

### Step 6: Identify Analytical Notebook Updates

Flag any insights from the news analysis that should be added to the Analytical Notebook:
- New cross-framework connections
- Empirical tests that gained or lost evidence
- Original formulations that emerged
- Open questions that advanced or need revision

State these explicitly at the end so they can be captured.

---

## Output Format

**Default:** HTML artifact matching the March 5, 2026 briefing design (dark theme, IBM Plex fonts, masthead, framework analysis blocks, data strip, scenario boxes with probability bars, watchlist table, footer with active frameworks and sources).

**If user requests shorter:** Markdown in-chat summary, no artifact. Still follow the analytical workflow but compress to the key moves.

**Structure of full briefing:**
1. Masthead (title, date, day count if ongoing conflict)
2. Status ticker (red, urgent-status one-liner if applicable)
3. Lead story (biggest development, framework analysis integrated)
4. Data strip (gold, oil, key financial indicators)
5. Secondary stories (2-column grid if multiple significant developments)
6. Framework analysis block (the convergence diagnosis)
7. Scenario assessment (three boxes with probability bars)
8. Variables to track (table: variable / significance / current read)
9. Footer (active frameworks, sources cited)

---

## Quality Checks

Before outputting, verify:

- [ ] **Narrative-material gap checked:** Force posture search was run separately from diplomatic search; any gap between stated narrative and material movements is noted explicitly as an analytical datum, not explained away
- [ ] Every factual claim is sourced from a web search conducted in this session (not from training data for post-cutoff events)
- [ ] Framework applications are *analytical*, not mechanical labeling ("Hudson: bad" is not analysis)
- [ ] At least one disconfirmation or complication is noted — if every data point confirms the thesis, something is being filtered out
- [ ] The scenario probability bars reflect actual shifts from new evidence, not inertia
- [ ] New variables or resolved variables are flagged
- [ ] Analytical Notebook implications are stated explicitly
- [ ] Sources are listed in the footer

---

## What This Skill Does NOT Do

- Does not update the Analytical Notebook directly (flags what should be added; user decides)
- Does not revise the thesis document (that's a separate task)
- Does not produce a comprehensive research report — this is a *briefing*, optimized for situational awareness and framework testing
- Does not speculate beyond what the frameworks and current evidence support
