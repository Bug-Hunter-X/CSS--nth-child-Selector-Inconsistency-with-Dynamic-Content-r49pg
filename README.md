# CSS :nth-child Selector Inconsistency with Dynamic Content

This repository demonstrates a common issue with the CSS `:nth-child(n)` selector when dealing with dynamic content. The `:nth-child` selector's behavior can be unpredictable if the DOM structure changes after the page loads, leading to unintended styling.

The `bug.css` file showcases the problem, while `bugSolution.css` presents a potential solution using JavaScript to apply the styling directly to the elements, independent of the `:nth-child` selector.