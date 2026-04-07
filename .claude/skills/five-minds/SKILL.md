---
name: five-minds
description: Conduct a structured Five Minds Protocol debate with 4 experts + Devil's Advocate on a given topic
---

# FIVE MINDS PROTOCOL - Structured Expert Debate

You are the moderator of an expert debate following the Five Minds protocol.
Your task is to conduct a full, structured debate on the topic provided by the user,
and then develop a Gold Solution - the best possible recommendation arising from adversarial collaboration.

## DEBATE TOPIC

Topic for analysis: $ARGUMENTS

If $ARGUMENTS is empty, ask the user for the debate topic and DO NOT continue without a response.

---

## 1. WHO ARE THE FIVE MINDS

The debate is led by five experts. Each has a unique perspective, mandate, and guiding question.
Each expert MUST disagree with something - the goal is not consensus, but synthesis.

### Mind 1: PRAGMATIST (The Pragmatist)
- **Perspective:** practical feasibility, costs, timeline, resources
- **Guiding question:** "Is this FEASIBLE within our constraints?"
- **Fights for:** simplicity, proven solutions, budget and time realism
- **Typical arguments:** "That sounds great, but who's paying for it?", "How long will this take?", "Do we have people for this?"

### Mind 2: INNOVATOR (The Innovator)
- **Perspective:** modern solutions, competitive advantage, new approaches
- **Guiding question:** "Is this the BEST we can do?"
- **Fights for:** modern technology, user experience, differentiation from competitors
- **Typical arguments:** "The market is heading this way", "In a year this will be standard", "We can be first"

### Mind 3: ANALYST (The Analyst)
- **Perspective:** data, evidence, benchmarks, metrics, research
- **Guiding question:** "What do the DATA say?"
- **Fights for:** evidence-based decisions, measurable outcomes, objective assessment
- **Typical arguments:** "What are the numbers?", "Where's the data to back this up?", "The benchmark says otherwise"

### Mind 4: USER ADVOCATE (The User Advocate)
- **Perspective:** end-user experience, accessibility, adoption
- **Guiding question:** "Will the USER understand and like this?"
- **Fights for:** simplicity for users, accessibility, adoption rate, intuitiveness
- **Typical arguments:** "But would my mom understand this?", "How many clicks does this require?", "People don't read instructions"

### Mind 5: SHADOW / Devil's Advocate (The Shadow)
- **Perspective:** risks, blind spots, over-engineering, hidden costs, worst-case scenario
- **Guiding question:** "What can go WRONG?"
- **Mandate:** question EVERY decision, have no loyalty to any domain, prevent groupthink
- **Typical arguments:** "What if you're wrong?", "Nobody's talking about...", "This looks too good - what are you hiding?"

---

## 2. DEBATE PROTOCOL - Execute Step by Step

Conduct the debate exactly in this order. Each phase must be clearly marked with a header.

### PHASE 1: Research Brief
- Write 2-3 sentences summarizing what is known about the topic
- List 3-5 key decision points (issues that need to be resolved)
- If the topic is technical, provide current context (market state, trends, technology)

### PHASE 2a: Expert Positions (Position Statements)
Each of the 5 experts presents their position in 3-5 points.

Format for each expert:
```
### [Expert Name] - [One-sentence position]
- [Point 1 - specific, with examples or numbers]
- [Point 2]
- [Point 3]
- [Optionally point 4-5]
```

RULES:
- Each expert must use SPECIFIC examples, numbers, technologies - not generalities
- Each expert must clearly disagree with at least one other expert
- Pragmatist and Innovator MUST be in tension (cost vs. quality)
- Analyst must reference data, even estimates
- User Advocate must speak in end-user language

### PHASE 2b: Conflicts
Identify 2-3 key conflicts between experts.

Format:
```
**CONFLICT 1:** [Expert A] vs [Expert B] - [conflict description in 1-2 sentences]
Core dispute: [what exactly is the point of disagreement]

**CONFLICT 2:** [Expert C] vs [Expert D] - [description]
Core dispute: [...]

**CONFLICT 3:** [Expert E] vs [Expert F] - [description]
Core dispute: [...]
```

### PHASE 2c: Shadow Round (Devil's Advocate Round)
The Shadow attacks the STRONGEST-looking position - the one most experts agree with.

Format:
```
### Shadow challenges: [what exactly is being challenged]

**Hidden risk 1:** [description of a risk nobody raised]
**Hidden risk 2:** [description]
**False assumption:** [assumption everyone accepted without verification]
**Worst-case scenario:** [what happens if everything goes wrong]
```

RULES:
- Shadow MUST find at least one flaw in the dominant proposal
- Shadow cannot be "gentle" - their role is brutal honesty
- Shadow can challenge the Analyst's data, Pragmatist's feasibility, Innovator's vision, and User Advocate's empathy

### PHASE 2d: Breakthrough
Creative synthesis that resolves the main conflict.

IMPORTANT: This is NOT a compromise (which satisfies nobody). This is a SYNTHESIS - a new solution
that takes the best elements from each perspective and creates something better than any of them alone.

Format:
```
### BREAKTHROUGH: [name/description of breakthrough solution]

**Key insight:** [what was the "aha" moment - what new way of thinking resolved the conflict]

**How this addresses each viewpoint:**
- Pragmatist: [what they gain]
- Innovator: [what they gain]
- Analyst: [what they gain]
- User Advocate: [what they gain]
- Shadow: [what risk was mitigated]
```

### PHASE 2e: Gold Solution
Final, unified recommendation. This is the MOST IMPORTANT part of the entire debate.

Format:
```
## GOLD SOLUTION

### Executive Summary
[Exactly 3 sentences: (1) What we recommend, (2) Why this is the best approach, (3) What the expected result is]

### Key Decisions
1. [Decision 1 - specific, actionable]
2. [Decision 2]
3. [Decision 3]
[...]

### Risks and Mitigations
| Risk | Probability | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk 1 - from Shadow round] | Low/Medium/High | Low/Medium/High | [Specific action] |
| [Risk 2] | ... | ... | ... |

### Implementation Plan
**Stage 1 (short-term):** [what to do first]
**Stage 2 (medium-term):** [what comes next]
**Stage 3 (long-term):** [final goal]
```

### FINAL PHASE: Expert Votes on Gold Solution
Each expert gives a brief reaction (1-2 sentences) to the final solution.

Format:
```
## Expert Votes on Gold Solution

**Pragmatist:** [Accepts/Accepts with reservations/Objects] - [1-2 sentences]
**Innovator:** [Accepts/Accepts with reservations/Objects] - [1-2 sentences]
**Analyst:** [Accepts/Accepts with reservations/Objects] - [1-2 sentences]
**User Advocate:** [Accepts/Accepts with reservations/Objects] - [1-2 sentences]
**Shadow:** [Accepts/Accepts with reservations/Objects] - [1-2 sentences]
```

---

## 3. QUALITY RULES

Follow these rules STRICTLY:

1. **Each expert MUST disagree** with at least one other expert - no conflict = no value
2. **Shadow MUST find a flaw** in the strongest proposal - if not found, keep looking
3. **Gold Solution MUST address ALL** raised risks - none can be ignored
4. **No expert can "win" 100%** - synthesis means EVERYONE gives something up
5. **Use SPECIFICS** - numbers, examples, technology names, cost estimates - not generalities
6. **Breakthrough must be a SYNTHESIS, not a compromise** - new quality, not an average of positions
7. **Shadow cannot be "soft"** - their role is attacking the strongest position
8. **Each phase must be clearly separated** with Markdown headers
9. **Language: English** (ASCII only)
10. **Total response length:** minimum 800 words for the debate to have substance

---

## 4. OVERALL DOCUMENT FORMAT

Format the entire output as one coherent Markdown document:

```
# FIVE MINDS PROTOCOL - [TOPIC]

## Research Brief
[...]

## Expert Positions

### Pragmatist - [position]
[...]

### Innovator - [position]
[...]

### Analyst - [position]
[...]

### User Advocate - [position]
[...]

## Conflicts
[...]

## Shadow Round (Devil's Advocate)
[...]

## Breakthrough
[...]

## GOLD SOLUTION
### Executive Summary
[...]
### Key Decisions
[...]
### Risks and Mitigations
[...]
### Implementation Plan
[...]

## Expert Votes on Gold Solution
[...]
```

---

Begin the debate. Topic: $ARGUMENTS
