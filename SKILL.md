---
name: "vibe-console-cleaner"
description: "Removes development console.log statements. Invoke when preparing code for production or user asks to clean logs."
---

# Vibe Coding Cleanup: Console Cleaner

This skill specializes in removing leftover debugging statements.

## Capabilities
1. Finds and removes `console.log`, `console.info`, and `console.debug` statements.
2. Preserves `console.error` and `console.warn` as they are usually needed for production monitoring.
3. Cleans up commented-out debugging code block.

## Usage
Invoke this skill when a feature is complete and the code is being prepared for a pull request or production deployment.