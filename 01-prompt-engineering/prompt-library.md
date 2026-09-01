# Prompt Library

**Workplace scenario:** Student / Academic Research Assistant supporting a university research team.

The prompts below are reusable examples for routine academic workplace tasks. Each prompt follows either the **C.A.R.E.** framework (Context, Action, Role, Expected Output) or **R.C.T.O.** (Role, Context, Task, Output).

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Meeting Summary | Summarize research-team meeting notes | C.A.R.E. | **Context:** I support a university research team and need to turn meeting notes into a concise record. **Action:** Summarize only the information provided, identify decisions, action items, owners, deadlines, and unresolved questions. If a detail is missing, write `[Not Specified]`. **Role:** Act as an academic project support assistant. **Expected Output:** A 5-bullet summary followed by an action-item table with columns: Action Item, Owner, Deadline, Priority, Status. | Concise summary plus a structured action-item table without invented information. |
| Meeting Reschedule Email | Draft a professional schedule-change email | C.A.R.E. | **Context:** A university research-team meeting scheduled for Wednesday at 10:00 needs to move to Thursday at 11:00 because the supervisor has an academic committee commitment. **Action:** Draft a courteous email notifying the team and asking members to confirm availability. **Role:** Act as a professional academic administrative assistant. **Expected Output:** Subject line plus a 100–130 word email, professional and clear. | A concise, courteous email with the new date/time and confirmation request. |
| Research Brief Extractor | Extract key information from a short article or notes | R.C.T.O. | **Role:** Act as a research support assistant. **Context:** I will provide a short article or set of notes related to our project. **Task:** Extract the research objective, main findings, limitations, useful evidence, and follow-up questions. Do not add facts that are not in the source. **Output:** A five-part brief using clear headings and `[Not Specified]` for missing items. | Structured research brief that preserves source meaning. |
| Seminar Planning Assistant | Build a short plan for a student research seminar | C.A.R.E. | **Context:** I am supporting a university research team that will hold a 60-minute student research seminar in four weeks. **Action:** Break the work into Goal → Mechanisms → Phases → Tasks. **Role:** Act as a project coordinator for an academic team. **Expected Output:** A concise table with phases, tasks, responsible role, suggested timing, and completion check. | Practical phased plan with specific tasks. |
| Supervisor Update | Draft a weekly progress update | R.C.T.O. | **Role:** Act as an academic research assistant. **Context:** I need to update my supervisor about completed work, current work, blockers, and next steps. **Task:** Rewrite the notes I provide into a professional weekly update. Preserve facts and flag missing information instead of guessing. **Output:** Subject line plus four short sections: Completed, In Progress, Blockers, Next Steps. | Clear weekly progress update suitable for email. |
| Priority Sorter | Prioritize academic project tasks | C.A.R.E. | **Context:** I have a list of research support tasks with different deadlines and dependencies. **Action:** Prioritize them based on urgency, impact, dependency, and effort. **Role:** Act as a project-support analyst. **Expected Output:** A ranked table with Task, Priority, Reason, Dependency, and Recommended Next Action. Explain any assumptions. | Ranked and justified task list. |
| Recurring Minutes Formatter | Produce consistent minutes from notes | R.C.T.O. | **Role:** Act as a university research-team secretary. **Context:** Our team uses the same minutes format after every meeting. **Task:** Convert the notes I provide into the exact format shown in the example. Do not infer missing information. **Output:** Follow this format: `Meeting Purpose`, `Key Discussion`, `Decisions`, `Action Items`, `Open Questions`. Example action item: `Prepare literature summary | Owner: Research Assistant | Deadline: Friday | Status: Open`. | Consistent meeting minutes in the same recurring structure. |

## Example Output 1 — Meeting Reschedule Email

**Subject:** Research Team Meeting Rescheduled to Thursday at 11:00

Dear Team,

Please note that our research-team meeting originally scheduled for Wednesday at 10:00 has been rescheduled to **Thursday at 11:00** due to the supervisor's academic committee commitment.

The meeting agenda will remain unchanged. We will review current progress, discuss outstanding tasks, and confirm the next steps for the research activities.

Please reply to confirm whether you are available at the new time. If you have a scheduling conflict, let me know as soon as possible so that we can identify an appropriate solution.

Thank you for your flexibility and cooperation.

Kind regards,  
Academic Research Assistant

## Example Output 2 — Supervisor Update

**Subject:** Weekly Research Support Update

### Completed
- Organized the meeting notes into a structured action-item list.
- Prepared the first draft of the seminar task plan.

### In Progress
- Reviewing the literature-summary notes for clarity and completeness.

### Blockers
- Final seminar room confirmation is **[Not Specified]**.

### Next Steps
- Confirm the seminar room.
- Finalize the agenda.
- Send the approved schedule to participants.

## When I Would Use These Prompts
- **Meeting Summary:** after every research-team meeting.
- **Meeting Reschedule Email:** when an academic meeting time changes.
- **Research Brief Extractor:** when converting a source into a quick decision-ready brief.
- **Seminar Planning Assistant:** when organizing a short academic event or milestone.
- **Supervisor Update:** for recurring weekly progress communication.
- **Priority Sorter:** when several research tasks compete for attention.
- **Recurring Minutes Formatter:** to keep meeting minutes consistent over time.
