# DataMan Requirements Register

> Replace all bracketed prompts with your own project evidence and requirements. Delete the prompts before submitting.

## Project Context

The Texas Instramunts Dataman from the 1970's will be remade digitally using modern technology with a new added features to help children today learn math. It will still have most of the original core features, but it will also have new features like the ability to store data and a parent dashboard that allows prents/teachers to keep up with the student's progress.

## Evidence Notes

- **E-01 — Source:** [DataMan manual / elicitation case / simulation / other confirmed source]  
  **Evidence:** [What does the source tell you?]

- **E-02 — Source:** [source]  
  **Evidence:** [evidence statement]

- **E-03 — Source:** [source]  
  **Evidence:** [evidence statement]

- **E-04 — Source:** [source]  
  **Evidence:** [evidence statement]

## Functional Requirements

- Answerchecker

- + Enter a math problem and a possible solution
- + Dataman checks their answer  
- + *  prints an error if it's wrong
-  + * Flashes an image if it's correct
-  + Dataman shows the correct answer after several failed attempts
- Memory Bank
-  + Up to 10 difficult problems can be saved for later
-  + Stored problems can be precticed in their own timed Answerchecker
-  +  * 2 attempts per problem
-  +  * results screen at the end showing the number of problems solved correctly, the number of problems attempted, and the amount of time it took to complete the problems
-  Parent/Teacher Dashboard
-  + View student progress
-  +  * See what problems a student answered in a session
-  +  * View stored problems in a memory bank
-  +  * View the time taken and accuracy after solving all the problems in the memory bank
-  Save Data
- +  Data like the problems stored in the memory bank should be saved so that no data is lost when the user logs off the coputer
  
### FR-01
**Requirement:** The system must be able to calculate and check the answer to math problems.  
**Source/Rationale:** "When DataMan is first turned on,  is set to function as an answer checker. This mode of operation ecourages children to experiment with problems and explore number relationships." 

### FR-02
**Requirement:** The system must have a parent dashboard.  
**Source/Rationale:**  "Adults want to understand what the learner practiced and whether progress is occurring..."

### FR-03
**Requirement:** The system must be able to store data.  
**Source/Rationale:** "Students shouldn’t lose their work" "...Students may pause practice and return later..." "...Learner’s saved practice state to remain available after leaving and returning to the application."

### FR-04
**Requirement:** The system must hve a way to allow students to practice harder problems.  
**Source/Rationale:** Repeating problems could make it easier for students to memorize answers.


## Non-Functional Requirements

- Program should be able to run in a browser
-  + More easily accessable
-  + can run on all devices

- Instant feedback
- + Students should not have to wait to find out if an answer is right or wrong
- Clear enough for a child to understand
- + Simple, shorter words
- + simple names
- + * easy for a kid to understand without a manual or an explanation from an adult
- + most of the program should be on one or two screens
- + * easier to navigate
### NFR-01
**Requirement:** The system must be able to run in a browser.  
**Source/Rationale:** "Stakeholders say modern means the experience should work reliably in a browser..."

### NFR-02
**Requirement:** The system must easy enough for a child to read.  
**Source/Rationale:** The product is mainy targeted towards children learning basic math.

### NFR-03
**Requirement:** The system must be responsive.

**Source/Rationale:** "Stakeholders identify immediate answer feedback"

## Open Questions / Assumptions

Do not turn an unsupported idea into a confirmed requirement. Record unresolved items here until evidence supports a decision.

- **Q-01:** How will parents/teachers access the dashboard?
- **Q-02:** Progra will be made with Python SQL and Flask
## Final Quality Check

Before submitting, confirm that each requirement is:

- [ ] Clear enough for another team member to interpret consistently.
- [ ] Supported by evidence, a stakeholder need, or a confirmed project constraint.
- [ ] Testable or verifiable later.
- [ ] Solution-neutral enough for this stage of the project.
- [ ] Focused on one main capability or quality.
- [ ] Classified correctly as functional or non-functional.

Also confirm:

- [ ] At least four functional requirements are included.
- [ ] At least three non-functional requirements are included.
- [ ] Every confirmed requirement has a source/rationale.
- [ ] Open questions and assumptions are separated from confirmed requirements.
- [ ] The simulation decision record is saved at `docs/decisions/m2-elicitation-decision-record.md`.
- [ ] This file is saved as `docs/requirements.md`, committed, and synced to GitHub.