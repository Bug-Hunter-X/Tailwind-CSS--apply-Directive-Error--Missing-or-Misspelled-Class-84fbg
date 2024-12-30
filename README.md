# Tailwind CSS @apply Directive Error: Missing or Misspelled Class

This repository demonstrates a common yet easily overlooked error when using Tailwind CSS's `@apply` directive. The issue arises when attempting to apply a class that either doesn't exist within your Tailwind configuration or contains a misspelling.  This often results in silent failures where no styling is applied, making debugging difficult.

## Reproduction

The `bug.html` file demonstrates the error.  The `bugSolution.html` shows the correction.

## Solution

Carefully review your Tailwind configuration (`tailwind.config.js` or similar) to ensure that all classes used within the `@apply` directive are correctly defined.  Consider using your IDE's auto-completion feature to avoid typos.