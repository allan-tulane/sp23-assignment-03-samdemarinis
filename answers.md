# CMPS 2200 Assignment 3
## Answers

**Name:**___Sam DeMarinis____


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**

The recurrence for the work is W(n) = W(n-1) + 1
The recurrence for the span is S(n) = S(n-1) + 1

The work and span of the solution is O(n).


- **d.**

The recurrence for work of scan is W(n) = W(n/2) + n
The recurrence for work of reduce is W(n) = 2W(n/2) + 1
The work of the function is O(n)

The recurrence for the span of scan is S(n) = S(n/2) + 1
The recurrence for the span of reduce is S(n) = S(n/2) + 1
The span of the function is O(logn)



- **f.**

The recurrence for the work of the function is W(n) = 2W(n/2) + 1
The work of the function is O(n)
The reccurrence for the work of the function is S(n) = S(n/2) + 1
The span of the function is O(logn)