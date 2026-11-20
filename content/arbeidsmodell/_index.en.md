---
# id: auto-generated – copied values are overwritten automatically on push
id: 93229e72-4a63-467c-8171-175d413d1275
# id: auto-generated – copied values are overwritten automatically on push
title: Working model
weight: 20
toc: true
lastmod: 2026-11-20T22:39:29+01:00
last_editor: Erik Hagen

---

This page describes how SAMT-BU currently works to map needs and try out solutions. The model is deliberately simplified, and it will be developed further.

## Cases and pilots

The project distinguishes between two things that are easily conflated, and that the project's own documents often use interchangeably:

- A **case** describes a **need** – a situation that does not work well enough today. The cases are found under [Needs](https://docs.samt-bu.no/en/behov/use-cases/).
- A **pilot** is an **implementation measure** – a concrete attempt to do something about one or more needs. The pilots are found under [Pilots](https://docs.samt-bu.no/en/pilotering/).

The relationship between them is **many-to-many**. One pilot can address several cases, and one case can be touched by several pilots – fully or partly, at different stages. Two practical consequences follow:

- **Cases are not merged.** Two cases appearing in the same pilot proposal does not make them one case. Each keeps its own description and is given a relationship instead.
- **Cases do not "lapse" because they are covered elsewhere.** A need handled through a pilot tied to another case is still a real need. "Lapsed" should be reserved for needs that have genuinely been rejected.

## The case description as a simplified statement of need

Needs are currently mapped through **case descriptions** – short, free-text accounts of a situation that does not work well enough. The format was chosen because the threshold is low: it lets many people contribute early, without having to engage with a formal model.

The price of that simplicity is that case descriptions do not systematically distinguish between need, goal, proposed solution and deliverable. Several of the cases in the register contain all four intermixed. Nor does the current register apply the distinction above consistently – some cases are marked as incorporated into or replaced by others.

This is known, and accepted for the time being.

## Carrying out pilots

The pilots are SAMT-BU's main way of trying out solutions. One of the project's most central products is MVPs and the piloting of information models and services, and the pilots are to be carried out in an agile way: with curiosity and learning through experimentation in short iterations, so that we can quickly demonstrate real value and just as quickly discover what does not work (fail fast). Each pilot starts from one or more cases, see [Cases and pilots](#cases-and-pilots).

This chapter describes what is common to all the pilots. What applies to each pilot – needs, goals, scope, participants and deliverables – is found under [Pilots](/en/pilotering/).

### The playbook

The project has produced a "playbook" (dreiebok) for carrying out pilots. It follows a familiar pattern for running projects, in seven phases:

![The playbook in seven phases: 1 Choose pilot, 2 Start-up, 3 Dream journey, 4 Choose MVP, 5 Build MVP, 6 Evaluation, 7 Continuation (figure in Norwegian)](dreiebok-faser.png)

1. **Choose pilot:** which needs (cases) the pilot is to address.
2. **Start-up:** goals, products, scope, staffing and plan.
3. **Dream journey:** how things should work for the user when everything is in place.
4. **Choose MVP:** what is to be built or tried out first.
5. **Build MVP**
6. **Evaluation**
7. **Continuation:** proposal for the next phase.

The phases describe a sequence, but the work is iterative, and individual phases are repeated as needed. The experience from each pilot is to be used to update the playbook.

### Organisation

A separate, autonomous team with a pilot lead is established for each pilot. The team is put together according to the competence the pilot needs, typically specialists from the organisations that own the data and services, architects and lawyers, and representatives of municipalities, county authorities and vendors where relevant.

Each pilot has a plan for its execution, covering background (case), objective, products, scope, staffing, work packages and milestones. The plan is the basis for the page "About pilot N".

### Way of working

- The pilot is carried out iteratively according to agile principles, in sprints of two or three weeks.
- Each sprint starts with a planning meeting and ends with a demo. A joint demo for all pilots under SAMT-BU is being considered.
- Initially, a stand-up for the whole pilot every other day is desirable. In time it may be sufficient to coordinate the work within each work package.
- At least one retrospective should be held during the pilot period.

### Tasks, documentation and communication

- Each pilot has its own repository on GitHub, with the tasks as issues and its own board. See [Tasks and follow-up](/en/styring/oppgaver-og-oppfolging/).
- The pilot's documentation and deliverables are published on [docs.samt-bu.no](/en/pilotering/), under the pilot.
- Communication activities are coordinated with the communications adviser in SAMT-BU's core team.

### Documentation of pilots

The pilots share a common basic pattern on the site, but how the deliverables and the solution description are divided up is not fixed yet. A reusable documentation template is being developed. The general conventions for pages are in [Pages and structure](/en/prosjektleveranser/loesninger/samhandlingsplattform/samt-bu-docs/brukerveiledning/sider-og-struktur/).

| Page | Content |
|---|---|
| **Front page** (Pilot N) | Only a short lead text. The subpages are listed automatically |
| **About pilot N** | Brief and factual, meant to last: need (with link to the case), goals, scope, participants and roles. Not method (described here), period, status or work packages |
| **Tasks and progress** | Right after About. Period, status and work packages: the board, the timeline and possibly the original plan |
| **Meetings** (optional) | Minutes that the deliverables build on, as chapters on one page |
| **Deliverables or chapters** | The content can be divided up in two ways, and the template has not been decided: a "Deliverables" page with one subpage per deliverable (for example dream journey, architecture, legal needs), as in Pilot 4, or thematic chapters directly under the pilot (for example user needs, actors and information flow, choice of solution, details of the chosen solution, legal matters), as in Pilot 6 |
| **Results and the way forward** | When the pilot has something to show: main results, benefits, prerequisites and next steps, briefly and with links to the deliverables |

Status per deliverable (from planned to delivered) is not yet in place. Examples: [Pilot 4](/en/pilotering/pilot-4/) (deliverables) and [Pilot 6](/en/pilotering/pilot-6/) (thematic chapters).

## Further work

The working model described here is a **basis for work, not an adopted metamodel**. A more precise conceptual framework for need, solution, goal and deliverable is under development, and may change both how needs are described and how they are linked to measures.

The conceptual work is found under [Concepts and terminology](https://docs.samt-bu.no/en/innsikt/begrepsapparat-og-konsepter/). The fact that this work evolves does not make the description on this page wrong – it describes practice as it stands today, and is updated when practice actually changes.
