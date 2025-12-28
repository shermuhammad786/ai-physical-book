---
id: 1
title: Create Physical AI Book Constitution
stage: constitution
date: 2025-12-29
surface: agent
model: Gemini
feature: none
branch: master
user:
command: /sp.constitution Create a Constitution document for a book about "Physical AI" with these requirements:
  Target audience: beginners to intermediate
  - Tech stack: Docusaurus for documentation
  - Focus on hands-on learning

  Provide the constitution with: Vision, Core Principles, Success Criteria, Constraints, Stakeholders, and Brand Voice.
labels: [constitution]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
  - .specify/templates/plan-template.md
tests:

---

## Prompt

/sp.constitution Create a Constitution document for a book about "Physical AI" with these requirements:
Target audience: beginners to intermediate
- Tech stack: Docusaurus for documentation
- Focus on hands-on learning

Provide the constitution with: Vision, Core Principles, Success Criteria, Constraints, Stakeholders, and Brand Voice.

## Response snapshot

Created a new constitution for the "Physical AI Book" project. The constitution includes the project's vision, core principles, success criteria, constraints, stakeholders, and brand voice. The version was set to 1.0.0. The `plan-template.md` was updated to reflect the new constitution.

## Outcome

- ✅ Impact: Created the project constitution and updated related templates.
- 🧪 Tests: No tests were run.
- 📁 Files: 
  - `.specify/memory/constitution.md` (created)
  - `.specify/templates/plan-template.md` (modified)
- 🔁 Next prompts: The user can now proceed with creating a specification for a feature using `/sp.specify`.
- 🧠 Reflection: The process of creating a constitution from a user prompt and updating related files was successful. The templating system for PHRs is useful for recording actions.

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): PASS
- Prompt variant (if applicable): None
- Next experiment (smallest change to try): None
