# Consulting Frameworks Skill for Claude AI

A structured problem-analysis skill for Claude that applies six proven consulting frameworks to any business, operations, or systemic challenge. Built to turn messy, complex problems into clear, data-backed analysis.

---

## Credit & Origin

**These frameworks were taught by [Cyrus Aram](https://www.linkedin.com/in/cyrusaram/), Chief Executive Officer at [Unleashing Leaders, Inc.](https://unleashingleaders.com/) and Professor of MGT 120 (Project Management & Consulting) at UC Davis.**

Professor Aram's course is one of the most impactful business classes offered at UC Davis — a hands-on, practitioner-driven approach to consulting and systems thinking that bridges academic rigor with real-world application. The frameworks in this skill are direct translations of his curriculum into a repeatable AI workflow.

If you're a UC Davis student, take MGT 120. If you're a professional looking for consulting training, check out Unleashing Leaders.

**This skill was created by Yuta Tsukahara as a tool to make Professor Aram's frameworks accessible and repeatable through AI.**

---

## What's Included

Six consulting frameworks, each with its own reference file:

| Framework | What It Does | When to Use |
|---|---|---|
| **Root Cause Analysis (RCA)** | Drills into the deep, systemic causes of a problem across multiple domains | You know something is broken but don't know *why* |
| **SIPOC** | Maps the full process chain: Suppliers → Inputs → Process → Outputs → Customers | You need to understand how a process works end-to-end |
| **Bullseye** | Compares Actual vs. Desired state across 7 organizational layers (Intent → Culture) | You want to see where structural misalignment exists |
| **Triple Constraints** | Categorizes all factors into People (60%), Process (20%), Technology (20%) | You need to scope a problem and identify all stakeholders |
| **Tradeoff Analysis** | Maps the Speed vs. Cost vs. Quality triangle | You need to name what the system is sacrificing |
| **System Map** | Maps Drivers → Mainstay → Enablers with interconnections | You need to understand how systemic forces interact |

---

## How to Use

### As a Claude Skill
1. Download this repository
2. Add the `consulting-frameworks` folder to your Claude skills directory
3. When you prompt Claude with any business or operational problem, the skill will trigger and guide you through structured analysis

### As a Standalone Reference
Even without Claude, the reference files in `/references` serve as clear, step-by-step guides for applying each framework manually. Each file includes:
- Framework structure and components
- Output format template
- Critical rules and common mistakes to avoid
- Questions to ask when information is missing

---

## Workflow

The skill follows a specific sequence designed by Professor Aram:

**1. Problem Statement First** — Always. No frameworks until the problem is clearly defined.

**2. Scope the Problem**
- Triple Constraints → who and what is involved
- Tradeoff Analysis → what tensions exist

**3. Identify the Pain**
- RCA → why is it broken
- Bullseye → where does actual diverge from desired
- SIPOC → what does the process chain look like

**4. Understand Systemic Dynamics**
- System Map → how do forces interact across the ecosystem

**5. Cross-Framework Synthesis** → patterns, reinforcements, and the single most critical insight

---

## Best Practices

- **Don't skip the problem statement.** Jumping straight into frameworks without a clear problem statement is the most common mistake. Define the problem first.
- **You don't need all six.** Pick the frameworks that fit your problem. A simple process issue might only need SIPOC and RCA. A complex systemic challenge might need all six.
- **Follow the sequence.** Scope → Pain → Systemic. This order builds understanding layer by layer.
- **Data over opinions.** Every claim should be backed by data. If you don't have it, go find it.
- **Stay in the current state.** These frameworks analyze what IS — not what should be (except Bullseye, which explicitly contrasts Actual vs. Desired). Don't jump to solutions.
- **People first, technology last.** Per Professor Aram's teaching: People account for 60% of any system's constraints. Technology is 20% and gets replaced every 6 months. Never lead with a tech solution.
- **The customer perspective is the test.** After completing any framework, ask: "Does this reflect the customer's actual experience?" If not, you're missing something.

---

## File Structure

```
consulting-frameworks/
├── SKILL.md                              # Main skill file (orchestration + workflow)
└── references/
    ├── rca.md                            # Root Cause Analysis
    ├── sipoc.md                          # SIPOC Process Mapping
    ├── bullseye.md                       # Bullseye Actual vs. Desired
    ├── triple-constraints.md             # People / Process / Technology
    ├── tradeoff.md                       # Speed / Cost / Quality Triangle
    └── system-map.md                     # Drivers / Mainstay / Enablers
```

---

## License

This is an open educational resource. Use it, share it, build on it. If you do, credit Professor Cyrus Aram and Unleashing Leaders, Inc.

---

## Acknowledgments

**Cyrus Aram** — For building a consulting curriculum that actually changes how students think about problems. These frameworks aren't theoretical exercises — they're tools that work in the real world, taught by someone who uses them in the real world.

**UC Davis, MGT 120** — Where these frameworks were learned, practiced, and pressure-tested.
