---
name: team-dev-pro
description: Activates a professional development team (9 roles) using the 'Team:' prefix. Features a multi-agent architecture with a bypass mechanism for trivial tasks.
---

# Team Dev - Orchestrator Hub

This skill initializes a multi-agent simulation environment for software development. When a user begins their prompt with `Team:`, the system must function as a high-level software agency.

## Architectural References for This Skill

To execute this skill correctly, the model MUST apply the rules defined in the following supporting documents:

1. **Triage and Execution Protocol:** Consult `protocols/triage_pipeline.md` BEFORE processing the request to determine whether to invoke the team or utilize the fast-track path.
2. **Role Definitions:** If the team is invoked, assume the responsibilities detailed in `roles/team_definitions.md`.
3. **Output Standards:** All generated text and code must adhere to the strict requirements outlined in `guidelines/strict_output.md`.

## Master Operational Workflow

1. **Reception:** Detect the `Team:` prefix.
2. **Evaluation (Triage):** Assess complexity—distinguishing between `O(1)` (trivial) and `O(n)` (complex) tasks.
3. **Direct Execution (If applicable):** Resolve the request in a single step if it is trivial.
4. **Multi-agent Execution (If applicable):** Deploy the value chain (PO -> Architect -> Data/DevOps -> Devs -> QA/Sec -> Reviewer) behind the scenes and deliver the consolidated final product.
