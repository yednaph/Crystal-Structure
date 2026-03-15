In Quantum Espresso, the structure information is provided by ibrav number,
and corresponding celldm values or lattice constants and cosines of angle between the axes.
It is also possible to set ibrav=0 and provide lattice vectors in CELL_PARAMETERS.

IMPORTANT POINT
When set ibrav=0, the lattice vectors must be provided with sufficiently large number of decimal accuracy,
otherwise symmetry detection may fail and strange problems may arrise.

ibrav numbers for different lattice types:

<b>ibrav	      Lattice type</b>
1	          Simple cubic
2	          Face centered cubic
3,-3	      Body centered cubic
4	          Hexagonal
5	          Trigonal with c as 3-fold axis
-5	        Trigonal with <111> as 3-fold axis
6	          Simple tetragonal
7	          Centered tetragonal
8	          Simple orthorhombic
9,-9,91	    One-face centered orthorhombic
10	        Face centered orthorhombic
11	        Body centered orthorhombic
12	        Simple monoclinic, c unique
-12	        Simple monoclinic, b unique
13	        One base centered monoclinic, c unique
-13	        One base centered monoclinic, b unique
14	        Triclinic
