# Orientifold Calabi-Yau Threefolds Database
This database is based on: arXiv:. Please cite us!

Using the Kreuzer-Skarke database of 4-dimensional reflexive polytopes, we systematically constructed a new database of orientifold Calabi-Yau threefolds up to $h^{1,1}(X) \leq 12$. Our approach involved a non-trivial $\mathbb{Z}_2$ involution,  with both divisor exchanging and multi-reflections,  acting on the Calabi-Yau manifolds. Each of such proper involutions will result in an orientifold Calabi-Yau manifolds and  $320,377,560$ of them was constructed.  We developed a novel algorithm that significantly reduces the complexity of determining the fixed locus under the involutions, followed by the locations of different types of O-planes. It shows that under the proper involutions one end up with majority the $O3/O7$-planes system and most of them will further admit a naive Type IIB string vacua. Additionally, a new type of free action was determined. We also computed the smoothness and the splitting of Hodge numbers for these  orientifold Calabi-Yau threefolds. 

We will further update our website regularly once we get some new results which are not included in the current database.

# The space given by Github is too small to store our data even we already zip it.
So we upload it to Mega cloud, and you could download it here https://mega.nz/folder/5OsS2LCD#oM1qhX6_F6m2-oA-f0iMmQ
If you have any question or advision, please tell us acicydatabase@163.com



# The entry for each involution will contain the following fields :

-------------------- Divisor Exchange Involutions --------------------

•Polyid: The index numbers labeling the polytope in the database.

•tri_id: The index of triangulation in a given polytope.

•BP_not_in_F: Boundary point not interior to facets of a polytope, corresponding to the vertex in the dual-polytopy $\Delta^{*}$ of the toric ambient space.

•F_Intsec: Quartet intersection number on the ambient space $\mathcal{A}$.

•triple_inters: Triple intersection number on the Calabi-Yau threefolds $X$.

•INVOL: The involution considered in this example.

•KK_data: The geometric data of this polytope mentioned in Kreuzer-Skarke database.

•Linear_I: Linear ideal of the polytopy.

•OPLANES: The locus and type of O-plane, followed by its contribution to D3-tadpole.

      { type of O-plane: [[Fixed locus_1], number of O-plane_1,...]
 
        ...
   
        "tadpole_cancel": True or False,
   
        "value": contribution to D3-tadpole
   
        "[h12p,h12n,smooth]" :  [h21+, h21-, whether P_sym is smooth]
       }

•Polys: Generators of $\mathcal{G}$ for exchange involutions.

•Q_parity: The parity of the holomorhpic three form under involution.

•Q_str: The expression of Q.

•SR_list: The Stanley-Reisner ideal.

•Sectors: Different patches of the polytopy associated to the SR-ideal.

•Wmatrix2:  GLSM weighted matrix $W$ together with the degree of hypersurface.

•divisors_ind: Independent divisors chosen to be the basis of divisor class.

•divisors_Hodge: The Hodge numbers of each divisors.

•Hodge_split_p_n: The value of $h^{1,1}_+$, $h^{1,1}_-$.  

•rwmat_for_y_notreduced: The new weight matrix $\tilde{W}$ after Segre embedding.

-------------------- Reflections --------------------
   
The terminologes for reflections are  almost the same as for divisor exchange involution, except the single, double and triple reflections are labeled as  invol1, invol2 and invol3.
The new type of free action described in Section.\ref{subsec:smoothfree} for multi-reflections are labeled  as "total fixed". The format is as follows:


     [Reflection]: type of O-plane, contribution to D3-tadpole, Fixed Locus

    
•invol1: Type of O-plane, its contribution to D3-tadpole  and the fixed locus  for single reflection.

•invol2: Type of O-plane, its contribution to D3-tadpole  and the fixed locus  for double reflection.

•invol3: Type of O-plane, its contribution to D3-tadpole  and the fixed locus  for triple reflection.
      
•invol3: Type of O-plane, its contribution to D3-tadpole  and the fixed locus  for triple reflection.

 

