---
title: Requirements Engineering
---

## FSE Requirements Engineering

- ### Requirements
  - ##### Functional - "What a system should do"
    - Its features
  - ##### Non-functional - "under what restrictions"
    - Performance, usability, security, availability, etc.

## Requirements Elicitation

- To **Elicit**: "evoke or draw out a (_reaction, answer or fact_) from someone"
  - Draw out the software requirements from a customer

### Requirements Elicitation Techniques

- On-Site Customer
- Active Stakeholder Participation
- Electronic Interviews
- Face-to-Face Interviews
- Focus Groups
- Joint Application Design (JAD)
- Observation
- Legacy Code Analysis
- Reading

### Requirements Management

- Requirements are always changing
- Need to keep track of individual requirements and their versions
  - Requirements identification
  - Change management
  - Traceability management
  - Impact analysis

## Requirements validation

### Two types of systems

1. Low risk and known users
2. High risk and uncertain "success"

### Low risk and unknown users

- Example: library control system
- Known system, fundamental in every library, etc.
- Necessity and feasibility of this system are obvious
- User stories work well!

### High risk and uncertain "success"

- Example: virtual store for renting digital books with payment via blockchain
- Typical startup systems, but not exclusive
- As risk ig high, implementation (idea) has to be quickly validated with real users

### Minimum Viable Product (MVP)

- Minimal - smallest features set (lowest cost)
- Viable - objective is to obtain data and validate an idea
- Product - can be used now

![](attachments/MVP%20Illustration.png)

## Build-Measure-Learn cycle

- At the end of a cycle, you can:
  - Make some adjustments and run cycle again
  - Pivot: change product focus (e.g. music rentals)
  - Give up (money ran out!)
  - It worked out! Let's build a more robust product

## A/B Testing

- Scenario where two requirements implementations "compete" with each other
- Example: online store
  - "Does the model photographed with the products impact the business?"
    - Original version
    - New version, proposed by some devs
- Is it worth migrating to the new version?
- A/B testing let the data decide
- **Version A**: Control (old), **Version B:** Treatment (new)
