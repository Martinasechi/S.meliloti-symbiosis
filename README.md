# S.meliloti-symbiosis
## Master's thesis in Molecular and Applied Biology at the University of Florence

### Systems biology in an ecological context: the model of the nitrogen fixing bacterial symbiont _Sinorhizobium meliloti_

In the last decades the world population has grown very rapidly and so the demand for more food production is increased too. Unfortunately, intensive agriculture has faced some difficulties because of climate changes and the excessive use of chemical nitrogenous fertilizers. A sustainable way for meeting the need of an increased global food demand should be based on a holobiont perspective, viewing crop plants as intimately associated with their microbiome. 

Rhizobia is very important in sustainable agriculture because these microorganisms form symbiotic nitrogen-fixing nodules on leguminous plants, which provides an important source of fixed nitrogen input into the soil ecosystem. The improvement of symbiotic nitrogen fixation is one of the main challenges facing agriculture research. However, manipulating the rhizobium-legume interaction for biotechnological purposes will require an in-depth understanding of the symbiotic interaction, as well as an ability to predict the consequences of genetic changes and environmental perturbations. 

Under these premises, regulation of gene expression is recognized as a key component in the cellular response to the environment and it’s fundamental to understand the bacterial metabolism during symbiosis phases. In this context, the general aim of this thesis has been the analysis of the genotype-by-genotype interactions that could be identified in the initial transcriptional response of rhizobium perception of a host plant. In particular, we have studied the symbiosis between _Sinorhizobium meliloti_ and alfalfa (_Medicago sativa_). 

Sets of genes differentially expressed during the perception of host plant root exudates are analyzed to extract the number and types of genes whose transcriptional differences mostly discriminate among strains and conditions. The fraction of DEGs explaining more than 50% of total variance accounted for ca. 15% of total DEGs, indicating that differences in the response to root exudates among strains are related to a relatively small set of genes. These “highly” discriminating genes suggest that there could be key gene functions which differentiate the rhizobia genotype x plant genotype strain-specific interactions. 

Therefore, this study demonstrated that the initial perception of root exudates by _Sinorhizobium meliloti_ leads to many changes in the rhizobium transcriptome and that these changes are dependent on the genotype x genotype interaction. Also, RNA-sequencing data have been useful to understand which metabolic and biochemistry pathways are more or less expressed during the early phases of the symbiosis. Additionally, from this thesis we can identify which bacterial strain is the most active in transcriptional response and, in future, this could be used to genetically improve _S. meliloti_ bioinoculant for the improvement of legume growth in agricultural ecosystems.





In this repository one can consult the RMarkdown scripts created on Rstudio, which show the various steps and codes used to perform data analysis and graphical representations. In particular, there are the following scripts:

• “Simper_Analysis.Rmd”: about the analysis with the simper function.

• “Id_genes_variability.Rmd”: about the creation of the tables with genes within 50% and 100% of the cumsum.

• "DESeq2_analysis.Rmd”: about the analysis with the contrast function.

• “Clustering_Heatmap_PCA.Rmd”: about the creation of the graphical representations.
