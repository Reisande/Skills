---
name: build-learning-site
description: Build or revise a personal study website that turns chosen sources into guided concept sessions, agent-written tests, and a spaced review queue. Use for a learning dashboard or tutor site.
---

# Build a learning site

Use the learner's existing stack and saved progress. Reuse its calendar, course IDs, storage and review interface where possible. Design around what the learner can demonstrate. Time is a ceiling they can change. Keep the current task, its evidence of completion and the next due review visible. Put the resource library and optional extensions behind a secondary view. When the learner wants a longer view, derive monthly summaries and expandable weeks from the same dated tasks and review slots as the daily screen. Respect changing weekday availability, phase boundaries and explicit week overrides.

## Choose sources and milestones

Read the installed guided-learning and adversarial-recall skills when designing sessions. Rank a short shortlist by authority, match to the learner's goal and prerequisites, inspectable exercises, feedback quality and currency where it matters. Give one concrete reason and one limitation per choice. Run the shortlist by the learner before adding new required reading. Keep existing notes and courses. Ask where personal notes live and link to the relevant heading.

Define each concept by a stable ID, source locator, observable task and pass criterion. Interleave related subjects over the week. Keep one new concept in focus at a time. Example: start from a trace, predict what caused a growing queue, read one section that tests that prediction, then change the traffic pattern.

## Build the session loop

Open with one due cold question when available. An empty queue starts with an unscored prediction. Use guided-learning to have the learner explain, predict or code before reading the smallest relevant passage. Probe one inference at a time. Capture the first specific gap and link it to a small exercise. Offer a hint only during coached practice. Preserve a fresh unaided attempt for assessment.

When a test is requested, spawn a dedicated assessment agent. Give it the concept ID, verified passage and locator, objective, scope and round ID. Have it prepare its rubric privately. Show only the contract or open question and the submission instructions. Prefer learner-written code with a runnable failing test when the behavior is executable. Use written explanations, predictions or code for all tests. Exclude multiple choice and recall cards.

Persist the round ID, question and agent-session reference before displaying the test, so reopening it resumes the original grader. Wait for a submission or explicit end. Resume the same agent for adversarial grading. Credit sound alternatives. Check a fresh boundary condition, distinguish observed execution from reasoning, and identify the first missing inference. Treat an ambiguous item as void. Keep a coached repair distinct from the first result. Keep private grading material outside learner-facing pages before submission.

## Persist and verify

Save each round once with its concept, source, date, response, outcome, assistance, gap and next due date. Reuse a suitable scheduler or use the interval rules in adversarial-recall. Misses return sooner. Assisted or same-day successes cannot extend the interval. Voids preserve the prior due date. Require delayed unaided application for retention. Show the next due concept in the learner's existing queue. Retain history across retries, refreshes and later rounds.

Check the normal path from the learner's screen: start a test, submit, inspect the grade, reload, and find the dated review. Cover duplicate submissions, unavailable agents and old progress. Use a disposable learning record for verification. Explain which actions the site performs and which need a Codex conversation when the chosen host has no agent runtime.
