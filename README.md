# Distance-Between-Two-Points-Adapted-by-Neilor-Tonin-URI-Brazil-Timelimit-1
Distance Between Two Points Adapted by Neilor Tonin, URI  Brazil  Timelimit: 1

Timelimit: 1
Read the four values corresponding to the x and y axes of two points in the plane, p1 (x1, y1) and p2 (x2, y2) and calculate the distance between them, showing four decimal places after the comma, according to the formula:

Distance = 

Input
The input file contains two lines of data. The first one contains two double values: x1 y1 and the second one also contains two double values with one digit after the decimal point: x2 y2.

Output
Calculate and print the distance value using the provided formula, with 4 digits after the decimal point.

Input Sample	Output Sample
1.0 7.0
5.0 9.0

4.4721

-2.5 0.4
12.1 7.3

16.1484

2.5 -0.4
-12.2 7.0

16.4575

MY solution

```base
x = input().split(" ")
y = input().split(" ")
x1 = float(x[0])
y1 = float(x[1])
x2 = float(y[0])
y2 = float(y[1])
R = ((x2-x1)**2 + (y2-y1)**2)**(1/2)
print("{:.4f}".format(R))
```

