# Uncommon CSS Bug: Incorrect Style Application to Nested Elements with Same Class

This repository demonstrates an uncommon bug in CSS that can lead to unexpected styling issues.  The bug involves incorrectly applying styles to nested elements with the same class within a parent element. This is often overlooked as it doesn't throw an error, only resulting in undesirable visual effects.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` provides a solution.

## Bug Description
The issue arises when using a CSS selector that targets elements with a specific class that are descendants of another element with a different class.  If multiple elements with the same class are nested within the parent, the style is applied to all of them, potentially causing unintended visual consequences.

## Solution
The solution involves using more specific CSS selectors to target only the desired elements.  This might involve using child selectors or more refined class names.