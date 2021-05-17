# Architecture

- [Architecture](#architecture)
  - [Scope](#scope)
  - [Goals](#goals)
  - [Key Terms and Definitions](#key-terms-and-definitions)
  - [Key Partners](#key-partners)
  - [Technologies](#technologies)
  - [Assumptions](#assumptions)
  - [System Architecture](#system-architecture)
  - [System Steps](#system-steps)
  - [Related Workflows](#related-workflows)
  - [Quality](#quality)
    - [Security](#security)
    - [Expected Load](#expected-load)
    - [Targeted SLA](#targeted-sla)
    - [Retention Policy](#retention-policy)
  - [Quality Scenarios](#quality-scenarios)
    - [PROBLEM 1 : Short blurb here](#problem-1--short-blurb-here)
      - [SOLUTION](#solution)
      - [KPI](#kpi)
    - [PROBLEM 2: Short blurb here](#problem-2-short-blurb-here)
      - [SOLUTION](#solution-1)
      - [KPI](#kpi-1)
  - [Implementation Considerations](#implementation-considerations)
  - [Feature List](#feature-list)
  - [Environment Matrix](#environment-matrix)
    - [Development](#development)
    - [QA](#qa)
    - [ITE/Stage](#itestage)
    - [Prod](#prod)

This is a template document for outlining a system architecture.
This type of document is intended to be a living document. Some may wonder
why this is in Markdown. Simple. Markdown means I dont have to focus on
the application I am writing on; just the content.  The markdown can either
then be imported and/or coverted to a supported format for the desired
documentation tool(e.g., MS Teams, Confluence, Sharepoint, etc)

## Scope

## Goals

*Explain the vision and goals for this system*

## Key Terms and Definitions

| Term      | Definition                                                                     |
| --------- | ------------------------------------------------------------------------------ |
| Component | A Service, Worker or Agent that runs independently and is a part of the system |

## Key Partners

*List the key parters, both internal and external that are needed for this Architecture*

## Technologies

*List the technologies/frameworks/libraries used and where info can be found.
It would also be useful to give a short description of why the technology
was chosen.*

## Assumptions

*List any assumptions about the system, its in(e)gress, etc.*

## System Architecture

*Provide any diagrams needed to give better insights into how the system is built and how it works*

## System Steps

*Provide additional text exlpaining how data moves through the system*

## Related Workflows

*List any known workflows that use this system*

| Name                    | Description | Go Live    | Active |
| ----------------------- | ----------- | ---------- | ------ |
|                         |             |            |        |
| _Link to Workflow Page_ |             | 2021-01-01 | Yes/No |

## Quality

### Security

### Expected Load

### Targeted SLA

### Retention Policy

## Quality Scenarios

Quality Scenarios, are very similar to acceptance criteria in everything but
format. While acceptance criteria are more centered on Given-When-Then at the
application level, Scenarios are regarding the larger architecture and
expectations. They are composed of

1. Scenario in which there is: a Use-Case, a Change, and a Failure.
2. System
3. Metric/KPI that measures that system is performaing as expected

### PROBLEM 1 : Short blurb here

Describe the problem. Note that there cannot be a solution with out a clearly
defined problem.

1. **What** is the business problem? (Is it related to a Use, Change, or Failure)
2. **Why** is it an issue?
3. What is this **connected** to? Parters/Systems impacted?

#### SOLUTION

Describe the solution

1. **Cost** of doing it (e.g. LOE, Performance Impacts, etc)
2. **Consequences** of NOT doing it (e.g., Performance, Resources, etc)

#### KPI

Describe how we know/measure that it works. This metric should be easy to
clearly define and verify.

### PROBLEM 2: Short blurb here

Describe the problem. Note that there cannot be a solution with out a clearly
defined problem.

1. **What** is the business problem? (Is it related to a Use, Change, or Failure)
2. **Why** is it an issue?
3. What is this **connected** to? Parters/Systems impacted?

#### SOLUTION

Describe the solution

1. **Cost** of doing it (e.g. LOE, Performance Impacts, etc)
2. **Consequences** of NOT doing it (e.g., Performance, Resources, etc)

#### KPI

Describe how we know/measure that it works. This metric should be easy to
clearly define and verify.

## Implementation Considerations

This section is to track considerations or concerns during implementation.

| No  | Item | Description | Detail | Question | Answer |
| --- | ---- | ----------- | ------ | -------- | ------ |
| 01  |      |             |        |          |        |
| 02  |      |             |        |          |        |
| 03  |      |             |        |          |        |

## Feature List

| No  | Feature | Ticket | Supported | Release Date | ENV | Notes |
| --- | ------- | ------ | --------- | ------------ | --- | ----- |
| 01  |         |        |           |              |     |       |
| 02  |         |        |           |              |     |       |
| 03  |         |        |           |              |     |       |

## Environment Matrix

### Development

| Component | Version | Notes |
| --------- | ------- | ----- |
|           |         |       |

### QA

| Component | Version | Notes |
| --------- | ------- | ----- |
|           |         |       |

### ITE/Stage

| Component | Version | Notes |
| --------- | ------- | ----- |
|           |         |       |

### Prod

| Component | Version | Notes |
| --------- | ------- | ----- |
|           |         |       |
