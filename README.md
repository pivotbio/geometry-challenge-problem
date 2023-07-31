# Challenge Problem

Given a set of 2-dimensional lines, we would like to find the pair of lines with the smallest intersection angle in the set, and the point in the 2-dimensional plane at which they intersect.

## Inputs

Your program should expect a text file as input with each line in the text file specifying an infinite line, represented by two x-y coordinate pairs that fall on that line in the form "x1,y1;x2,y2". The text file may have any number of lines.

### Example

```
1,1;10,10
1,10;10,1
```

## Output

Your program should output to the console the two intersecting lines in the same format as the input file, the minimum angle at intersection (in degrees), and the point at which they intersect.

### Example

```
Line 1: 1,1;10,10
Line 2: 1,10;10,1
Intersection Angle: 45.004423
Intersection Point: 5,5
```

