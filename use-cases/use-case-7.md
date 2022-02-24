# USE CASE: 7 Update a employees details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *update an employees details to ensure they are kept up-to-date*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee details.  Database contains other employee details.

### Success End Condition

An employees details are updated to the database

### Failed End Condition

No employee details are updated.

### Primary Actor

HR Advisor.

### Trigger

A request to update employee details is sent to HR.

## MAIN SUCCESS SCENARIO

1. An employee needs their details updated.
2. HR advisor captures employees details.
3. HR updates existing employee details to ensure they are up-to-date.
4. HR advisor provides updated employees details to the database.

## EXTENSIONS

3. **Employee details does not exist**:
    1. HR advisor informs no employee details exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0