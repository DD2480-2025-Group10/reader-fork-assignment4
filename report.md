# Report for assignment 4

**Group 10**: William, Villiam, Erik, Alrik, Boyan

## Project

Name: reader

URL: https://github.com/lemon24/reader

`reader` is a Python library feed reader library for managing RSS, Atom, and JSON feeds. It is designed to allow writing feed reader applications without any business logic boilerplate and without depending on a particular framework.

## Onboarding experience

Did you choose a new project or continue on the previous one?

If you changed the project, how did your experience differ from before?

We chose to work on a new project instead of `mypy` that we worked on in assignment 3. Compared to `mypy`, `reader`
did feel less complex and considerably more approachable based on the time we had to complete the assignment.
The code is well structured, the issue we chose has a clear scope and had a stable test suite. Before choosing `reader`, we were thinking of working on `poke-env` (https://github.com/hsahovic/poke-env) but ultimately chose not to because (*ADD REASON WHY*)

## Effort spent

For each team member, how much time (**in hours**) was spent in:

| Tasks | Villiam | William | Erik | Alrik | Boyan |
|------|---------|---------|------|-------|-------|
| 1. Plenary discussions/meetings | V | W | E | A | B |
| 2. Discussions within parts of the group | V | W | E | A | B |
| 3. Reading documentation | V | W | E | A | B |
| 4. Configuration and setup | V | W | E | A | B |
| 5. Analyzing code/output | V | W | E | A | B |
| 6. Writing documentation | V | W | E | A | B |
| 7. Writing code | V | W | E | A | B |
| 8. Running code | V | W | E | A | B |

For setting up tools and libraries (step 4), enumerate all dependencies
you took care of and where you spent your time, if that time exceeds
30 minutes.

## Overview of issue(s) and work done.

Title: `Use httpx instead of requests`

URL: https://github.com/lemon24/reader/issues/360

`reader` previously used **requests** for HTTP, but its lack of default timeouts and limited hook support had led to increasingly complex workarounds. This issue replaces it with **httpx**, a more modern alternative with built-in timeouts, cleaner request/response hooks, and future HTTP/2 support.

Scope (functionality and code affected).

*TO BE ADDED*

## Requirements for the new feature or requirements affected by functionality being refactored

Optional (point 3): trace tests to requirements.

## Code changes

### Patch

[View diff on GitHub] - https://github.com/lemon24/reader/compare/master...DD2480-2025-Group10:reader-fork-assignment4:master

Optional (point 4): the patch is clean.

Optional (point 5): considered for acceptance (passes all automated checks).

## Test results

Overall results with link to a copy or excerpt of the logs (before/after
refactoring).

## UML class diagram and its description

### Key changes/classes affected

Optional (point 1): Architectural overview.

Optional (point 2): relation to design pattern(s).

## Way of working (NOT DONE)

### Principles Established

Principles and constraints are committed to by the team. ✅

Principles and constraints are agreed to by the stakeholders. ✅

The tool needs of the work and its stakeholders are agreed.  ✅

A recommendation for the approach to be taken is available. ✅

The context within which the team will operate is understood ✅

The constraints that apply to the selection, acquisition, and use of practices and tools are
known. ✅

### Foundation Established

The key practices and tools that form the foundation of the way-of-working are
selected. ✅

Enough practices for work to start are agreed to by the team. ✅

All non-negotiable practices and tools have been identified. ✅

The gaps that exist between the practices and tools that are needed and the practices and
tools that are available have been analyzed and understood. ✅

The capability gaps that exist between what is needed to execute the desired way of
working and the capability levels of the team have been analyzed and understood. ✅

The selected practices and tools have been integrated to form a usable way-of-working. ✅

### In Use

The practices and tools are being used to do real work. ✅

The use of the practices and tools selected are regularly inspected. ✅

The practices and tools are being adapted to the team’s context. ✅

The use of the practices and tools is supported by the team. ✅

Procedures are in place to handle feedback on the team’s way of working. ✅

The practices and tools support team communication and collaboration. ✅

### In Place

The practices and tools are being used by the whole team to perform their work. ❌

All team members have access to the practices and tools required to do their work. ✅

The whole team is involved in the inspection and adaptation of the way-of-working. ❌


Based on the checklist in the Essence Standard v1.2, we asses our way of working as currently completing the In Use state and starting with the In Place state, having hit 1 milestone in the in place phase. We had some issues with using the same tools in this lab, but in the end we managed to sort it out.


## Overall experience (NOT DONE)

What are your main take-aways from this project? What did you learn?

How did you grow as a team, using the Essence standard to evaluate yourself?


Optional (point 6): How would you put your work in context with best software engineering practice?

Optional (point 7): Is there something special you want to mention here?
