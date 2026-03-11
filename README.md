Crystallographic Information File (.CIF) format

For a variety of materials, CIF files can be downloaded from the various databases, such as:
https://www.crystallography.net/cod/

https://next-gen.materialsproject.org/

https://www.ccdc.cam.ac.uk/

https://publcif.iucr.org/publcif.php

https://aflowlib.org/search/

Also, by using some tools such as VESTA, cif2cell, QE Input generator

Vesta is available for download here(https://jp-minerals.org/vesta/en/). Crystal structure visualization, creation, modification in supercells, etc, can be done.

By using the cif2cell package, previously generated/downloaded CIF files can be converted to QE input files.

This package can be installed by sudo pip3 install cif2cell (apply this command from the installation directory).

echo ‘export PATH=”/home/your-user-name/.local/lib/python3.8/site-packages/:$PATH”‘ >> ~/.bashrc

Now use cif2cell Si.cif -p quantum-espresso -o Si.in, where Si.cif is the previously generated/downloaded CIF and Si.in is the newly generated QE input file.

You can also use the QE Input generator, such as ​
https://qeinputgenerator.materialscloud.io to generate PWscf input files

https://seekpath.materialscloud.io/ for the k-path visualization and generation
