# USE CASE: 6 View an employees details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *view an employees details to support their promotion request*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee details.  Database contains other employee details.

### Success End Condition

employees details are viewed by HR

### Failed End Condition

No employee details are viewed.

### Primary Actor

HR Advisor.

### Trigger

A request to view employee details is sent to HR.

## MAIN SUCCESS SCENARIO

1. HR advisor is requested to view an employees details.
2. HR advisor captures employees details.
3. HR looks at employee details to support their promotion request.

## EXTENSIONS

3. **Employee details does not exist**:
    1. HR advisor informs finance no employee details exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0