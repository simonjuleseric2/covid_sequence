# covid_sequence

Analysis of the genetic sequence of the Severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) compared with other viruses from the same familly (Coronaviridae) in diferent hosts.
We will use clustal Omega that use seeded guide trees and HMM profile-profile techniques to generate alignments between multiple sequence. From this alignement a distance matrix can be extracted and used to generate the phylogenetic tree.

**IDs**   
* MN996528 :  H. Sapiens (Human SARS-CoV-2)   
* NC_019843: H.Sapiens (Human MERS-CoV)   
* JQ065048:   anatidae (ducks, geese and swans)   
* NC_028824:  rhinolophus (horseshoe bats)   
* KX38909:    Gallus gallus (Chicken) 


The blue branche represent the human strain (MERS-CoV and SARS-CoV-2)

![](tree.png)

Next we explore different samples of the SARS-CoV-2 taken from several (human) hosts in different countries. The results are displayed on the following phylogenetic tree:
![](tree2.png)

# Dependencies:

* Biopython
* clustral (for alignement)
