# computing_flag_Dressian
We compute the 4 step flag Dressian, and its positive part, using the main results of the paper "Generalized Permutahedra and Positive Flag Dresians". Note: We are in fact computing an embedding of the flag Dressian as the support of the subfan of the secondary fan that induces subdivisions of the 3 dimensional permutahedron into generalized permutahedra.

Description of repository contents:

1. computing_flag_dressian_4.ipynb : explicit step by step computation of 4 step flag Dressian, and its positive part. We use the tropical and linear conditions 
from the main theorems of the paper. There are also several examples of permutahedral subdivisions of the 4-permutahedron.

2. flag_dressian_4.poly : the flag Dressian FlDr(4) saved as a polymake object.

3. positive_flag_dressian_4.poly : positive part of flag Dressian. The support of this fan consists of height functions that subdivide the 4 permuthaedron into cells that are Bruhat interval polytopes.
