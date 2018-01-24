# JS-Best-Practices

# This document lists the must have JS practices

1.	Variables are not put at root scope or there are no implicit variables.
2.	There are no unused variables
3.	There are no hardcoded strings
4.	Functions are made pure as far as possible.
5.	Keep the return statement to minimal (possibly only a single one)
6.	Caching of jQuery selectors if used more than once.
7.	Events should not be attached more than once.
8.	Cyclomatic complexity should be less and not be more than 10 in the worst case.
9.	Callback statements are declared in a separate function
10.	All ajax data are handled with type check of any available property
11.	JQuery operations are chained where ever possible.
12.	Similar jQuery operations are combined
13.	Make sure there are no more than two level of event target delegation in case of binding events.
14.	Avoid event binding on document load which are based on another event 
15.	Apply event name spacing where ever required. 
16.	Do not mix utilities and module codes. 
17.	Avoid wild card jQuery selectors. Prefer to be inside a scope of a component.
18.	Clean any function without body – remove them altogether.
19.	Follow consistent naming convention.
20.	Avoid too much shortening of code ( one liners)
21.	Where ever logging is required, make sure to do that by single global method with meaningful information.
22.	Avoid jQuery selectors by attributes – they are 100 times slower
23.	Make your code as flat as possible. Nested code is difficult to comprehend and debug.
24.	Avoid $.each where ever possible.
25.	Split the JS into logical meaningful files, if it contains so much of code.
26.	Keep the declaration and execution of functions in different scope block.
27.	Utility methods should be pure functions.
28.	Cache long object chains in variables to improve performance.
29.	Avoid applying style in Javascript, make use of classes.
30.	Avoid ids wherever possible.
31.	Avoid names/ids/class names like myDiv, test – give a meaningful name.
32.	Prefer revealing pattern to adding methods by this.
33.	Make sure to lint your files ( add JSHint plugin to your editor)
34.	Avoid unnecessary variables
