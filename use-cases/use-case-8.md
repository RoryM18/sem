# USE CASE: 7 Delete a employees details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *delete an employees details to ensure they the company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee details.  Database contains other employee details.

### Success End Condition

An employees details are deleted from the database

### Failed End Condition

No employee details are deleted.

### Primary Actor

HR Advisor.

### Trigger

A request to delete an employees details is sent to HR.

## MAIN SUCCESS SCENARIO

1. An employee needs their details deleted.
2. HR advisor captures employees details.
3. HR deletes existing employee details to ensure the company is compliant with data retention legislation..
4. HR advisor removes deleted employees details from the database.

## EXTENSIONS

3. **Employee details does not exist**:
    1. HR advisor informs no employee details exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0