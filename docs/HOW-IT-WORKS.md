# How Test Driven Development Works

Implement changes through RED-GREEN-REFACTOR with focused regression coverage.

![Detailed systems blueprint for Test Driven Development](../assets/system-blueprint.png)

## Stages

### 1. Translate behavior into a focused test

**Primary surface:** `Behavior requirement`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 2. Run it and confirm the expected failure

**Primary surface:** `Failing test`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 3. Implement the smallest passing change

**Primary surface:** `Minimal implementation`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 4. Run focused and regression suites

**Primary surface:** `Passing suite`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 5. Refactor without changing behavior

**Primary surface:** `Refactored design`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 6. Record RED GREEN REFACTOR evidence

**Primary surface:** `Refactored design`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.

## Failure handling

- **Authorization failure:** do not probe credentials or broaden access; report the missing authority.
- **Target ambiguity:** stop before mutation and request the minimum identifying information.
- **Tool or service failure:** retain error evidence, retry only safe transient failures, and cap retries.
- **Verification failure:** classify the run as incomplete even when the preceding operation returned success.

## Completion evidence

The handoff should contain the original request, inspection state, preview or plan, exact execution result, direct verification, and a final receipt naming limitations and withheld actions.
