# USE CASE: 3 Produce a Report on the Salary of Employees of a Given Department

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *Department manager* I want *to produce a report on the salary of employees of a given department* so that *I can support financial reporting of the organisation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains current employee salary data.

### Success End Condition

A report is available for a Department Manager to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department Manager.

### Trigger

A request for finance information is sent to a Department Manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given department.
2. Department Manager captures name of the department to get salary information for.
3. Department Manager extracts current salary information of all employees of the given department.
4. Department Manager provides report to finance.

## EXTENSIONS

3. **Department does not exist**:
    1. Department Manager informs finance no department exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0