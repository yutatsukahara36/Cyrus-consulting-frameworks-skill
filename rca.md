# Root Cause Analysis (RCA) / Fishbone

## Purpose
Identify the deep, systemic causes of a problem by drilling through domains and sub-causes. RCA is the foundation framework — it exposes WHY the system is broken.

## Structure

### Step 1: Start with the Problem Statement
Place the confirmed problem statement at the head of the fishbone. This anchors everything.

### Step 2: Identify Domains (the "bones")
Select 3-6 domains relevant to the problem. Common domains include:

- **People & Stakeholders** — Who is affected, who contributes to the problem
- **Process** — How work gets done, where breakdowns occur
- **Technology** — Systems, tools, digital infrastructure gaps
- **Policy & Business Rules** — Regulations, internal rules, external mandates
- **Workflow & Procedures** — Specific operational steps that fail
- **Culture** — Mindsets, incentives, organizational behavior

The domain selection requires judgment — not every problem needs all domains. Choose based on where the pain concentrates.

### Step 3: Outline Sub-Causes per Domain
For each domain, identify 2-4 specific sub-causes. Each sub-cause must:
- Be specific and observable (not vague like "lack of communication")
- Include supporting data with source citations
- Avoid solution language (say "24-day wait times" not "need faster scheduling")

### Step 4: Apply Five Whys
For each major sub-cause, drill deeper by asking "why" in different open-ended ways. Go at least 3 levels deep on the most critical sub-causes.

### Step 5: Add Data
Every sub-cause should have at least one supporting data point. Use web search for industry data, published research, government statistics.

### Step 6: Generate Key Insights
Synthesize across all domains. What patterns emerge? Where do multiple domains converge on the same root issue?

## Output Format

```
# Root Cause Analysis: [Problem Name]

## Problem Statement
[The confirmed problem statement]

## Domain 1: [Name]
### Sub-cause 1.1: [Specific issue]
- Evidence: [Statistic + source]
- Why deeper: [Next level cause]
  - Why deeper: [Next level]

### Sub-cause 1.2: [Specific issue]
- Evidence: [Statistic + source]

[Repeat for each domain]

## Key Insights
[2-3 paragraph synthesis of what the RCA reveals about the root structural issues]
```

## Words to AVOID in sub-causes
- "Lack of marketing"
- "Lack of communication"
- "No awareness"
- "Regulations" (too vague — specify WHICH regulation and its specific effect)

## Critical Rules
- People closest to the problem should inform the RCA — ask the user about frontline perspectives
- Stay in the current state pain. No hypotheticals, no solutions.
- Always tie back to customer experience impact
- When sub-causes overlap across domains, note the connection — this reveals systemic issues
- Attack insights, not people's competence

## Questions to Ask the User (if info is missing)
- "Who are the stakeholders closest to this problem day-to-day?"
- "What are the most common complaints from customers/end-users?"
- "Are there specific policies or rules that constrain how this process works?"
- "Has anyone attempted to fix this before? What happened?"
