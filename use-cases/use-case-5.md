# USE CASE: 5 Add a new employees details to ensure they get paid

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *add a new employees details to ensure they get paid*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee details.  Database contains other employee details.

### Success End Condition

A new employees details are added to the database 

### Failed End Condition

No employee details are added.

### Primary Actor

HR Advisor.

### Trigger

A request to add employee details is sent to HR.

## MAIN SUCCESS SCENARIO

1. New employee joins the company and details need to be added.
2. HR advisor captures employees details.
3. HR adds new employee details to ensure they get paid.
4. HR advisor provides employees details to the database.

## EXTENSIONS

3. **Employee details does not exist**:
    1. HR advisor informs finance no employee details exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0