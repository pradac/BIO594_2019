## RNA-Seq and Gene Expression: In-Class Discussion Summary
Cassie Raker and Amy Zyck
****
***Papers Discussed:***

Bernal MA, Donelson JM, Veilleux HD, Ryu T, Munday PL, Ravasi T. 2018. Phenotypic and molecular consequences of stepwise temperature increase across generations in a coral reef fish. _Mol Ecol_. 27:4516–4528. doi: 10.1111/mec.14884

Lohman BK, Stutz WE, Bolnick DI. 2017. Gene expression stasis and plasticity following migration into a foreign environment. _Mol Ecol_. 26:4657–4670. doi: 10.1111/mec.14234

Walworth NG, Lee MD, Hutchins DA, Fu F-X, Webb EA. 2016. Molecular and physiological evidence of genetic assimilation to high CO2 in the marine nitrogen fixer Trichodesmium. _Proc Natl Acad Sci_. 113:E7367–E7374. doi: 10.1073/pnas.1605202113

***Discussion Plan***

In this discussion, we chose to focus on the goals of the different studies as well as the figures. We hoped that this would provide a good overview of different experimental designs and analysis methods, as well as framework to evaluate the strength of each paper’s arguments. We also wanted to be sure to leave time to talk about each paper.


***Lohman et al. 2017***

_Summary_

The discussion began with the Lohman et al. (2017) study. Lohman tested whether plasticity in gene expression would help stickleback migrants adjust to unfamiliar habitats. They conducted a reciprocal transplant experiment where fish native to stream or lake habitats were transplanted into the other habitat. Gene expression profiles were measured to determine if migrants converged on the expression profiles of the adapted native fish. Lohman compared the immunological responses and traits related to parasite defense between the stickleback from each habitat. Their analyses showed that fish transplanted into the different habitat partially converged on the expression profile typical of the adapted natives. They found that lake and stream fish differed in survival rates and parasite infection rates, with lake fish exhibiting a more plastic response to the migration event.

_Figures_

Figure 2: We decided to start by talking about Figure 2, since this was the WGCNA and was a good starting point to understand later figures and concepts. We discussed again that this is a clustering analysis, and that the different colors are purely organizational. Each color category contains genes that are similarly differentially expressed. A WGCNA is very useful in determining the direction of further analysis.

Figure 3: This figure provided a nice Segway from Figure 2, as it is further analysis of the greenyellow module from the WGCNA. Researchers found that the number of alleles were directly related to parasite diversity, and that the MHC allele is related to immunology in sticklebacks.

Figure 4: We then moved on to a larger discussion of phenotypic plasticity, which focused around the reaction norm models in Figure 4. Phenotypic plasticity is the ability of a genotype to express different phenotypes based on the environment. A gene can also be plastic in one population and not in another. Researchers expected to see more fixed responses than plastic responses. Although the reaction norms seem to show plasticity, there was some concern in class that the researchers had not done the proper statistical tests to definitively say whether genes were becoming more fixed. They did find that the origin of the fish explained more gene expression than the destination.

Figure 6: In Figure 6, we discussed LDA analysis. Once we discussed the significance of the density plot on the side, this figure was very helpful. It showed that while both lake and stream fish had a plastic response, fish from the lake were more plastic. In addition, 86% of the difference was explained by fish origin. The density plot especially helped to illustrate the higher amounts of variability in the lake populations. The narrower the distribution, the less variation there is in the population, so that population will likely be less plastic.

Figure 7: The final figure of the paper plots gene by gene convergence. This showed the strength of destination and origin effects in a different way. Points representing upregulated genes are in the upper right quadrant of the graph, and downregulated genes are in the lower left. The red reference line represents a 1:1 ratio of origin and destination effects. The plot shows that origin determines more downregulated genes. Again, this figure shows that origin has more to do with the plasticity in a population than destination.


***Bernal et al. 2018***

_Summary_

The class then briefly discussed the Bernal study. This paper focused on transgenerational plasticity in coral reef fish, as they wanted to see if there was a heritable change between multiple generations. Wild fish were collected and their first-generation (F1) offspring were divided into three seasonally cycling temperature treatments (control, and two elevated temperature treatments).  The second-generation (F2) offspring were then placed into several different temperature treatments, shown in Figure 1. Transgenerational F2 fish were kept in the same environment as their parents. Step F2 fish were introduced to a higher temperature treatment than their parents and the acute F2 fish were introduced to a higher temperature treatment for 7 days. The purpose of the experiment was to see if there was gradual change in transgenerational plasticity in response to the stepwise temperature increase, as this is likely what the fish will experience in the wild. Hepatosomatic index, oxygen consumption, and liver gene expression were compared in the second-generation fish of the multiple treatments. They found that differentially expressed genes were related to metabolic processes and they also found that the liver increased in size in the higher temperature treatments.

_Figures_

Figure 5: We only discussed Figure 5 from the Bernal study. This figure includes heatmaps that show the differentially expressed genes between the Step +3.0°C treatment and Transgenerational +1.5°C (a) and Transgenerational +3.0°C (b). The dark red and blue represent higher and lower expression, respectively. The white represents no changes in expression. These heatmaps cluster genes together based on the similarity of their gene expression pattern. More information on heatmaps can be found [here](https://www.ebi.ac.uk/training/online/course/functional-genomics-ii-common-technologies-and-data-analysis-methods/biological-0).

***Walworth et al. 2016***

_Summary_

This was the most challenging paper that we discussed. Walworth studied multiple populations of the cyanobacteria Trichodesmium and their responses to varying levels of CO2 stress. They put some in a normal CO2 environment, and some in a high CO2 environment. They ran the experiment over five years, which allowed them to study hundreds of generations. While this was technically a transgenerational study, it is hard to pinpoint the generations. Different treatments resulted in different numbers of generations, and they used this information as a proxy for reproductive fitness. They followed this with a reciprocal transplant experiment to test for adaptation. A key difference between this study and the others we discussed was that the researchers were able to sample at a population level instead of an individual level. This meant that they were testing the phenotypic plasticity of the population, as opposed to specific organisms. They found that traits that have been plastic can become fixed under intense stress. The Trichodesmium lost their sensitivity to low CO2 levels after living in a high CO2 environment for many generations.

_Figures_

Figures 2 and 4: We discussed Figures 2 and 4 together, as they were the same type of figure and communicated similar information. These are Venn diagrams showing which genes are downregulated (Figure 2) and upregulated (Figure 4) under different treatments. Specific symbols refer specific genes with known functions (identified using Gene Ontology tools). The class felt that this was a slightly confusing way to communicate reasonably straightforward information. However, it is admittedly difficult to communicate GO enrichment data. We also clarified that the pink bars in Figure 2.b were plotted separately because the scale was so much larger. They represented sigC, which is a transcriptional element (TE) associated with adaptation.

Figure 3.c: We spent some time discussion the genome plot in Figure 3, as many people had not seen one before. Genome plots are not usually used for this type of analysis, but the researchers wanted to be sure to represent the repetitive regions in the Trichodesmium genome. This was unusual since bacterial genomes do not usually have repetitive regions, but there were multiple copies of various transcriptional elements. This provided the class with an opportunity to discuss why it is difficult to assemble a genome with repetitive elements. It is difficult to match terms and sequences when there are multiple instances of each gene. We then discussed the organization of the plot, beginning with Tracks 1 and 2. These both showed the location of TE copies in the genome, but on opposite strands. The two strands mostly overlapped. Track 3 contained the labels for the TEs. Track 4 contained lines pointing to where the genes actually are. More connecting lines means more copies of that gene.
