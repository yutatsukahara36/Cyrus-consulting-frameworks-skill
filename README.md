# Consulting Frameworks Skill for Claude AI

A structured problem-analysis skill for Claude that applies seven proven consulting frameworks to any business, operations, or systemic challenge. Built to turn messy, complex problems into clear, data-backed analysis.

---

## Credit & Origin

**These frameworks were taught by [Cyrus Aram](https://www.linkedin.com/in/cyrusaram/), Chief Executive Officer at [Unleashing Leaders, Inc.](https://unleashingleaders.com/) and Professor of MGT 120 (Project Management & Consulting) at UC Davis.**

Professor Aram's course is one of the most impactful business classes offered at UC Davis — a hands-on, practitioner-driven approach to consulting and systems thinking that bridges academic rigor with real-world application. The frameworks in this skill are direct translations of his curriculum into a repeatable AI workflow.

If you're a UC Davis student, take MGT 120. If you're a professional looking for consulting training, check out Unleashing Leaders.

**This skill was created by Yuta Tsukahara as a tool to make Professor Aram's frameworks accessible and repeatable through AI.**

---

## What's Included

Seven consulting frameworks, each with its own reference file:

### Mandatory Entry Frameworks (always run)

| Framework | What It Does | When to Use |
|---|---|---|
| **Strategy** | Analyzes current strategic positioning: unique position, tailored activities, trade-offs, improvement continuity | Always — establishes strategic context before any deeper analysis |
| **Triple Constraints** | Categorizes all factors into People (60%), Process (20%), Technology (20%) | Always — scopes the problem and identifies all stakeholders |
| **Tradeoff Analysis** | Maps the Speed vs. Cost vs. Quality triangle | Always — names what the system is sacrificing |

### Optional Deep-Dive Frameworks (user selects after entry frameworks)

| Framework | What It Does | When to Use |
|---|---|---|
| **Root Cause Analysis (RCA)** | Drills into the deep, systemic causes of a problem across multiple domains | You know something is broken but don't know *why* |
| **SIPOC** | Maps the full process chain: Suppliers → Inputs → Process → Outputs → Customers | You need to understand how a process works end-to-end |
| **Bullseye** | Compares Actual vs. Desired state across 7 organizational layers (Intent → Culture) | You want to see where structural misalignment exists |
| **System Map** | Maps Drivers → Mainstay → Enablers with interconnections | You need to understand how systemic forces interact |

---

## How to Use

### As a Claude Skill
1. Download this repository
2. Add the `consulting-frameworks` folder to your Claude skills directory
3. When you prompt Claude with any business or operational problem, the skill will trigger and guide you through structured analysis

### As a Standalone Reference
Even without Claude, the `.md` reference files serve as clear, step-by-step guides for applying each framework manually. Each file includes:
- Framework structure and components
- Output format template
- Critical rules and common mistakes to avoid
- Questions to ask when information is missing

---

## Workflow

The skill follows a specific sequence designed by Professor Aram:

**1. Problem Statement First** — Always. No frameworks until the problem is clearly defined.

**2. Mandatory Entry Frameworks (always run, in order)**
- Strategy → current strategic positioning and trade-offs
- Triple Constraints → who and what is involved (People 60%, Process 20%, Tech 20%)
- Tradeoff Analysis → what tensions exist (Speed vs. Cost vs. Quality)

**3. Deep-Dive Framework Selection**
After the entry frameworks, Claude recommends which deep-dives fit your problem. You pick which ones to run:
- RCA → why is it broken
- Bullseye → where does actual diverge from desired
- SIPOC → what does the process chain look like
- System Map → how do forces interact across the ecosystem

**4. Cross-Framework Synthesis** → patterns, reinforcements, and the single most critical insight

---

## Best Practices

- **Don't skip the problem statement.** Jumping straight into frameworks without a clear problem statement is the most common mistake. Define the problem first.
- **The first three are non-negotiable.** Strategy, Triple Constraints, and Tradeoff Analysis always run. They set the foundation.
- **Pick the deep-dives that fit.** Not every problem needs all four. A simple process issue might only need SIPOC. A complex systemic challenge might need all four.
- **Data over opinions.** Every claim should be backed by data. If you don't have it, go find it.
- **Stay in the current state.** These frameworks analyze what IS — not what should be (except Bullseye, which explicitly contrasts Actual vs. Desired). Don't jump to solutions.
- **People first, technology last.** Per Professor Aram's teaching: People account for 60% of any system's constraints. Technology is 20% and gets replaced every 6 months. Never lead with a tech solution.
- **The customer perspective is the test.** After completing any framework, ask: "Does this reflect the customer's actual experience?" If not, you're missing something.

---

## File Structure

```
Cyrus-consulting-frameworks-skill/
├── README.md                     # This file
├── SKILL.md                      # Main skill file (orchestration + workflow)
├── strategy.md                   # Strategy Analysis (mandatory)
├── triple-constraints.md         # People / Process / Technology (mandatory)
├── tradeoff.md                   # Speed / Cost / Quality Triangle (mandatory)
├── rca.md                        # Root Cause Analysis (optional deep-dive)
├── sipoc.md                      # SIPOC Process Mapping (optional deep-dive)
├── bullseye.md                   # Bullseye Actual vs. Desired (optional deep-dive)
└── system-map.md                 # Drivers / Mainstay / Enablers (optional deep-dive)
```

---

## License

This is an open educational resource. Use it, share it, build on it. If you do, credit Professor Cyrus Aram and Unleashing Leaders, Inc.

---

## Acknowledgments

**Cyrus Aram** — For building a consulting curriculum that actually changes how students think about problems. These frameworks aren't theoretical exercises — they're tools that work in the real world, taught by someone who uses them in the real world.

**UC Davis, MGT 120** — Where these frameworks were learned, practiced, and pressure-tested.
