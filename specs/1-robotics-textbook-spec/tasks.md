# Tasks: "Physical AI & Humanoid Robotics" Textbook

**Input**: Design documents from `specs/1-robotics-textbook-spec/`
**Prerequisites**: plan.md, spec.md

## Phase 1: Setup (Shared Infrastructure)

**Purpose**: Initialize the Docusaurus project.

- [X] T001 Initialize Docusaurus project using `npx create-docusaurus@latest textbook classic`
- [X] T002 [P] Update `docusaurus.config.js` with the book title, tagline, and other metadata.
- [X] T003 [P] Create `CONTRIBUTING.md` with initial content guidelines and lesson format.

---

## Phase 2: User Story 1 - Clear Book Structure (Priority: P1) 🎯 MVP

**Goal**: Create the initial structure for the first chapter and its lessons.

**Independent Test**: The first chapter and its lessons should be visible in the sidebar and accessible.

### Implementation for User Story 1

- [X] T004 [US1] Create a directory `docs/1-introduction-to-physical-ai`.
- [X] T005 [P] [US1] Create a lesson file `docs/1-introduction-to-physical-ai/1-what-is-physical-ai.md`.
- [X] T006 [P] [US1] Create a lesson file `docs/1-introduction-to-physical-ai/2-history-of-ai-and-robotics.md`.
- [X] T007 [P] [US1] Create a lesson file `docs/1-introduction-to-physical-ai/3-ethics-of-physical-ai.md`.
- [X] T008 [US1] Update `sidebars.js` to include the first chapter and its three lessons.

**Checkpoint**: At this point, User Story 1 should be fully functional and testable independently.

---

## Phase 3: User Story 2 - Consistent Content (Priority: P1)

**Goal**: Define the content guidelines and lesson format.

**Independent Test**: The `CONTRIBUTING.md` file should be reviewed for clarity and completeness.

### Implementation for User Story 2

- [X] T009 [US2] Flesh out the `CONTRIBUTING.md` file with detailed content guidelines, including tone, style, and a template for lessons.

**Checkpoint**: At this point, User Stories 1 AND 2 should both work independently.

---

## Phase 4: User Story 3 - Docusaurus Integration (Priority: P2)

**Goal**: Document the Docusaurus-specific organizational requirements.

**Independent Test**: A new chapter can be added following the documented guidelines.

### Implementation for User Story 3

- [X] T010 [US3] Create a `docs/guides/docusaurus-integration.md` file.
- [X] T011 [US3] Document the file naming conventions, directory structure, and metadata usage for Docusaurus in `docs/guides/docusaurus-integration.md`.

**Checkpoint**: All user stories should now be independently functional.

---

## Phase N: Polish & Cross-Cutting Concerns

**Purpose**: Improvements that affect multiple user stories.

- [X] T012 [P] Review all content for clarity, consistency, and accuracy.
- [X] T013 [P] Add images and diagrams to lessons where appropriate.
- [X] T014 Run quickstart.md validation.

---

## Dependencies & Execution Order

- **Setup (Phase 1)**: Must be completed first.
- **User Stories (Phase 2+)**: Can be worked on in parallel after Phase 1 is complete.
- **Polish (Final Phase)**: Depends on all user stories being complete.
