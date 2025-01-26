# Unexpected :nth-child Behavior in Nested Lists

This repository demonstrates an uncommon issue with the CSS `:nth-child` selector when dealing with nested lists.  The provided CSS intends to style the second list item within nested lists, but it unexpectedly only affects the top-level list items.  The `bug.css` file contains the problematic code, and `bugSolution.css` provides a solution using a more appropriate selector.

## Bug Description
The `:nth-child` selector does not correctly traverse nested list elements, resulting in an unexpected styling outcome.

## Solution
The solution employs a more appropriate approach to select the desired elements by addressing the nested structure directly.  This ensures the correct styling is applied to the intended elements.