# Applied AI Innovation & Research Enablement (AIRE) Program

College of Social Science, Michigan State University

## Overview

The **Applied AI Innovation & Research Enablement (AIRE) Program** is a college-level initiative designed to support responsible, effective use of artificial intelligence in teaching, research, and academic operations. It is organized around three interconnected pillars:

- a learning environment for building responsible AI literacy
- a research-facing sandbox for experimenting with AI workflows
- an institutional analytics layer for monitoring adoption, readiness, and impact

This organization mirrors the program’s internal systems. The original deployments ran on secure MSU infrastructure. Public versions reproduce the structure, workflows, and methods using synthetic data so others can explore, adapt, and extend the approach.

## Program Goals

AIRE is designed to help the college:

- build responsible AI literacy across faculty, staff, students, and researchers
- support research teams as they integrate AI into methods and workflows
- provide leadership with clear, data-informed insight into AI adoption and readiness
- align AI experimentation with institutional values, governance, and policy
- ensure that adoption is equitable and well supported across departments and roles

The three public repositories in this organization reflect those goals in coordinated ways.

## AIRE Program Components

### 1. AIRE Literacy Hub

**Purpose:** A college-wide learning environment that supports faculty, staff, students, and researchers as they learn how to use AI responsibly in teaching, research, and administrative practice.

**Highlights:**

- modular resources on responsible AI use
- workshop and microcourse materials
- discipline-aware examples and scenarios
- guidance on policy, governance, and classroom use

**Public entry point:** The AIRE Literacy Hub is published as a static site and supporting repositories.  
_(Insert link to the existing literacy hub site and repo here.)_

### 2. AIRE Researcher Sandbox

- **Repo:** `aire-researcher-sandbox`
- **Scope:** research workflows and methodological experimentation  
  <https://github.com/aire-program/aire-researcher-sandbox>

The AIRE Researcher Sandbox is an internal-style toolkit that provides reproducible notebooks, pipelines, and example workflows for researchers and graduate students who want to explore AI in their own work. It focuses on:

- text and document workflows (OCR, NER, topic modelling, embeddings)
- basic retrieval augmented generation (RAG) patterns for research corpora
- evaluation strategies for AI-assisted analysis
- examples that can be adapted to different areas of social science research

Researchers and graduate students can:

- open notebooks directly in Colab
- follow step-by-step explanations
- adapt the workflows to their own data and context
- use the environment as a template for lab-specific experimentation

For details, see the README in the `aire-researcher-sandbox` repository.

### 3. AIRE Impact Dashboard

- **Repo:** `aire-impact-dashboard`
- **Scope:** institutional analytics and decision support  
  <https://github.com/aire-program/aire-impact-dashboard>

The AIRE Impact Dashboard is the program’s decision intelligence layer. It provides leadership, department chairs, program directors, and assessment specialists with a consolidated view of:

- participation in AI literacy activities
- changes in confidence and self-reported competency
- departmental readiness and adoption patterns
- reflection themes and sentiment across roles
- areas where additional support or mentoring may be required

The public version is implemented in Streamlit with Plotly visualizations and ships with a synthetic dataset that mirrors the structure of the internal system. It includes a data upload interface for loading locally curated CSVs and demonstrates the analytic model and decision support patterns without exposing real institutional data.

For more detail, including technical architecture and usage, see the README in the `aire-impact-dashboard` repository.

## How the Components Work Together

- The **AIRE Literacy Hub** supports individuals as they build responsible AI skills.
- The **AIRE Researcher Sandbox** supports research teams as they experiment with AI methods and workflows.
- The **AIRE Impact Dashboard** helps leadership understand where training and experimentation are taking hold, where additional support is needed, and how readiness is developing across the college.

Together, they form a cycle:

1. **Learn** – individuals and departments engage with training and resources through the Literacy Hub.
2. **Experiment** – researchers and graduate students use the Sandbox to test methods and workflows.
3. **Understand** – leadership uses the Impact Dashboard to monitor participation, confidence, readiness, and emerging needs.

Findings from the dashboard feed back into the design of new learning resources and researcher support, closing the loop between training, experimentation, and institutional insight.

## Internal Deployment and Public Mirror

All three AIRE components were first deployed on MSU internal systems and used in live program work. This GitHub organization hosts public mirrors that:

- retain the structure, workflows, and institutional framing of the internal tools
- replace sensitive data with carefully designed synthetic datasets
- document governance, data handling, and responsible AI practices
- support collaboration with partners and other institutions

This separation allows the college to be transparent about methods and design while maintaining appropriate privacy and data protections for internal use.

## Getting Started by Audience

- **Leadership, department chairs, and program directors:** Start with the `aire-impact-dashboard` repository to explore how program activity and readiness can be surfaced in an institutional dashboard.
- **Researchers and graduate students:** Start with the `aire-researcher-sandbox` repository to work through notebooks and workflows that illustrate how AI can be used in research practice.
- **Educators, staff, and students who want AI literacy resources:** Start with the AIRE Literacy Hub site and its associated repositories.

## Governance and Responsible AI

Across all three components, AIRE is grounded in:

- clear governance and documentation
- attention to consent, privacy, and data handling
- an emphasis on responsible and transparent use of AI tools
- reproducible workflows that can be adapted and audited

Future work and extensions of the program follow these same principles. Documentation in individual repositories provides more detail about data models, synthetic data design, and evaluation practices.

## Contributing and Collaboration

AIRE is designed so that:

- other institutions can review the overall model
- individual components can be forked or adapted
- collaborators can propose improvements via issues and pull requests

For contribution guidelines or partnership discussions, refer to the individual repository READMEs or the contact information provided by the program’s institutional owners.
