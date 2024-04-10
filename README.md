
# NewCYdatabase
Includes CY 3-fold constructed as hypersurface featured Z2 symmetry with 1<h11<8 and 7<h11<13.

Datas could be divided to four part from two points: NID for h11 less than 8, reflection for h11 less than 8, NID for h11 greater than 7, reflection for h11 greater than 7.

# First is the h11.
We compute the CY threefold for all FRST of all favorable polytope for 1<h11<8; And that for part of FRST of some favorable polytope for 7<h11<13.

# Second is the $Z_2$ symmetry
There are two types of symmetry, one introduced by NID involution and one by divisor reflection. We considered all the proper NID case for every ambient space in our work, and all 1-divisor, 2-divisors and 3-divisors reflection for 1<h11<7; All 1-divisor , 15 2-divisors and 15 3-divisors for h11=7; 30 3-divisors for 7<h11<13.



# The entry for each involution will contain the following fields :
•BP not in F: Boundary point not interior to facets of a polytope, corresponding to the basis in ambient space.

•F Intsec: The quadric divisor intersection number of this triangulation, could be used to derive triple intersection number and divisors’ topology quantity.

•INVOL: The involution we choose, tells which divisors exchange.

•KK data: The geometric value of this polytope mentioned in Kreuzer-Skarke database except the vertices matrix, such as h11, h21, Euler number, tells which one of Kreuzer-Skarke database corresponds to our data.

•Linear I: Linear ideal of this triangulation, telling the relations between divisors and independent divisors set.

•NVERTS: The coordinates of vertices of the corresponding Newton polytope.

•OPLANES: The O-plane we finally computed under the choosing involution for this triangulation.

•P symm1: The normal expression of hypersurface, constructed by requiring Z2 symmetry on the original hypersurface and all coefficients are set to be +1.

•Polys: The expression of new divisors in the form of old divisors.

•Q parity: The parity of the system, value 1 means σ∗(J) = J O5/O9 system; value -1 means σ∗(J) = J, O3/O7 system.

•Q str: The expression of Q.

•SR list: The Stanley-Reisner ideal in expression of list.

•Sectors: The sectors of this triangulation, corresponding to SR ideal, are the biggest areas in ambient that SR ideal are satisfied.

•Wmatrix2: The ordinary weight matrix of this triangulation, its’ parameter could be either positive or negative.

•divisors Hodge: The basic geometric Hodge numbers of each divisor.

•Hodge split p n: The value of h11+ and h11−

•invol sr li: Here are non-trivial identical divisors involutions that do not have any impact to the Stanley-Reisner ideal and linear ideal.

•invol sr li tr:The involution that do not have any impact to the Stanley-Reisner ideal, linear ideal and triple intersection number.

•invol triple new:The involution that do not have any impact to the triple intersection number.

•label: Identification numbers of this data.

•ni y: The index of combined divisor in the final divisors basis.

•polyid: The identification numbers of the polytope induce this data.

•rwmat for y: The reduced weight matrix for new divisor.

•rwmat for y notreduced: The original weight matrix for new divisor.

•sr+linear==triple: True if the requirement of Stanley-Reisner ideal and linear

ideal results in same involutions compare to triple intersection number.

•tri id: The index number of triangulation (in a polytope) that induce this data.

•triple inters: The triple intersection number of this data.

# things goes the same for reflection case.
