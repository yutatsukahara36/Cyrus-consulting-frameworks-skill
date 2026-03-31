---
name: consulting-frameworks
description: Apply structured consulting and operations frameworks to analyze any business, operations, or systemic problem. Use this skill whenever the user wants to analyze a problem using frameworks like Root Cause Analysis (RCA/Fishbone), SIPOC, Bullseye, Triple Constraints, Tradeoff Analysis, or System Map. Also trigger when users say things like 'help me break down this problem', 'analyze this system', 'what's causing this issue', 'map this process', 'identify root causes', 'what are the tradeoffs', 'who are the stakeholders', 'what's broken in this system', or any request to systematically diagnose a business or operational challenge. Trigger even if users don't name a specific framework — if they describe a messy problem and want structured analysis, this skill applies.
---

# Consulting Frameworks Skill

This skill guides structured problem analysis using six proven consulting frameworks. The goal is to produce comprehensive, data-backed analysis that a user can then use to build visual deliverables (slides, diagrams, maps).

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

### Phase 2: Framework Selection

Based on the problem, recommend which frameworks to apply and in what order. Here is the recommended sequencing:

**To determine SCOPE, use:**
- Triple Constraints (who/what is involved)
- Tradeoff Analysis (what tensions exist)

**To determine PAIN of the current system, use:**
- RCA / Fishbone (why is it broken)
- Bullseye (where does actual diverge from desired)
- SIPOC (what does the process chain look like)

**To understand SYSTEMIC DYNAMICS, use:**
- System Map (how do forces interact across the ecosystem)

Ask the user which frameworks they want, or recommend a subset based on their problem. If they want all six, sequence them in the order above.

### Phase 3: Framework Execution

For each framework, read the corresponding reference file before generating output:
- RCA → `rca.md`
- SIPOC → `sipoc.md`
- Bullseye → `bullseye.md`
- Triple Constraints → `triple-constraints.md`
- Tradeoff → `tradeoff.md`
- System Map → `system-map.md`

Each reference file contains the framework structure, what to include, how to organize it, and what questions to ask the user if information is missing.

### Phase 4: Output Format

For each framework, produce:

1. **Structured analysis** in clearly organized sections with headers matching the framework's components
2. **Key Insight** — a synthesis paragraph at the end of each framework explaining the "so what"
3. **Data citations** — every statistic must include its source
4. **Sufficient detail** for the user to build their own visual deliverable (slide, diagram, poster) from the output

Do NOT generate visualizations. The output is comprehensive written analysis that serves as the content layer for the user's own visual work.

### Phase 5: Cross-Framework Synthesis

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
