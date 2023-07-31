# clifford-number
Clifford numbers definition (for any dimension) using SymPy symbolic python library

Any real matrix 4x4 [M] can be represented by a Clifford number [Cl] of 16 dimensions
The Clifford numbers have geometric meaning and they can be used in Physics

The product of two real 4x4 matrices is a new 4x4 matrix, 
It means that the product of two Clifford numbers is another Cliffor number
but we have to calculate 256=16x16 iterations in 4 dimensions for calculating that product.
If we move to extra dimensions, the numbers of operations increases quickly, so
we need a library...

This library allows a symbolic visualization of any clifford number, their sum and their product as well as 
a numeric calculation of all the above.
We should understand that this code is not optimized and
the time for calculation can increase in insane way with few extra dimensions...
