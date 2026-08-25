# Flyrank-ai-fluency

# FlyRank AI Fluency

This repository contains my work and assignments for the **General AI Fluency** track of the FlyRank program.

---

## Week 1 — Draw the Path: Portfolio Sitemap + Toolkit

### Assignment Goal

The goal of this assignment was to define the structure and positioning of my technical portfolio, set up my AI toolkit, configure a Claude Project, and use Claude to pressure-test the portfolio sitemap.

---

## Portfolio Direction

### Primary Proof Statement

> **I build and productionize AI-powered software systems.**

### Target Audience

> **An engineering hiring manager evaluating candidates for an AI/ML or AI engineering internship.**

### Primary Action

> **Explore my projects.**

The portfolio is centered around **AI engineering**, while demonstrating supporting capabilities in software engineering, cloud, DevOps, and data through real project work.

The goal is to show evidence through **projects, architecture, technical decisions, implementation, deployment, and results**, rather than simply listing technologies or skills.

---

## 1. Portfolio Sitemap

I created a sitemap defining the structure of the portfolio and how a visitor moves from the initial claim toward the project's proof of work.

The sitemap includes:

- Home
- Projects
- Project / Case Study pages
- Experience
- About
- Contact
- Supporting elements such as skills, resume, GitHub, and social links

The **Projects** section is the primary proof mechanism, with individual case studies providing deeper technical context.

### Evidence

See:

`week-1/Draw_the_Path:Portfolio_Sitemap_+_Toolkit_assignement/sitemap/sitemap.pdf`

---

## 2. AI Toolkit

The Week 1 toolkit was set up with:

- Claude
- ChatGPT
- Gemini
- Perplexity

A Claude Project named **Portfolio Build — AI Fluency** was created specifically for this portfolio build.

The project contains custom instructions that define:

- The portfolio's proof statement
- The target audience
- The primary action
- Claude's role as a tutor and critical thinking partner
- How Claude should challenge assumptions and evaluate portfolio decisions

### Evidence

See:

`week-1/Draw_the_Path:Portfolio_Sitemap_+_Toolkit_assignement/project-instructions-with_POS_audience_action/`

---

## 3. Claude Sitemap Pressure Test

I uploaded the actual sitemap to the Claude Project and asked Claude to critically pressure-test it against:

- The primary proof statement
- The target audience
- The primary action
- The role and necessity of each sitemap section
- Whether the portfolio provides sufficient evidence for the claim
- Whether the portfolio appears too broad in scope

Claude identified several weaknesses, including:

- The case-study structure clearly demonstrated the ability to **build**, but did not explicitly demonstrate **productionization**
- The Projects, Experience, and About sections had too much equal visual/structural weight
- The project tags (`AI/ML`, `Cloud`, `DevOps`, `SDE`, `Data`) could make the portfolio appear to represent several equal professional identities
- The case-study structure was missing explicit production-related evidence such as deployment, CI/CD, testing/reliability, monitoring, and infrastructure/scaling considerations

### Evidence

The pressure-test prompt and Claude's responses are stored in:

`week-1/Draw_the_Path:Portfolio_Sitemap_+_Toolkit_assignement/pressure_tests/`

This includes:

- `pressure-tests-prompt.png`
- Screenshots of Claude's pressure-test response

---

## 4. Change Identified from the Pressure Test

The most important change identified from Claude's feedback is to make **productionization explicit** within the project case studies.

### Change

> **Revise the project case-study structure so that productionization is explicitly represented rather than implied by Implementation, GitHub, or a demo. Incorporate relevant production evidence such as deployment/hosting, CI/CD, testing and reliability, monitoring, and infrastructure or scaling decisions into a concise Productionization section rather than adding multiple separate sitemap pages.**

This keeps the sitemap small while making the **"productionize"** part of the portfolio's primary proof statement visible and credible.

### Evidence

See:

`week-1/Draw_the_Path:Portfolio_Sitemap_+_Toolkit_assignement/changes-to-be-done(noted)/changes.txt`

---

## Week 1 Evidence Structure

```text
week-1/
└── Draw_the_Path:Portfolio_Sitemap_+_Toolkit_assignement/
    ├── sitemap/
    │   └── sitemap.pdf
    │
    ├── project-instructions-with_POS_audience_action/
    │   ├── claude-proj-ss.png
    │   ├── Proj-instr-part-1.png
    │   └── Proj-instr-part-2.png
    │
    ├── pressure_tests/
    │   ├── pressure-tests-prompt.png
    │   └── Claude pressure-test response screenshots
    │
    └── changes-to-be-done(noted)/
        └── changes.txt