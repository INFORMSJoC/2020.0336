SMALL INSTANCES MAT FILES:
The mat files in this folder have TWO matrices:   A and B and the order n
However, it is not clear which of the matrices is the distance matrix.
We now add references and details on the problems here:

---------------------------------------------------------------
%%% chr instances
%%One matrix A is the adjacency matrix of a weighted tree the other B that
%%of a complete graph.  A === F flows;  and  B === D distances
%%https://coral.ise.lehigh.edu/data-sets/qaplib/qaplib-problem-instances-and-solutions/#CB
These are problems 1-11 in quicktest.m
A is typically VERY sparse, while problems 1-3 have ONE distance ZERO.
---------------------------------------------------------------
%%%  els19 instance problem 12 in quicktest.m
  B === F flows;  and  A === D distances  (i.e. roles reversed)
A.N. Elshafei [Elshafei:77]
The data describe the distances of 19 different facilities of a
hospital and the flow of patients between those locations. The
optimal solution was first found by [Mautor:92].
https://coral.ise.lehigh.edu/data-sets/qaplib/qaplib-problem-instances-and-solutions/#El
---------------------------------------------------------------
B. Eschermann and H.J. Wunderlich [EsWu:90]
  A === F flows;  and  B === D distances
Very sparse examples.
These examples stem from an application in computer science, from the testing
of self-testable sequential circuits. The amount of additional hardware
for the testing should be minimized. The optimal solutions are due
to [ClPe:94] (n=16) and
[BrClMaPe:96] (n=32).
---------------------------------------------------------------
