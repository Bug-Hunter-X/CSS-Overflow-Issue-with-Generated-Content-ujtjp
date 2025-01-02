# CSS Overflow Issue with Generated Content

This repository demonstrates a common yet uncommon CSS bug related to overflowing generated content using the `::before` and `::after` pseudo-elements.  The bug occurs when the content generated using the `content` property exceeds the bounds of its containing element.  This can lead to unexpected behavior, such as overlapping elements or content being hidden.

The `overflowingContent.css` file showcases the buggy code, while `overflowingContentSolution.css` provides the solution.

The solution involves using appropriate CSS properties to handle the overflow, ensuring that the generated content doesn't interfere with the rest of the layout.