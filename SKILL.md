---
name: consulting-frameworks
description: Apply structured consulting and operations frameworks to analyze any business, operations, or systemic problem. Use this skill whenever the user wants to analyze a problem using frameworks like Strategy, Triple Constraints, Tradeoff Analysis, Root Cause Analysis (RCA/Fishbone), SIPOC, Bullseye, or System Map. Also trigger when users say things like 'help me break down this problem', 'analyze this system', 'what's causing this issue', 'map this process', 'identify root causes', 'what are the tradeoffs', 'who are the stakeholders', 'what's broken in this system', or any request to systematically diagnose a business or operational challenge. Trigger even if users don't name a specific framework — if they describe a messy problem and want structured analysis, this skill applies.
---

# Consulting Frameworks Skill

This skill guides structured problem analysis using seven proven consulting frameworks. The goal is to produce comprehensive, data-backed analysis that a user can then use to build visual deliverables (slides, diagrams, maps).

## Critical Rules

1. **Problem Statement First.** Before applying ANY framework, establish a clear problem statement. Never start with frameworks — start with understanding the problem.
2. **Ask before assuming.** When key context is missing (industry specifics, stakeholder details, internal process knowledge), ask the user. Do NOT fabricate organizational details.
3. **Research what you can.** Use web search for publicly available data — industry statistics, benchmarks, regulatory context, demographic data. Only ask the user for things you genuinely cannot find.
4. **Stay in the current state.** These frameworks analyze what IS, not what SHOULD BE (except Bullseye which explicitly contrasts Actual vs. Desired). Do not jump to solutions.
5. **Data over opinions.** Every claim should be backed by data where possible. Cite sources. Use statistics, percentages, and concrete numbers.
6. **Frameworks serve the problem, not the other way around.** Recommend which frameworks are most useful for the user's specific situation rather than forcing all six.

## Workflow

### Phase 1: Problem Scoping

When a user presents a problem, first establish:

1. **Domain**: What industry/sector is this in?
2. **Scope**: What specific aspect of the problem are we analyzing? (A whole system? A single process? A customer experience gap?)
3. **Problem Statement**: Draft a problem statement that includes:
   - Brief context
   - Present impact with statistics/data
   - "Resulting in..." consequences
   - Process domain
   - A hook that speaks to both logic and emotion
   - NO solutions embedded in the statement

Ask the user to confirm or refine the problem statement before proceeding.

### Phase 2: Mandatory Entry Frameworks

After the problem statement is confirmed, ALWAYS execute these four frameworks in order. These are not optional — they establish the strategic context and scope that every deeper analysis depends on:

1. **Strategy** → `strategy.md` — Analyze the current strategic positioning (unique position, tailored activities, trade-offs, improvement continuity)
2. **Triple Constraints** → `triple-constraints.md` — Scope all People (60%), Process (20%), and Technology (20%) involved
3. **Tradeoff Analysis** → `tradeoff.md` — Name the Speed vs. Cost vs. Quality tensions and what's being sacrificed

These three frameworks are ALWAYS required regardless of the problem or context.

### Phase 3: Deep-Dive Framework Selection

After the entry frameworks are complete, recommend which additional frameworks would add value based on the problem. Ask the user which ones they want to run. Once the user selects, **execute all selected frameworks immediately** — do not stop or ask again.

Available deep-dive frameworks:

- **RCA / Fishbone** → `rca.md` — Why is it broken? Deep causal analysis across domains
- **Bullseye** → `bullseye.md` — Where does actual diverge from desired at each organizational layer?
- **SIPOC** → `sipoc.md` — What does the full process chain look like end-to-end?
- **System Map** → `system-map.md` — How do systemic forces (Drivers, Mainstay, Enablers) interact?

Recommend based on the problem:
- If the user needs to understand WHY something is failing → RCA
- If the user needs to see structural misalignment → Bullseye
- If the user needs to map a specific process → SIPOC
- If the user needs to understand ecosystem-level dynamics → System Map

After the user picks, run every selected framework and then proceed to Cross-Framework Synthesis.

### Phase 4: Framework Execution

For each framework, read the corresponding reference file before generating output:
- Strategy → `strategy.md`
- Triple Constraints → `triple-constraints.md`
- Tradeoff → `tradeoff.md`
- RCA → `rca.md`
- SIPOC → `sipoc.md`
- Bullseye → `bullseye.md`
- System Map → `system-map.md`

Each reference file contains the framework structure, what to include, how to organize it, and what questions to ask the user if information is missing.

### Phase 5: Output Format

For each framework, produce:

1. **Structured analysis** in clearly organized sections with headers matching the framework's components
2. **Key Insight** — a synthesis paragraph at the end of each framework explaining the "so what"
3. **Data citations** — every statistic must include its source
4. **Sufficient detail** for the user to build their own visual deliverable (slide, diagram, poster) from the output

Do NOT generate visualizations. The output is comprehensive written analysis that serves as the content layer for the user's own visual work.

### Phase 6: Cross-Framework Synthesis

After completing all requested frameworks, provide a brief synthesis:
- What patterns appear across multiple frameworks?
- Where do the frameworks reinforce each other?
- What is the single most critical insight?

## Asking Questions

When information is missing, ask focused questions. Group related questions together (max 3-5 per round). Examples of what to ask vs. what to research:

**Ask the user:**
- Internal process steps ("What are the 4-8 main steps in this process?")
- Stakeholder-specific knowledge ("Who are the key decision-makers?")
- Organizational constraints ("What's your budget/timeline reality?")
- Cultural context ("How does your org typically respond to change?")

**Research yourself:**
- Industry statistics and benchmarks
- Regulatory and policy context
- Demographic and market data
- Technology landscape and adoption rates
- Published case studies and comparisons
