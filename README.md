# CPS Team Operational Doctrine

**Consistency, Portability, Scalability**

*A doctrine for sustainable, observable, and reproducible team operations.*

---

## Overview

**CPS Team Operational Doctrine** is a framework for building sustainable, observable, and reproducible teams through explicit roles, measurable capacity, task decomposition, and continuous situational awareness.

The doctrine is designed to reduce dependence on exceptional individuals, implicit knowledge, and unsustainable workloads.

Its goal is not to eliminate every failure or incident.

Its goal is to create a team that can:

* continue operating under changing conditions
* detect problems before they become critical
* explain why a schedule is realistic or unrealistic
* identify missing capabilities in the team
* redistribute work without relying on heroics
* improve its own operating model through feedback

---

## What Problem Does CPS Solve?

Teams often fail not because they lack skilled members, but because critical operational information is invisible.

Common examples include:

* unclear roles
* hidden overload
* missing capabilities
* ambiguous decision boundaries
* excessive dependency on specific individuals
* unrealistic schedules
* unclear escalation paths
* unmeasured task complexity
* leaders being forced to manage through intuition alone

CPS attempts to make these invisible factors observable and manageable.

---

## Purpose

The purpose of CPS is to build teams that can deliver results continuously without relying on:

* excessive overtime
* individual heroics
* permanently overloaded leaders
* undocumented knowledge
* exceptional talent as a prerequisite for normal operation

A CPS team should be able to produce reliable outcomes with ordinary professionals operating within sustainable limits.

---

## Core Principles

### Consistency

The same operational rules should produce similar decisions across different people and situations.

Decision-making should not depend entirely on the intuition of one leader.

---

### Portability

The operating model should be transferable between teams and projects.

A member who understands CPS should be able to enter another CPS-based team and quickly understand:

* how decisions are made
* where responsibility exists
* how work is estimated
* when escalation is required

---

### Scalability

The team structure should remain understandable as the organization grows.

Additional members, roles, and responsibilities should be incorporated without requiring the entire operating model to be redesigned.

---

## Leader's Job

A leader continuously observes the team, interprets its current state, makes decisions, and issues the next operational direction.

CPS leaders operate continuously through an OODA-style loop:

**Observe → Orient → Decide → Act**

The leader's primary responsibility is not to personally complete the largest number of tasks.

The leader's responsibility is to maintain the conditions under which the team can operate effectively and sustainably.

Good leadership begins with accurate situational awareness.

---

## Sustainable Capacity: The 80% Rule

A CPS team should not normally plan around 100% of its theoretical capacity.

The default planning ceiling is:

**80% of sustainable capacity**

The remaining 20% is reserved for factors such as:

* unexpected issues
* communication
* reviews
* investigation
* clarification
* support for other members
* learning
* estimation error
* operational variance

This buffer is not considered wasted capacity.

It is part of the team's resilience.

---

## Role Tags

Each member is represented by one or more capability tags.

Examples:

* Architecture
* Design
* Programming
* Review
* Infrastructure
* Security
* Project Leadership
* Liaison

Tags describe **what kinds of work a person can reliably perform**.

A member may hold multiple tags, but holding multiple tags does not automatically mean that all capabilities can be used at full capacity simultaneously.

---

## Capacity Points

Capacity points represent the amount of work a member can sustainably process within a given period.

For example:

* Implementation: 8 pt/day
* Design: 6 pt/day
* Review: 4 pt/day

Initial capacity may be self-declared.

Actual performance should then be observed and the values adjusted over time.

Capacity points are not intended to represent human worth or salary directly.

They represent operational throughput within a defined work category.

---

## Task Decomposition

Large tasks should be decomposed until their technical and design characteristics become understandable.

Avoid tasks such as:

> Accounting Feature

Prefer tasks such as:

* Accounting API
* Accounting Frontend
* External Accounting API Interface

The purpose of task decomposition is not to maximize the number of tickets.

The purpose is to reach a level where complexity, required capabilities, and ownership can be reasonably identified.

---

## Task Point Estimation

One possible estimation model is:

**Technical Elements × Design Perspectives = Task Points**

Example:

A payment feature includes the following technical elements:

* Database
* API
* JavaScript
* PHP
* HTML

Technical elements:

**5**

The task also requires consideration of:

* Frontend
* Backend
* Communication
* External API

Design perspectives:

**4**

Estimated complexity:

**5 × 4 = 20 pt**

Task points are not intended to predict the future perfectly.

They provide an explainable baseline that can be reviewed and improved.

---

## Schedule Estimation

Suppose a task is estimated at:

**24 pt**

A member can sustainably process:

**8 pt/day**

The theoretical minimum is:

**24 / 8 = 3 days**

However, CPS normally plans at 80% capacity:

**8 × 0.8 = 6.4 pt/day**

Therefore:

**24 / 6.4 = 3.75 days**

The operational estimate becomes:

**4 days**

This provides a clear explanation for why a task may require four days even if its theoretical minimum is three.

---

## Assignment

Tasks should be assigned by matching:

* required role tags
* required capacity
* available member capacity
* current workload
* operational risk

If the team does not possess the required tags, this should be visible.

A capability shortage may require:

* schedule extension
* external support
* reassignment
* training
* scope reduction

The important point is that the reason for delay becomes explainable.

---

## Anomaly Detection

CPS treats deviation from estimates as information.

This includes both:

* slower-than-expected completion
* faster-than-expected completion

Unexpected delay may indicate:

* missing knowledge
* hidden complexity
* dependency issues
* inaccurate capacity assumptions
* poor task decomposition

Unexpectedly fast completion may indicate:

* underestimated member capability
* overestimated task complexity
* missed requirements
* skipped design considerations
* unresolved questions being silently ignored

Finishing early is not automatically a problem.

However, significant deviation should be explainable.

---

## Team Topology

A CPS team should make its operational structure visible.

The team topology should show:

* required positions
* required role tags
* required capacity
* assigned members
* current shortages
* backup coverage

This allows leadership to answer questions such as:

* Which capabilities are missing?
* Which member is overloaded?
* Which role has no backup?
* Why is a specific phase slower than expected?
* What kind of person should be added to the team?

---

## Multi-role Members

Members with multiple capability tags can provide valuable redundancy.

However, multi-role capability should not automatically become permanent overload.

A member should normally have a primary role.

Additional capabilities may be used for:

* backup
* temporary support
* cross-team coordination
* emergency coverage
* liaison work

The 20% operational reserve may be used for limited cross-role support where appropriate.

---

## Liaison Roles

Some members primarily improve the flow of information between roles or groups.

A liaison may:

* detect communication gaps
* connect members with the correct expert
* observe team condition
* reduce misunderstanding
* support escalation
* help maintain shared situational awareness

Not all valuable output is a direct implementation artifact.

---

## Redundancy and PACE

Critical operations should avoid dependence on a single person, tool, or procedure.

Where appropriate, teams should define a PACE plan:

* **Primary**
* **Alternate**
* **Contingency**
* **Emergency**

PACE may be applied to:

* personnel
* deployment procedures
* communication channels
* infrastructure
* operational workflows
* decision authority

A critical capability should have a known fallback wherever practical.

---

## Leader Evaluation

A leader should not be evaluated only by personal task throughput.

Leadership output may include:

* increased team throughput
* reduced rework
* reduced overload
* improved predictability
* faster decision-making
* clearer escalation
* reduced dependency on individuals
* improved team resilience

The leader's product is often the condition of the team itself.

---

## Feedback Loop

CPS is not intended to be static.

The team should continuously compare:

* estimated task points
* actual completion time
* declared capacity
* observed capacity
* predicted risks
* actual incidents

The model should be adjusted based on evidence.

A useful cycle is:

**Estimate → Assign → Execute → Observe → Compare → Adjust**

CPS should become more accurate through use.

---

## Quick Example

Task:

**Payment API**

Required tags:

* Backend
* API
* Database
* External Integration

Estimated complexity:

**24 pt**

Assigned member:

* Backend: supported
* API: supported
* Database: supported
* External Integration: supported

Member capacity:

**8 pt/day**

Operational capacity at 80%:

**6.4 pt/day**

Estimated duration:

**24 / 6.4 = 3.75 days**

Planned duration:

**4 days**

---

## What CPS Is Not

CPS is not intended to:

* guarantee that projects never fail
* replace engineering judgment
* turn people into numerical scores
* eliminate professional autonomy
* maximize utilization
* create permanent surveillance
* reward overwork
* require exceptional individuals

CPS is intended to make team operations easier to understand, explain, and improve.

---

## Status

CPS Team Operational Doctrine is currently an experimental framework.

Definitions, terminology, estimation models, and operational practices are expected to evolve through real-world use and community feedback.

Contributions, criticism, field reports, and alternative models are welcome.

---

## Guiding Idea

> A sustainable team does not depend on people continuously exceeding their limits.
>
> It depends on making roles, capacity, decisions, and risks visible enough to act before failure occurs.
