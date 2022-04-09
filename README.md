# building a phylogenetic tree based on multi fasta protein sequences

target protien : Leishmanolysin

Alternative Name(s) : Glycoprotein gp63, Promastigote surface endopeptidase.

Gene : LMLN

it's membrane-bound glycoprotei.

present in the promastigote of various species of Leishmania protozoans that are responsible for the disease leishmaniasis.

Belongs to peptidase family M8.

information from [Expasy](https://enzyme.expasy.org/EC/3.4.24.36).

## steps
* getting Leishmanolysin gene sequence from NCBI
* Blast search for similar gene sequences
* store in /fasta folder
* use MUSCLE for alignment
* construct phylo tree with different distances 

# results 
**phylogenetic tree of different monkey species**
```

                       ______ Theropithecus gelada
    __________________|
  _|                  |__________________________________ Macaca fascicularis
 | |
 | | Callithrix jacchus
_|
 |__ Cebus imitator
 |
 |         , Sapajus apella
 |_________|
           | Saimiri boliviensis
```
