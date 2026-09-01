# Information Processing Example

## Purpose
This example demonstrates **summarizing, extracting, restructuring, and prioritizing** unstructured research-team notes into a decision-ready output.

## Raw Input
> Team meeting notes: The student research seminar should happen during the last week of September. We need a room, but nobody confirmed one yet. Sara will prepare the draft agenda by 8 September. The research assistant will collect presentation titles from the student presenters by 10 September. Dr. Khalid said he will review the final agenda, but no exact review date was given. We should keep the seminar to one hour. Someone needs to send the participant email after the room is confirmed. The team prefers 3 short presentations and 10 minutes for questions at the end. We also need to check whether the projector is available. Priority is to confirm the room first.

## Prompt Used
**Context:** I support a university research team and need to convert messy meeting notes into a decision-ready brief.

**Action:** Summarize only the information provided. Extract decisions, action items, owners, deadlines, priorities, and unresolved questions. If an owner, date, or other detail is missing, write `[Not Specified]` rather than guessing.

**Role:** Act as an academic project support assistant.

**Expected Output:**  
1. A short summary.  
2. An action-item table with columns: Action Item, Owner, Deadline, Priority, Status.  
3. A short list of unresolved questions.

## AI Output
### Summary
- The team plans to hold a one-hour student research seminar during the last week of September.
- The preferred format is three short presentations followed by ten minutes for questions.
- Room confirmation is the highest priority.
- A draft agenda and presentation titles must be prepared before the seminar.
- Projector availability and the participant email remain dependent on additional confirmation.

### Action Items
| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm seminar room | [Not Specified] | [Not Specified] | High | Open |
| Prepare draft agenda | Sara | 8 September | Medium | Open |
| Collect presentation titles | Research Assistant | 10 September | Medium | Open |
| Review final agenda | Dr. Khalid | [Not Specified] | Medium | Open |
| Send participant email | [Not Specified] | After room confirmation | Medium | Blocked |
| Check projector availability | [Not Specified] | [Not Specified] | Medium | Open |

### Unresolved Questions
- Which room will host the seminar?
- Who is responsible for room confirmation?
- When will Dr. Khalid review the final agenda?
- Who will send the participant email?
- Who will check projector availability?

## Human Review
I checked the AI output against the raw notes. I confirmed that:
- the one-hour duration, three presentations, and ten-minute Q&A were preserved correctly;
- the priority of room confirmation was correctly identified as high;
- no owner or deadline was invented;
- all missing details were marked `[Not Specified]`;
- “send participant email” was correctly shown as dependent on room confirmation.

I changed no factual content because the structured result accurately reflected the source.

## Final Structured Output
### Decision-Ready Summary
The research team intends to hold a **60-minute student research seminar in the last week of September**, using a format of **three short presentations plus ten minutes for questions**. The immediate priority is to **confirm the seminar room**, because the participant email depends on it. The draft agenda is due on **8 September**, and presentation titles are due on **10 September**.

### Final Action-Item Table
| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm seminar room | [Not Specified] | [Not Specified] | High | Open |
| Prepare draft agenda | Sara | 8 September | Medium | Open |
| Collect presentation titles | Research Assistant | 10 September | Medium | Open |
| Review final agenda | Dr. Khalid | [Not Specified] | Medium | Open |
| Send participant email | [Not Specified] | After room confirmation | Medium | Blocked |
| Check projector availability | [Not Specified] | [Not Specified] | Medium | Open |

## Information Tasks Used and Why
- **Summarizing:** to reduce the raw meeting notes to the main decisions and key points.
- **Extracting:** to identify action items, owners, deadlines, priorities, and unresolved questions.
- **Restructuring:** to convert unstructured notes into a clear summary and action-item table.
- **Prioritizing:** to identify room confirmation as the first action because other communication depends on it.

### Final Unresolved Questions
1. Who will confirm the room, and by what date?
2. When will Dr. Khalid complete the agenda review?
3. Who will send the participant email?
4. Who will verify projector availability?
