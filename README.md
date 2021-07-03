# allelica-lib Documentation.

For The Example Using The Class.
[Source-Code](https://github.com/4DIngenieria/Allelica).


```diff
For the installation of this library: "pip install Allelica-pkg-Nico.4D"
```

```python

#Example Without Dask

from allelica_lib import parse

parse.process("source.xlsx", "out.tsv")

```

```python

#Example Using The Library Dask

from allelica_lib import parse

parse.process_dask("source.xlsx", "out.tsv", 4) 

#'4' Is The Number of Partitions That The Dask Library Will Use When Running The Process. 

```

```diff
Other requirements:
```
- pip install dask 
- pip install pandas 
- pip install openpyxl