# CSS Specificity Conflict Bug
This repository demonstrates a common CSS bug related to specificity conflicts, specifically when styling pseudo-elements such as `:before` or `:after`. The issue arises from unintentionally overriding styles due to the order and specificity of CSS selectors.

## Bug Description
The `bug.css` file contains CSS rules that style a `div` element and its `:before` pseudo-element. However, a later style rule with higher specificity overrides the initial style, resulting in unexpected visual output. 

## Solution
The `bugSolution.css` file shows how to resolve this issue by either modifying the specificity of the selectors or rearranging the style rules in the stylesheet to ensure the desired effect. 

This example highlights the importance of understanding CSS specificity and carefully ordering your styles to avoid such issues.