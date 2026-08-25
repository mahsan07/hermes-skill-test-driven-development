# How Test Driven Development Works

The visuals on this page are static SVGs, so they render directly on GitHub on phones and desktop browsers. Each one is generated from a model specific to this skill.

## System architecture

![Detailed system map for Test Driven Development](../assets/system-map.svg)

### Components

- **1. Behavior requirement:** participates in translate behavior into a focused test.
- **2. Failing test:** participates in run it and confirm the expected failure.
- **3. Minimal implementation:** participates in implement the smallest passing change.
- **4. Passing suite:** participates in run focused and regression suites.
- **5. Refactored design:** participates in refactor without changing behavior.

## Actor and data sequence

![Actor and data sequence for Test Driven Development](../assets/operation-sequence.svg)

### 1. Translate behavior into a focused test

**Primary surface:** `Behavior requirement`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 2. Run it and confirm the expected failure

**Primary surface:** `Failing test`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 3. Implement the smallest passing change

**Primary surface:** `Minimal implementation`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 4. Run focused and regression suites

**Primary surface:** `Passing suite`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 5. Refactor without changing behavior

**Primary surface:** `Refactored design`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.
### 6. Record RED GREEN REFACTOR evidence

**Primary surface:** `Behavior requirement`

Record the concrete input, the operation performed, and the evidence produced at this stage. Continue only when the output is sufficient for the next stage; otherwise preserve the blocker and stop.

## Example output shape

![Illustrative output for Test Driven Development](../assets/example-output.svg)

The example is a visual contract: a real run may look different, but it should expose comparable state, provenance, and verification information. It is not presented as evidence of a live external action.

## Decision and stop conditions

![Decision guide for Test Driven Development](../assets/decision-guide.svg)

The workflow stops when the target is ambiguous, the relevant surface is unavailable or unauthorized, or the final artifact cannot be checked. A logged-in session or successful tool call is not by itself proof that the requested outcome is complete.

## Verification checklist

- Confirm every component shown in the system map exists in the target environment.
- Trace the actor sequence using actual tool output or artifact state.
- Compare the result with the example-output information contract.
- Re-read or reopen the final artifact instead of trusting an attempt message.
- Report omitted stages, unsupported capabilities, and remaining human decisions.
