# Python learning log

A working log of learning Python properly — from fundamentals toward backend
development — as part of a 24-week plan.

**The rule for this repository: nothing is added until it runs.**

## Current state

Week 1 is a command-line to-do app with JSON persistence. The files appear here
once they execute, not before — no placeholder code, no copied tutorials.

## Progress

| Week | Build | Status |
|---|---|---|
| 1 | To-do CLI app: menu loop, JSON storage, input validation | next |

## How this repository is organised

Code lives in small, separate files rather than one growing script, so each
piece can be run and understood on its own. Early weeks are single files; later
weeks become folders with a `main` entry point.

## Running anything in here

Every file runs on its own:

```bash
py path/to/file.py
```

Nothing needs a build step, a virtual environment, or a service.

## Commit style

One commit per logical step, with a message that says what changed and why.
A single dump commit at the end hides exactly the part worth reviewing: the
order in which the problem was solved.

## Why this is public

Learning in public keeps the work honest. If a commit is wrong, it is visible,
and fixing it is part of the record.
