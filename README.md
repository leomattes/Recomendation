# Aplying the recommendation system
This notebook is a part of the project Library recomender system. 
To generet the datases used in this notebook, we have used spiders to colect biblographis registers and users trasactions over many library sites. The bibliograthic registers have been already unificated and associated with a unique identifier class "codObra";

Ever time that the spider find a new transactions, its necessary to convert the local id to the "codObra" id. The last notebook is about row to joing the recomender with a unified register id.

1. SparJoinTable Note book  explains how to use spark to joing to dataset, in the case the unified register with the transaction ones.

2. SparkRecomendetion e Note book  
