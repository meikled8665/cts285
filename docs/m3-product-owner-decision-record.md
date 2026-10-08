# M3 Product Owner Decision Record

## Scenario
StudyTrack release planning under constrained capacity.

## Round 1 — Capacity 13
- ST-01: Create a study task (3 pts)
- ST-02: Mark a study task complete (2 pts)
- ST-03: Recover a missed task (3 pts)
- ST-08: Parent progress dashboard (5 pts)

**Why this release slice was defensible:**
Creating tasks and marking them as complete would be essential features for this type of program, and recovering missed tasks could keep the user motivated. Parents may want to keep up with their child's progress (and there is stakeholder interest).

**One intentional deferral and why:**
I intentionally left out the AI study recommendations. It is not needed for the program to function; it was not requested by stakeholders, and it would likely take up too much time and resources

## Complication
Capacity dropped from 13 to 10 points. Keyboard accessibility testing revealed that task entry cannot reliably be completed with keyboard navigation, so ST-04 became release-critical.

## Revised Release Slice — Capacity 10
- ST-01: Create a study task (3 pts)
- ST-02: Mark a study task complete (2 pts)
- ST-03: Recover a missed task (3 pts)
- ST-04: Keyboard-accessible task entry (2 pts)

### Removed after complication
- ST-08: Parent progress dashboard

### Added after complication
- ST-04: Keyboard-accessible task entry

**What changed and why:**
I dropped the parent dashboard and made it keyboard-accessible. The dashboard isn't as important as the other features, and making it keyboard-accessible makes the program easier for some users.

**Tradeoff accepted:**
Trading off the parent dashboard for keyboard accessibility.

## Transfer to DataMan
Before finalizing your DataMan backlog, review whether any item is high value but not ready, depends on unresolved work, consumes disproportionate effort, or should move because it reduces risk or unlocks other work.
