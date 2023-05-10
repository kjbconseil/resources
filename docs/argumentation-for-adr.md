# Implement an ADR (a log of all the architecture decisions taked by a team on a project) 

## Before going further, read 2 of thoses 
- [https://www.redhat.com/architect/architecture-decision-records](https://www.redhat.com/architect/architecture-decision-records)
- https://blog.octo.com/architecture-decision-record/
- [Scaling the Practice of Architecture, Conversationally (martinfowler.com)](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
- [Documenting Architecture Decisions (cognitect.com)](https://blog.wescale.fr/bonnes-pratiques-pour-%C3%A9crire-un-adr)
- [https://www.linkedin.com/pulse/what-architecture-decision-record-adr-do-i-need-how-useful-atmakur	](https://www.linkedin.com/pulse/what-architecture-decision-record-adr-do-i-need-how-useful-atmakur)
- https://github.com/joelparkerhenderson/architecture-decision-record

## Read this one to embrace a global philosophy (Optional)
- [https://martinfowler.com/articles/scaling-architecture-conversationally.html#WhentraditionalApproachesToArchitectureBreakDown](https://martinfowler.com/articles/scaling-architecture-conversationally.html#WhentraditionalApproachesToArchitectureBreakDown)


## Resume
An ADR or a log decision aime to help every stakeholders in a project to have a log of all architecture decisions.

Caution; an architectural decision is not a developer principle as TDD or DDD could be.
Keep in mind, that we always should be able to mesure a decision.
Indeed, we should be able to apply [SMART pinciple](https://en.wikipedia.org/wiki/SMART_criteria) for each decision that we take.

## SWOT
Strengths:
- Discuss as a team all architecture topics 
- Make it easier to retrieve arch documents
- To know WHY a decision had to be taken at a specific time
- Help onboarding of a new teammate

Opportunities: 
- Simplify documentation for developers (if is is put in a git repo of a project or a wiki)

Weakness:
- Sharing data format with business partners (could ask a re-wording from a project manager or director)

Threats:
- Overthinking
- Log everything and nothing ... (something that is not an architecture decision for example) 
