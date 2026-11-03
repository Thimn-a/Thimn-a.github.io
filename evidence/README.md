# Portfolio Evidence

This folder contains the evidence for the BeeHive to Purple Bee integration project referenced in my portfolio.

## Project Overview

![Project Overview](project%20overview.png)

*Figure 1: Overview of the BeeHive to Purple Bee integration project.*

## Systems Involved

![BeeHive](BeeHive.png)

*Figure 2: BeeHive.*

![Purple Bee](PurpleBee.png)

*Figure 3: Purple Bee.*

## Team

![Development Team](Development%20Team.png)

*Figure 4: Development team and roles.*

## Requirements

![User Story](user%20story.png)

*Figure 5: User story.*

![Use Case Diagram](use%20case.png)

*Figure 6: Use case diagram.*

![Activity Diagram](activity%20diagram.png)

*Figure 7: Activity diagram.*

![Data Requirements](Data%20Requirements.png)

*Figure 8: Data requirements.*

![Technical Requirements](technical%20requirements.png)

*Figure 9: Technical requirements.*

## Tools

![OpenCode](opencode.png)

*Figure 10: OpenCode.*

## Agile Log Book

This log records the key deliverables produced during the project and the decisions captured in each one.

### Entry 1: Requirements Document

| Field | Details |
|---|---|
| **Date** | Thursday, 10 September 2026 |
| **Artefact** | BeeHive – Purple Bee Final Documentation (Requirements Document) |
| **Team** | Thimna Booi (Project Lead / Documentation), Kelly Nolte (Researcher / Integration Developer), Kgothatso Kaole (Database Developer / Data Analyst) |
| **Status** | Requirements defined; integration planned but not yet implemented or tested |
| **Document** | [BeeHive-Purple Bee Final Documentation](../BeeHive-Purple%20Bee%20final%20documentation.pdf) |

**Goal of this iteration**

Define how confirmed BeeHive meeting action items become Purple Bee tasks, removing duplicate task capture and keeping traceability between a meeting and the work that comes out of it.

**What was delivered**

- Project overview, system boundary, stakeholders and actors
- 18 business rules (BR-001 to BR-018) and 10 functional requirements (FR-001 to FR-010) with acceptance criteria
- Use case model, use case glossary (UC-001 to UC-010) and detailed narratives
- Activity diagram covering the BeeHive → Integration/API → Purple Bee flow
- Interface, performance, security and data requirements, including data mapping and ownership
- Integration matrix (INT-001 to INT-005) and external dependencies
- Open questions, risks and constraints

**Key decisions**

- Tasks are created only when the nominated project lead (Purple Bee Admin or Manager) explicitly confirms an action item; meeting or AI completion never creates tasks automatically.
- Phase 1 is one-way task creation from BeeHive to Purple Bee over authenticated HTTPS APIs, with no direct database access.
- Duplicates are prevented with the idempotency key `beehive:{meeting_id}:{action_item_id}`.
- Recordings, full transcripts, full AI summaries, private notes and secrets never cross the integration.
- Transient failures are retried (1 min, 5 min, 15 min, 1 h, 6 h); permanent validation errors are returned for correction.

**Carried forward to the next iteration**

- 8 open questions (OQ-001 to OQ-008), including final task fields, the authoritative role field, API endpoint contract, retention periods, volumes and performance targets.
- 8 tracked risks (R-001 to R-008) with mitigations.
- Build and verify the API endpoints and database structures in staging.


#### Document pages

Each section of the requirements document is shown below as page images.

##### Cover and table of contents (pages 2–4)

![Cover and table of contents – page 2](logbook/page-02.png)

*Figure 11: Cover and table of contents – page 2.*

![Cover and table of contents – page 3](logbook/page-03.png)

*Figure 12: Cover and table of contents – page 3.*

![Cover and table of contents – page 4](logbook/page-04.png)

*Figure 13: Cover and table of contents – page 4.*


##### Project overview (pages 5–7)

![Project overview – page 5](logbook/page-05.png)

*Figure 14: Project overview – page 5.*

![Project overview – page 6](logbook/page-06.png)

*Figure 15: Project overview – page 6.*

![Project overview – page 7](logbook/page-07.png)

*Figure 16: Project overview – page 7.*


##### Development team and devices (page 8)

![Development team and devices – page 8](logbook/page-08.png)

*Figure 17: Development team and devices – page 8.*


##### Functional requirements and business rules (pages 9–10)

![Functional requirements and business rules – page 9](logbook/page-09.png)

*Figure 18: Functional requirements and business rules – page 9.*

![Functional requirements and business rules – page 10](logbook/page-10.png)

*Figure 19: Functional requirements and business rules – page 10.*


##### Business use case model (page 11)

![Business use case model – page 11](logbook/page-11.png)

*Figure 20: Business use case model – page 11.*


##### User activities (page 12)

![User activities – page 12](logbook/page-12.png)

*Figure 21: User activities – page 12.*


##### Use case glossary and narratives (pages 13–15)

![Use case glossary and narratives – page 13](logbook/page-13.png)

*Figure 22: Use case glossary and narratives – page 13.*

![Use case glossary and narratives – page 14](logbook/page-14.png)

*Figure 23: Use case glossary and narratives – page 14.*

![Use case glossary and narratives – page 15](logbook/page-15.png)

*Figure 24: Use case glossary and narratives – page 15.*


##### Activity diagram (pages 16–17)

![Activity diagram – page 16](logbook/page-16.png)

*Figure 25: Activity diagram – page 16.*

![Activity diagram – page 17](logbook/page-17.png)

*Figure 26: Activity diagram – page 17.*


##### Interface requirements (page 18)

![Interface requirements – page 18](logbook/page-18.png)

*Figure 27: Interface requirements – page 18.*


##### Performance requirements (page 19)

![Performance requirements – page 19](logbook/page-19.png)

*Figure 28: Performance requirements – page 19.*


##### Security requirements (pages 20–21)

![Security requirements – page 20](logbook/page-20.png)

*Figure 29: Security requirements – page 20.*

![Security requirements – page 21](logbook/page-21.png)

*Figure 30: Security requirements – page 21.*


##### Data requirements (pages 22–26)

![Data requirements – page 22](logbook/page-22.png)

*Figure 31: Data requirements – page 22.*

![Data requirements – page 23](logbook/page-23.png)

*Figure 32: Data requirements – page 23.*

![Data requirements – page 24](logbook/page-24.png)

*Figure 33: Data requirements – page 24.*

![Data requirements – page 25](logbook/page-25.png)

*Figure 34: Data requirements – page 25.*

![Data requirements – page 26](logbook/page-26.png)

*Figure 35: Data requirements – page 26.*


##### Integration and dependency requirements (pages 27–28)

![Integration and dependency requirements – page 27](logbook/page-27.png)

*Figure 36: Integration and dependency requirements – page 27.*

![Integration and dependency requirements – page 28](logbook/page-28.png)

*Figure 37: Integration and dependency requirements – page 28.*


##### BeeHive and Purple Bee integration (pages 29–31)

![BeeHive and Purple Bee integration – page 29](logbook/page-29.png)

*Figure 38: BeeHive and Purple Bee integration – page 29.*

![BeeHive and Purple Bee integration – page 30](logbook/page-30.png)

*Figure 39: BeeHive and Purple Bee integration – page 30.*

![BeeHive and Purple Bee integration – page 31](logbook/page-31.png)

*Figure 40: BeeHive and Purple Bee integration – page 31.*


##### Requirement IDs, priority and traceability (pages 32–33)

![Requirement IDs, priority and traceability – page 32](logbook/page-32.png)

*Figure 41: Requirement IDs, priority and traceability – page 32.*

![Requirement IDs, priority and traceability – page 33](logbook/page-33.png)

*Figure 42: Requirement IDs, priority and traceability – page 33.*


##### Open questions, risks and constraints (pages 34–37)

![Open questions, risks and constraints – page 34](logbook/page-34.png)

*Figure 43: Open questions, risks and constraints – page 34.*

![Open questions, risks and constraints – page 35](logbook/page-35.png)

*Figure 44: Open questions, risks and constraints – page 35.*

![Open questions, risks and constraints – page 36](logbook/page-36.png)

*Figure 45: Open questions, risks and constraints – page 36.*

![Open questions, risks and constraints – page 37](logbook/page-37.png)

*Figure 46: Open questions, risks and constraints – page 37.*


[← Back to main portfolio](../README.md)
