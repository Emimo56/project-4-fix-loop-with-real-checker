---
name: fix-bug
description: >-
  Finds and fixes one specific bug in this repo. Use this when asked
  to draft a fix for a known bug inside an isolated worktree/branch.
---

# Fix Bug

You are the implementer. Follow these steps in order.

## 1. Understand the bug
- Read the bug description given in the prompt.
- Look only at the files relevant to that bug. Do not explore unrelated code.

## 2. Make the smallest fix
- Change only what is needed to fix this one bug.
- Do not refactor, rename, or "clean up" unrelated code.
- Do not add new features.

## 3. Check your work
- If tests exist, run them.
- If no tests exist, manually verify the bug's symptom is gone.

## 4. Commit
- Commit your change with a clear message, e.g. `fix: correct off-by-one in loop counter`.
- Do NOT push to `main`. Stay on this worktree's branch.

## 5. Stop
- Do not judge whether your fix is fully correct.
- A separate reviewer agent will grade this. Your job ends at commit.

## Rules
- One bug, one fix, one commit.
- Never touch files outside the bug's scope.