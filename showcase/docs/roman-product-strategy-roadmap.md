# Roman Product Strategy Roadmap

Date: March 12, 2026

## Purpose

This document prioritizes the next product features across Roman's public GitHub projects based on three goals:

- strengthen internship portfolio value
- increase product depth and realism
- create features that are easy to explain in interviews

The recommendations are based on the current public state of these repositories:

- `SQL-playground`
- `jessica-career-os`
- `roman-command-center`
- `Physics-Study-Bot`

## Executive Summary

If the goal is maximum portfolio payoff, the best next flagship feature is:

**SQL Playground: Guided Challenge Mode**

Why:

- it turns a tool into a real learning product
- it demonstrates backend, frontend, data design, and product thinking together
- it is easy for recruiters to understand quickly

If the goal is strongest real-world workflow story, the best next flagship feature is:

**Jessica Career OS: Follow-Up Automation + Workflow Layer**

Why:

- it makes the product feel operational, not just informational
- it shows process design, job-state management, and user-value depth
- it is a strong example of business workflow software

If the goal is fastest improvement with low implementation risk, the best next move is:

**Roman Command Center: Weekly Review**

Why:

- it upgrades the product from tracking to decision support
- it adds visible value without requiring a major architectural rewrite
- it is strong evidence of analytics thinking

## Priority Matrix

| Feature | Repo | Effort | Portfolio Value | Why It Matters |
|---|---|---:|---:|---|
| Guided challenge mode | SQL Playground | Medium-High | Very High | Converts a sandbox into a structured learning product |
| Follow-up automation | Jessica Career OS | Medium | Very High | Makes the workflow feel complete and business-relevant |
| Weekly review dashboard | Roman Command Center | Medium | High | Turns raw logs into insights and planning |
| Shareable query links + history | SQL Playground | Medium | High | Improves usability and collaboration story |
| Recruiter/contact CRM | Jessica Career OS | Medium | High | Expands the app into a fuller operating system |
| CSV export/import | Roman Command Center | Low | Medium-High | Practical feature with strong product credibility |
| Adaptive study loop | Physics Study Bot | Medium-High | High | Turns the repo from concept into a real educational product |

## Repo-by-Repo Recommendations

### 1. SQL Playground

#### Best Feature: Guided Challenge Mode

Add structured SQL exercises with:

- prompt text
- starter schema or dataset context
- expected result checks
- hints
- completion tracking

What this proves to recruiters:

- you can build product layers on top of a data engine
- you understand education-oriented UX
- you can design constrained execution and validation systems

Why this is high leverage:

- the current app already has query execution, schema browsing, and visualization
- the missing piece is progression
- progression creates a stronger product story than utility alone

Expected implementation difficulty:

- medium-high
- requires challenge data model, validation logic, and learning UX

Secondary feature: Shareable Query Links + Query History

Add:

- recent query history
- restorable sessions
- URL-based sharing for query state

What this proves:

- usability thinking
- state management discipline
- collaboration-friendly product design

Best reason to build it:

- it makes the playground feel real for repeated use

### 2. Jessica Career OS

#### Best Feature: Follow-Up Automation

Add a workflow layer that:

- creates follow-up reminders automatically after submission
- pre-generates follow-up outreach text
- flags stale applications
- suggests next actions by stage

What this proves to recruiters:

- you can model a real business workflow
- you can translate user pain into automation
- you understand operational software, not just CRUD screens

Why this is high leverage:

- the current product already covers discovery, scoring, packet generation, and tracking
- the biggest missing piece is what happens after applying
- this closes the loop

Expected implementation difficulty:

- medium
- mostly workflow logic, reminders, and UI state extensions

Secondary feature: Recruiter/Contact CRM

Add:

- recruiter and hiring manager contacts
- outreach history
- contact-to-job linking
- response logging

What this proves:

- stronger relational modeling
- deeper business app design
- better system completeness

Best reason to build it:

- it upgrades the app from job tracker to actual career operating system

### 3. Roman Command Center

#### Best Feature: Weekly Review

Add a dedicated weekly reflection and planning layer with:

- streak summaries
- trend changes
- completed vs planned comparisons
- application funnel changes
- recommendations for next-week focus

What this proves to recruiters:

- analytics thinking
- dashboard design beyond simple charts
- ability to convert data into action

Why this is high leverage:

- the app already captures a lot of activity data
- the highest-value gap is interpretation
- interpretation is what makes dashboards meaningful

Expected implementation difficulty:

- medium
- mostly analytics queries, aggregation, and presentation

Secondary feature: CSV Export/Import

Add:

- export per module
- full-dataset export
- import for seeded or historic data

What this proves:

- practical product judgment
- data portability awareness
- operational usefulness

Best reason to build it:

- it is simple to understand and immediately makes the app feel more complete

### 4. Physics Study Bot

#### Best Feature: Adaptive Study Loop

Build the first real product layer:

- select topic
- generate or serve practice questions
- capture answers
- grade or review answers
- track weak areas
- recommend what to study next

What this proves to recruiters:

- ability to turn an idea into a functioning product
- educational product design
- feedback-loop thinking

Why this is high leverage:

- the repo currently appears underdeveloped publicly
- this is the fastest path to making it portfolio-worthy

Expected implementation difficulty:

- medium-high
- likely needs question flow, tracking, and adaptation logic

## Recommended Build Order

### Option A: Best Internship Portfolio Sequence

1. SQL Playground: Guided Challenge Mode
2. Jessica Career OS: Follow-Up Automation
3. Roman Command Center: Weekly Review
4. SQL Playground: Shareable Query Links + History
5. Physics Study Bot: Adaptive Study Loop

Why this order:

- starts with the most legible flagship product improvement
- follows with a strong business workflow feature
- then adds an analytics-heavy project for breadth

### Option B: Fastest Momentum Sequence

1. Roman Command Center: Weekly Review
2. Jessica Career OS: Follow-Up Automation
3. SQL Playground: Shareable Query Links + History
4. SQL Playground: Guided Challenge Mode
5. Physics Study Bot: Adaptive Study Loop

Why this order:

- front-loads moderate-scope wins
- creates visible product progress quickly
- delays the heaviest build until momentum is established

## Best Feature by Goal

### If the goal is "most impressive to recruiters"

Choose:

**SQL Playground: Guided Challenge Mode**

Reason:

- strongest product transformation
- strongest mix of UX, backend, and data work
- easiest to understand in one demo

### If the goal is "most practical real-world business app"

Choose:

**Jessica Career OS: Follow-Up Automation**

Reason:

- closest to real workflow software
- demonstrates operational usefulness
- adds obvious end-user value

### If the goal is "fastest solid upgrade"

Choose:

**Roman Command Center: Weekly Review**

Reason:

- strong feature without being overly large
- high portfolio clarity
- leverages existing data well

## Suggested Decision Rule

Pick the next feature based on what story Roman wants the portfolio to tell most clearly:

- build **SQL Playground Guided Challenge Mode** if the goal is to look strongest for software engineering and data-oriented internships
- build **Jessica Career OS Follow-Up Automation** if the goal is to show product and workflow-system thinking
- build **Roman Command Center Weekly Review** if the goal is to ship a meaningful improvement quickly

## Final Recommendation

If only one major feature should be built next, the best choice is:

**SQL Playground: Guided Challenge Mode**

It offers the best balance of:

- recruiter clarity
- technical depth
- product maturity
- demo value

If two features are built next, the best pair is:

1. SQL Playground: Guided Challenge Mode
2. Jessica Career OS: Follow-Up Automation

That combination gives the portfolio both:

- a strong educational/data product
- a strong workflow/business product
