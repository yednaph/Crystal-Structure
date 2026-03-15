In Quantum Espresso, the structure information is provided by ibrav number,
and corresponding celldm values or lattice constants and cosines of angle between the axes.
It is also possible to set ibrav=0 and provide lattice vectors in CELL_PARAMETERS.

IMPORTANT POINT
When set ibrav=0, the lattice vectors must be provided with sufficiently large number of decimal accuracy,
otherwise symmetry detection may fail and strange problems may arrise.

ibrav numbers for different lattice types:

<p><b>ibrav	      Lattice type</b></p>
<p>1	          Simple cubic</p>
<p>2	          Face centered cubic</p>
<p>3,-3	      Body centered cubic</p>
<p>4	          Hexagonal</p>
<p>5	          Trigonal with c as 3-fold axis</p>
<p>-5	        Trigonal with <111> as 3-fold axis</p>
<p>6	          Simple tetragonal</p>
<p>7	          Centered tetragonal</p>
<p>8	          Simple orthorhombic</p>
<p>9,-9,91	    One-face centered orthorhombic</p>
<p>10	        Face centered orthorhombic</p>
<p>11	        Body centered orthorhombic</p>
<p>12	        Simple monoclinic, c unique</p>
<p>-12	        Simple monoclinic, b unique</p>
<p>13	        One base centered monoclinic, c unique</p>
-13	        One base centered monoclinic, b unique
14	        Triclinic
