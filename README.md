# CSS Specificity Issue

This repository demonstrates a common CSS issue related to selector specificity.  The problem arises when deeply nested selectors unintentionally override more general styles.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides a solution.

## Problem

The provided CSS has conflicting styles due to the high specificity of a nested selector.  The intended behavior is for `.item` to have a blue background, but the nested selector overrides this with red.

## Solution

The solution involves understanding and manipulating CSS specificity.  The corrected CSS in `bugSolution.css` addresses this by using more appropriate selectors or by using the `!important` flag (although this is generally discouraged).