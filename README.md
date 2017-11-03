# TCR chain pairing preferences

Inferring interactions and restriction of alpha and beta chain sequences in T-cell receptors

### Content:

**Pairing data from Howie et al.**

``tcr_ab_pairs.txt.gz`` - flat file with TCR alpha and beta sequences that contains

* V and J segment ids. A comma-separated list of segment ids is provided for ambiguous assignments
* CDR3 nucleotide and amino acid sequences
* Sample ID - the id of repertoire a clone was obtained from
* Clone ID - the id of clone. TCR alpha/beta records having the same sample id and clone id are considered paired.

Sequences were re-aligned using MIXCR and filtered from unmapped reads and non-coding TCRs. Only paired records were retained post-filtering.

Amino acid properties:

* [Kidera factors](https://link.springer.com/article/10.1007/BF01025492): ``prop_kidera.txt``
* [Miyazawa-Jernigan matrix](https://www.ncbi.nlm.nih.gov/pubmed/8604144) aka statistical potential: ``prop_mj96t3.txt``