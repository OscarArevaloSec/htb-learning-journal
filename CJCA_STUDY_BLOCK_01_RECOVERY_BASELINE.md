# CJCA Study Block 01 — Recovery Baseline

**Target date:** June 1, 2026  
**Purpose:** Establish your real current baseline before the June 23 CJCA sprint becomes wishful thinking. This block is not about feeling productive. It is about producing evidence that shows where you are strong, where you are weak, and whether the next three weeks should focus on enumeration, reporting, triage, or fundamentals.

## Operating Standard

For this block, you are not allowed to treat “I studied” as completion. A completed block must produce at least one filled evidence log, one short executive summary draft, and one technical finding or investigation note. If you do not create artifacts, the session does not count.

> **Blunt rule:** If you get stuck, document the stuck point. A documented failure is useful. An undocumented struggle is just lost time.

## Time Box

| Segment | Duration | Objective | Required Output |
|---|---:|---|---|
| Setup | 15 minutes | Prepare workspace, notes, screenshots folder, evidence log, and report template. | Workspace checklist completed. |
| Timed Enumeration | 75 minutes | Enumerate one target, lab, or scenario without walkthroughs. | Evidence entries E-001 through at least E-005. |
| Validation / Triage | 60 minutes | Validate one possible issue, path, or security-relevant observation. | One finding candidate or triage note. |
| Reporting | 45 minutes | Convert evidence into client-readable language. | One executive summary draft and one technical finding draft. |
| Review | 15 minutes | Score your weak areas honestly. | Baseline score table completed. |

## Before You Start

Create a folder named using this pattern:

```text
CJCA_Block_01_Recovery_Baseline_YYYY-MM-DD
```

Inside that folder, create the following structure:

```text
CJCA_Block_01_Recovery_Baseline_YYYY-MM-DD/
├── evidence-log.md
├── technical-finding.md
├── screenshots/
├── commands.txt
└── review.md
```

Copy the following templates into the folder before starting:

| Template | Use |
|---|---|
| `CJCA_Evidence_Log_Template.md` | Track every meaningful command, screenshot, observation, and interpretation. |
| `CJCA_Technical_Finding_Template.md` | Convert one validated issue or investigation result into report language. |
| `CJCA_Mock_Cycle_Report_Packet.md` | Use only if you extend this into a full 3–4 hour mock cycle. |

## Target Selection

Choose **one** practice target or scenario. Do not bounce between five resources. If you are using HTB Academy, choose a module section or lab that maps to CJCA-style fundamentals. If you are using a retired box or practice environment, choose something appropriate for junior-level enumeration, web/service validation, Linux or Windows fundamentals, or SOC-style triage.

| Acceptable Target Type | Good Choice | Bad Choice |
|---|---|---|
| Enumeration-focused target | A single host or module lab where you can identify exposed services and explain them. | A complex multi-host chain that turns into four hours of random rabbit holes. |
| Web fundamentals | A small web app where you can validate one issue and document impact. | A black-box app where you immediately need advanced exploit research. |
| Defensive triage | A small log, alert, or packet scenario where you explain what happened. | A giant dataset where you only skim and never write a conclusion. |

## Execution Rules

During the timed enumeration segment, record commands and observations as you go. Do not wait until the end. Screenshots without interpretation do not count as evidence.

| Rule | Reason |
|---|---|
| No walkthroughs during the first 75 minutes. | You need to know your real baseline, not your ability to follow hints. |
| Every meaningful result gets an evidence ID. | Your report quality depends on traceable evidence. |
| If a path fails, document why it failed. | Dead ends show methodology and prevent repeated mistakes. |
| Stop hands-on work when the timer ends. | CJCA readiness requires time control, not endless tinkering. |
| Reporting is mandatory. | The exam is not just technical discovery; it requires communication. |

## Required Evidence Log Entries

By the end of the enumeration and validation phases, your evidence log should include at least the following:

| Evidence Type | Minimum Standard |
|---|---|
| Scope / target confirmation | What you are testing and what you are not testing. |
| Service, application, or artifact inventory | What was discovered and why it matters. |
| Manual validation | One item you validated beyond simply running a tool. |
| Rejected path | One thing you tested that did not work, with your reasoning. |
| Finding candidate or triage conclusion | One item worth explaining in a report. |

## Baseline Scorecard

Score yourself honestly from **1 to 5**. A 5 means you can perform the skill independently under time pressure and explain it clearly. A 3 means you can do it with some friction. A 1 means this is currently a blocking weakness.

| Skill Area | Score 1–5 | Evidence From This Block | Fix Before Next Block |
|---|---:|---|---|
| Workspace setup and organization |  |  |  |
| Enumeration discipline |  |  |  |
| Manual validation |  |  |  |
| Evidence capture |  |  |  |
| Technical explanation |  |  |  |
| Executive summary writing |  |  |  |
| Time management |  |  |  |
| Knowing when to move on |  |  |  |

## Report Output Requirement

At the end of the block, write one executive summary paragraph and one technical note. They do not need to be perfect. They need to exist.

### Executive Summary Draft

Write three to five sentences for a non-technical reader. Explain what you reviewed, what you found, why it matters, and what should happen next.

### Technical Finding or Investigation Note

Use this structure:

| Section | Draft |
|---|---|
| Observation |  |
| Evidence IDs |  |
| Technical Explanation |  |
| Impact |  |
| Recommended Next Step |  |

## Pass / Fail Criteria

| Result | Meaning | Next Step |
|---|---|---|
| Pass | Evidence log, executive summary, and technical note are complete. | Continue to the next scheduled study block. |
| Partial Pass | Evidence exists, but reporting is weak or incomplete. | Repeat only the reporting section within 24 hours. |
| Fail | No useful artifact was produced. | Redo this block before moving forward. |

## After-Action Review

Write one paragraph answering each question.

| Question | Response |
|---|---|
| What slowed me down the most? |  |
| What did I understand better than expected? |  |
| Where did I rely on guessing instead of methodology? |  |
| What will I fix in the next block? |  |

## Final Instruction

When you finish, commit or save the artifacts. The goal is to build a visible trail of competence before June 23. If the trail is empty, you are not ready. If the trail is messy but improving, you are on the right path.
