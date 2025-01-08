# CSS Specificity Bug: Unexpected Style Override

This repository demonstrates a subtle bug in CSS related to specificity and cascading styles.  The issue arises when selectors have equal specificity, leading to unexpected style overrides based on the order of declaration. 

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file demonstrates a solution using more specific selectors or reorganizing style declarations to ensure the desired outcome.

The bug is described in detail in the `bug.json` file.  This repository serves as an example of a situation that is surprisingly common, yet can take a considerable amount of time to debug if one isn't aware of CSS specificity rules and the way cascading styles work. 