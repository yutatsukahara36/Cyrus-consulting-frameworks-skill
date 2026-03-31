# Tradeoff Analysis

## Purpose
Identify the fundamental tensions in a system by mapping the classic triangle: you cannot maximize all three of Speed, Cost, and Quality simultaneously. This framework forces honest acknowledgment of what is being sacrificed and why.

## The Three Corners

### 1. Quality (Consistent, High-Quality Output)
- Durability, reliability, features, consistency
- In services: accuracy, expertise, thoroughness
- In healthcare: quality of care, outcomes, patient safety
- In operations: defect rates, customer satisfaction, standards compliance

### 2. Speed (Rapid Deployment / Turnaround)
- Fast turnaround time
- Emergency response capability
- Time-to-market or time-to-delivery
- Scalability under time pressure

### 3. Cost (Budget-Conscious Efficiency)
- Low cost, minimal resources needed
- Budget scalability
- Operational efficiency
- Resource conservation

## Structure

### Step 1: Identify the Three Corners for This Problem
Translate the generic Speed/Cost/Quality into domain-specific language. For example:
- Healthcare: "Consistent High Quality Care" / "Rapid Deployment Capacity" / "Budget-Conscious Scalability"
- Product dev: "Feature Completeness" / "Time to Market" / "Development Cost"
- Operations: "Service Quality" / "Response Speed" / "Resource Efficiency"

### Step 2: Map Current Tradeoffs
For each pair of corners, describe what happens when you prioritize one over the other:
- Speed + Cost (sacrifice Quality): Describe the scenario and real-world evidence
- Speed + Quality (sacrifice Cost): Describe the scenario and real-world evidence
- Cost + Quality (sacrifice Speed): Describe the scenario and real-world evidence

### Step 3: Identify Which Tradeoff the System Currently Makes
Based on evidence, which corner is currently being sacrificed? This is the key insight.

### Step 4: Key Insight
Write a synthesis explaining: the system forces a choice between X, Y, and Z, and the current configuration sacrifices [corner] — resulting in [specific consequences].

## Output Format

```
# Tradeoff Analysis: [Problem Name]

## The Three Corners
1. **[Domain-specific Quality label]** — [What this means in context]
2. **[Domain-specific Speed label]** — [What this means in context]
3. **[Domain-specific Cost label]** — [What this means in context]

## Current Tradeoffs

### [Tradeoff Scenario 1: e.g., "Emergency Healthcare Dispatch"]
Prioritizes: [Speed + Cost]
Sacrifices: [Quality]
Evidence: [Specific description with data — e.g., "Emergency responses deploy quickly but rely on temporary setups, undertrained personnel, and mobile units, leading to inconsistent quality of care"]

### [Tradeoff Scenario 2: e.g., "Resource Rationing"]
Prioritizes: [Cost + partial Quality]
Sacrifices: [Speed / Access]
Evidence: [Specific description with data]

### [Tradeoff Scenario 3: e.g., "Service Scarcity"]
Prioritizes: [Cost]
Sacrifices: [Quality + Speed]
Evidence: [Specific description with data]

## Key Insight
[Synthesis paragraph: The system forces a choice between [the three corners], with [specific corner] consistently being sacrificed. This results in [concrete consequences with data].]
```

## Critical Rules
- It is IMPOSSIBLE to maximize all three. If someone claims otherwise, they are not being honest about what's being sacrificed.
- Name the tradeoffs clearly — don't hide behind vague language
- Each tradeoff scenario should have real-world evidence or data
- The Key Insight should make clear what the system is currently giving up and what the consequences are

## Questions to Ask the User
- "If you had to pick two out of speed, cost, and quality — which two does the current system prioritize?"
- "What's being sacrificed as a result? What are the visible consequences?"
- "Are there specific scenarios where the tradeoff becomes most apparent?"
