# SSE Course Project: TickTick System Analysis

A university course project applying **Systems and Software Engineering (SSE)** and **TRIZ** methodology to analyze and improve a real-world software product — the TickTick productivity app.

## What the project does

The analysis follows a structured 9-step SSE/TRIZ process:

1. **System selection** — TickTick is chosen as the subject: a cross-platform task and time management app with well-defined boundaries and inherent design contradictions.
2. **Value proposition** — identifies the target user (knowledge workers, students), their jobs-to-be-done, pains, and gains, and maps them to TickTick's features.
3. **Nine-Windows (System Operator)** — analyzes the system across past, present, and future at three levels: sub-system, system, and super-system.
4. **Functional model** — maps the system's core functions (capture → structure → plan → remind → execute → track) and identifies negative side effects such as cognitive overload and focus interruption.
5. **Requirements** — derives functional (FR) and non-functional (NFR) requirements from the value proposition and the functional model.
6. **Contradictions** — detects four system-level contradictions, e.g. more features → better functionality but higher cognitive load; more reminders → better reliability but broken focus.
7. **Physical contradiction** — selects the "reminders vs. focus" contradiction and formulates it as a TRIZ physical contradiction: the notification system must be interruptive and non-interruptive at the same time.
8. **TRIZ solution** — resolves the contradiction using Inventive Principles (Dynamization, Segmentation, Preliminary Action): a context-aware adaptive notification system that switches behavior based on whether the user is in a focus state.
9. **Updated functional model** — integrates the solution into a TO-BE model, showing how the negative function is eliminated while all useful functions are preserved.

## Key outcome

The project proposes replacing TickTick's static notification system with a context-aware one that queues and batches notifications during focus sessions, and delivers them interruptively only during idle periods — resolving the contradiction without adding new features or complexity.
