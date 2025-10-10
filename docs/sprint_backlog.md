> Last updated: Oct 8, 2025
# Sprint Backlog

### Sprint 1 — Project foundation & environment setup
**Duration:** 2 weeks (Oct 8 - Oct 22, 2025) 
**Goal:** Establish the project's structure, documentation and initial development environment for simulation and AI experimentation.

## Sprint Schedule

| Week | Focus | Expected Output |
|------|--------|-----------------|
| **Week 1** | Setup, documentation, environment installation | Project repo + simulator installed |
| **Week 2** | Testing and validation | “Hello Robot” simulation test + updated docs |

---

## Sprint Backlog

| ID | Task | Description | Related Epic | Acceptance Criteria | Status |
|----|------|-------------|---------------|----------------------|---------|
| **S1.1** | Finalize repo setup | Confirm GitHub repo structure (`docs/`, `src/`, `tests/`) and ensure `.gitignore`, `README.md` are working | Epic 1 | Repo accessible on GitHub, base files visible | Done |
| **S1.2** | Create Python virtual environment | Initialize `venv`, install base packages (`numpy`, `opencv`, `torch`, `transformers`, etc.) | Epic 1 | Able to activate venv and import packages | Done |
| **S1.3** | Install and configure simulator | Choose and install **Webots** or **CoppeliaSim**, confirm sample scenes run | Epic 2 | Simulator runs successfully on Mac | ☐ |
| **S1.4** | Document setup steps | Record installation notes, configurations, and issues in `research_notes.md` | — | Clear environment setup notes committed | ☐ |
| **S1.5** | Define project goal & update epics | Refine `product_goal.md`, `epics.md`, and `product_backlog.md` | — | Files reflect 10-epic structure and vision | ☐ |
| **S1.6** | Create initial simulation script | Write simple Python script that connects to simulator and moves robot forward | Epic 1 | Robot performs a basic motion in simulation | ☐ |
| **S1.7** | Sprint Review & Retrospective notes | Summarize what worked, blockers, and improvements for next sprint | — | Retrospective added to `research_notes.md` | ☐ |


---

## Sprint Deliverables

By the end of Sprint 1, it is expected to have:

- A functional GitHub repository with project structure  
- A working Python environment  
- A running simulator (Webots or CoppeliaSim)  
- A basic "Hello Robot" simulation test  
- Updated documentation and retrospective notes  

---

## Sprint Review Criteria

| Area | Expected Result |
|-------|----------------|
| **Codebase** | Project runs locally with correct structure |
| **Documentation** | `.md` files are updated and committed |
| **Simulation** | Robot executes at least one movement |
| **Reflection** | Lessons learned documented in `research_notes.md` |

---

**Sprint 1 Retrospective**
- What went well:
- What challenges or blockers occurred:
- What I learned:
- What I’ll improve next sprint:

---
