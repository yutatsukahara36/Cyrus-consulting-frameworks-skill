# SIPOC Framework

## Purpose
Map the full process chain from Suppliers through to Customers. SIPOC reveals who feeds the system, what inputs are required, how the process works, what it produces, and who receives the output. It exposes where handoffs break and where supplier quality affects outcomes.

## Structure

### Name Your SIPOC
Every SIPOC should have a descriptive name that captures the specific process being mapped (e.g., "SIPOC: Overwhelmed Rural Infrastructure" or "SIPOC: Customer Onboarding Pipeline"). This name becomes a reference anchor when working across multiple frameworks.

### Work in This Order: Output → Process → then fill in the rest
Starting with Output grounds the analysis in what the system actually produces (good or bad), then traces backward through the process that creates it.

### Components

**Suppliers**
- People or entities who supply anything — physical and non-physical
- Include organizations, departments, roles, external vendors
- Government agencies, regulatory bodies if relevant
- Add supporting data (e.g., "Rural County Hospitals — more than 1/5 of TX counties have ≤1 PCP")

**Inputs**
- Things that feed into the process
- Capacity constraints (ICU beds, staff counts, equipment)
- Staffing and skill levels
- Infrastructure (broadband, transport, facilities)
- Information systems and data
- Funding and resources
- Add specific constraints with data

**Process**
- The main 4-8 steps of what actually happens
- Write as a narrative sequence (Step 1, Step 2, etc.)
- Use "verb then noun" format for each step
- Focus on what actually happens in practice, not what's supposed to happen
- Include where breakdowns and delays occur within the process
- The "belly of the beast" — the people who do the work daily — are the best source for process steps. Ask the user if you don't have this info.

**Outputs**
- What the process creates — products, services, experiences
- Include both intended and unintended outputs
- Negative outputs matter: "Delayed/denied healthcare" is a valid output
- Systemic effects: cascade failures, burden shifts to other parts of the system
- Data on output quality and failure rates

**Customers**
- Who receives the output — both direct and indirect
- Segment by type (e.g., "Rural Infected Patients," "Healthcare Workers," "Patients Seeking Routine Care")
- For each customer segment, note the specific impact they experience
- Include internal customers (staff, departments) not just external end-users

### Key Insights Section
After mapping all five components, write a synthesis paragraph explaining:
- Where the chain is weakest
- Which supplier-input gaps most directly cause output failures
- Where the same entity appears as both Supplier and Customer (this signals process mess)

## Output Format

```
# SIPOC: [Descriptive Name]

## Suppliers
**[Supplier Category 1]**
- [Specific supplier with data]

**[Supplier Category 2]**
- [Specific supplier with data]

## Inputs
**[Input Category 1]**
- [Specific constraint/resource with data]

## Process
1. [Step 1 — what happens, where it breaks]
2. [Step 2 — what happens, where it breaks]
... (4-8 steps)

## Outputs
**[Output 1]**
- [Description with data on frequency/severity]

## Customers
**[Customer Segment 1]**
- [Specific impact they experience]

## Key Insights
[Synthesis paragraph]
```

## Critical Rules
- If someone is both Supplier AND Customer, flag it — this creates process loops and confusion
- Don't over-detail or under-detail. Keep it specific enough to be actionable but not so granular it loses the forest for the trees
- SIPOC components are intertwined — one bad supplier input cascades all the way to customer experience
- Process steps should reflect reality, not the idealized version

## Questions to Ask the User
- "What are the main 4-8 steps in this process as it actually works today?"
- "Who supplies the key inputs? Are there bottlenecks in supply?"
- "Who are the different types of end-users/customers affected?"
- "Are any stakeholders serving dual roles as both supplier and customer?"
