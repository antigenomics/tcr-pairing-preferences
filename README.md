# tcr-pairing-preferences
TCR chain pairing preferences: interactions and restriction of alpha and beta chain sequences in T-cell receptors

### Content:

**Pairing data from Howie et al.**

``tcr_ab_pairs.txt.gz`` - flat file with TCR alpha and beta sequences that contains

* V and J segment ids. A comma-separated list of segment ids is provided for ambiguous assignments
* CDR3 nucleotide and amino acid sequences
* Sample ID - the id of repertoire a clone was obtained from
* Clone ID - the id of clone. TCR alpha/beta records having the same sample id and clone id are considered paired.

Sequences were re-aligned using MIXCR and filtered from unmapped reads and non-coding TCRs. Only paired records were retained post-filtering.
