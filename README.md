# CSS Specificity Bug: Unexpected Style Inheritance

This repository demonstrates a subtle bug related to CSS specificity.  The bug showcases how a less-specific selector can override a more specific one due to the rules of CSS specificity.

The `bug.css` file contains the problematic CSS.  The `bugSolution.css` file provides a corrected version.

The issue arises from the way CSS resolves conflicting styles.  Understanding CSS specificity is crucial for avoiding these kinds of errors.

## Setup

1. Clone the repository.
2. Open `index.html` (or create a simple HTML file to test the CSS) in your web browser.

## How to reproduce
1. Inspect the paragraph element in your browser's developer tools and observe that it has the lightgreen background.