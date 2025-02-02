# Inconsistent Flexbox Layout with Oversized Children

This repository demonstrates an issue with flexbox layouts where inconsistent behavior arises when the combined width of child elements exceeds the width of the container.  Certain browsers might handle this edge case differently, leading to unexpected layout results.  The provided CSS file (`bug.css`) showcases the problem, while the solution file (`bugSolution.css`) provides a possible fix.

## Problem

The original CSS aims for an even distribution of two paragraphs within a flex container. However, if the content within the paragraphs causes their total width to surpass the container's available space, some browsers may render the layout incorrectly.  This inconsistency can impact cross-browser compatibility.

## Solution

The solution implements a more robust approach to handle potential overflow within the flex container.  This ensures more consistent rendering across different browsers.