# GenePrioritization

The present approach to gene prioritization is based on the computation of similarity of GO profiles between a 'seed' set of genes already linked with a disease and a 'reference' or background set of genes. Similarity measurement is carried out by mSemSim from GOSemSim R package. The ability of classification of the measurments is tested by ranking the genes according to their similarity to the nearest true neighbour (NTN algorithm) and then ckecking the classification performance by ROC (receiver operating curve).
