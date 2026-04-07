<!-- REFERENCE ONLY - The authoritative format is embedded in SKILL.md.
     This file serves as documentation/reference for people browsing the skill. -->

# MANIFEST - HITL Pipeline

## Meta
- **Topic:** [TOPIC]
- **Start:** [TIMESTAMP]
- **Status:** In progress | Phase 1/6
- **Main model:** [opus/sonnet]
- **Subagent models:** [sonnet/haiku]

---

## Phase 1: Strategy

### Topic Analysis
[2-3 sentence description of the problem/task]

### Key Research Questions
1. [Question 1]
2. [Question 2]
3. [Question 3]

### Scope
- **IN:** [what is in scope]
- **OUT:** [what is out of scope]

### Decomposition
| Subtask | Type | Priority | Complexity |
|---------|------|----------|------------|
| [Subtask 1] | Research | High | M |
| [Subtask 2] | Build | Medium | L |

---

## Gate 1: Strategy -> Research
- **Selected option:** [A/B/C - name]
- **Rationale:** [1-2 sentences]
- **Gate file:** `gates/GATE_1_strategy_research.md`

---

## Phase 2: Research

### Subagents Launched
| Agent | Direction | Status | Key Result |
|-------|-----------|--------|------------|
| Research Tech | [topic] | Completed | [1 sentence] |
| Research UX | [topic] | Completed | [1 sentence] |
| Research Community | [topic] | Completed | [1 sentence] |

### Results Synthesis
[5-10 sentence summary: what aligns, what differs, what gaps exist]

### Key Facts
- [Fact 1 - with source]
- [Fact 2]
- [Fact 3]

---

## Phase 3: Five Minds Debate

### Gold Solution
[3-5 sentence summary of Gold Solution from debate]

### Key Decisions from Debate
1. [Decision 1]
2. [Decision 2]
3. [Decision 3]

### Risks Identified by Shadow
- [Risk 1 + mitigation]
- [Risk 2 + mitigation]

---

## Gate 2: Debate -> Build
- **Selected option:** [A/B/C - name]
- **Rationale:** [1-2 sentences]
- **Gate file:** `gates/GATE_2_debate_build.md`

---

## Phase 4: Build

### What Was Built
[Implementation description]

### Files Created/Modified
| File | Action | Description |
|------|--------|-------------|
| [path] | Created | [what it does] |

### Technical Decisions
- [Decision 1 - why]
- [Decision 2 - why]

---

## Gate 3: Build -> QA
- **Selected option:** [A/B/C - name]
- **Rationale:** [1-2 sentences]
- **Gate file:** `gates/GATE_3_build_qa.md`

---

## Phase 5: QA

### QA Results
| Category | Issues | Critical | Fixed |
|----------|--------|----------|-------|
| Code Review | [N] | [M] | [K] |
| Security | [N] | [M] | [K] |
| Performance | [N] | [M] | [K] |

### Critical Findings
- [Issue 1 - status: fixed/open]

---

## Summary

### Final Result
[3-5 sentence summary of what was achieved]

### Key Decisions
1. Gate 1: [what was chosen and why]
2. Gate 2: [what was chosen and why]
3. Gate 3: [what was chosen and why]

### Recommendations for Future
- [Recommendation 1]
- [Recommendation 2]

### Metrics
- **Duration:** [from start to end]
- **Subagents launched:** [N]
- **Phases completed:** 6/6
- **Decision gates:** 3/3

---

## Decision Log

| Gate | Option | Deliberation | Deep dive? | Timestamp |
|------|--------|-------------|------------|-----------|
| 1: Strategy->Research | [A/B/C] | [quick/deep] | [Yes/No] | [timestamp] |
| 2: Debate->Build | [A/B/C] | [quick/deep] | [Yes/No] | [timestamp] |
| 3: Build->QA | [A/B/C] | [quick/deep] | [Yes/No] | [timestamp] |
