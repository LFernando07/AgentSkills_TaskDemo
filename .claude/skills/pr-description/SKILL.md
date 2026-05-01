---
name: pr-description
description: Wriite pull request description. Use when create a PR, writting a PR, or when the user ask to summarize changes for a pull request
---

When writting a PR description:

1. Run 'git diff main...HEAD' to see all changes on this branch.
2. Write a decription following this format:

## What

One sentense explaining what this PR does.

## Why

Brief context on why this change needed.

## Changes

- Bullet points of specific changes made
- Group related changes together
- Mention any files deleted or renamed

## Testing

How to verify this works. Include specific commands if relevant

Keep description concise. Focus on what a reviewer need to know.
