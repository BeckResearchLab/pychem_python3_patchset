# pychem_python3_pathset
Set of patches to make PyChem 1.0 Python 3 compatible

<hr>
These patches were generated by doing the following:

* curl -O https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/pychem/pychem-1.0.tar.gz
* tar -xvzf pychem-1.0.tar.gz 
* 2to3 -w -f print pychem-1.0/src/pychem/*.py
* Fix tab on line 280 of pychem-1.0/src/pychem/vector3d.py
* Fix invalid syntax on line 212 of pychem-1.0/src/pychem/geometric.py (remove extra parens)
