# Structure-similarity-as-a-guide-to-predict-drug-enzyme-binding
Based on their KEGG identifiers 1475 different chemical structures of human metabolites were obtained. Chemical structures were also obtained for every drug in DrugBank [15] and Tanimoto scores using FP4 fingerprints were calculated for each metabolite-drug pair using OpenBabel software [18]. A set of 4231 drug-metabolite pairs with Tanimoto scores higher than 0.9 were extracted for further analysis (excluding the trivial cases in which the DrugBank compound and the metabolite were identical). EC numbers for the targets of each drug and for the enzymes associated to each metabolite were extracted from DrugBank and KEGG respectively. In 2817 cases both the drug and the metabolite had at least one target reported. For 644 pairs at least one of the targets was shared among the drug and the metabolite, which is 23% of the total pairs with Tanimoto scores over 0.9.
