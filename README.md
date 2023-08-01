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

Your program should output to the console the two intersecting lines that have the smallest angle between them (as compared to all other line intersections in the set) in the same format as the input file, the minimum angle at intersection (in degrees), and the point at which they intersect.

### Example

```
Line 1: 1,1;10,10
Line 2: 1,10;10,1
Intersection Angle: 45.0
Intersection Point: 5.5,5.5
```

## Considerations

## Rubric

* Readability: variables, functions, and classes are named clearly indicating their purpose
* Correctness: the code solves the problem as described by the requirements
* Testing: appropriate tests are included to ensure that the code works correctly
* Repeatability: the code includes instructions and dependency expectations for us to run it locally on our side.

## Timing

We believe this problem should take between one and four hours to complete. If you find yourself at the four hour mark and have not finished, stop and send in what you have.

## Submission

Send a .zip file or a link to your git repository to rsmith@pivotbio.com by at least the night before your review session. We will review the code and test a number of edge cases before the session. Good luck!