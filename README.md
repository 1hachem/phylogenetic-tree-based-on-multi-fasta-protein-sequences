# building a phylogenetic tree based on multi fasta protein sequences

target protien : Leishmanolysin

Alternative Name(s) : Glycoprotein gp63, Promastigote surface endopeptidase.

Gene : LMLN

it's membrane-bound glycoprotei.

present in the promastigote of various species of Leishmania protozoans that are responsible for the disease leishmaniasis.

Belongs to peptidase family M8.

information from [Expasy](https://enzyme.expasy.org/EC/3.4.24.36).

## steps
1. getting Leishmanolysin gene sequence from NCBI
1. Blast search for similar gene sequences
1. store in /fasta folder
1. use MUSCLE for alignment
1. construct phylo tree with different distances 

# results 
**phylogenetic tree of 6 different monkey species**
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
