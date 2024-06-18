## Tools

### Tools for Virus

#### RVHaplo (2022)  &nbsp; &nbsp; <a href="https://academic.oup.com/bioinformatics/article/38/8/2127/6528317"> <u>Paper</u> </a>  &nbsp; &nbsp; <a href="https://github.com/dhcai21/RVHaplo"> <u>Code</u> </a>
RVHaplo is a tool for reconstructing viral haplotypes from long reads. It takes long reads and a reference genome as input and outputs the genome sequences of haplotypes and their abundance in the sample. It has flexible parameters to control haplotype reconstruction and is suitable for reconstructing highly similar haplotypes (e.g., 99.5% identity).


#### HaploDMF (2022) &nbsp; &nbsp; <a href="https://academic.oup.com/bioinformatics/article/38/24/5360/6780015"> <u>Paper</u> </a>  &nbsp; &nbsp; <a href="https://github.com/dhcai21/HaploDMF"> <u>Code</u> </a>
HaploDMF is a tool for reconstructing viral haplotypes from long reads. By taking long reads and a reference genome as input, it applies a deep matrix factorization model to extract features from the alignment, construct genome sequences of haplotypes, and estimate their abundance in the sample. It requires fewer parameters to be adjusted and is suitable for samples containing many haplotypes.

#### PhaGenus (2023) &nbsp; &nbsp; <a href="https://academic.oup.com/bib/article/24/6/bbad408/7420494?login=true#425616568"> <u>Paper</u> </a>  &nbsp; &nbsp; <a href="https://github.com/jiaojiaoguan/phagenus"> <u>Code</u> </a>
PhaGenus is a learning-based model that conducts genus-level taxonomic classification for phage contigs. It utilizes a powerful transformer model to learn the association between protein clusters and support the classification of up to 508 genera. 


#### ViralM (2024) &nbsp; &nbsp; <a href="https://github.com/ChengPENG-wolf/ViraLM"> Code </a>
A Viral Language Model for virus identification from metagenomic data. 

#### VirBot (2023) &nbsp; &nbsp; <a href="https://doi.org/10.1093/bioinformatics/btad093"> <u>Paper</u> </a>  &nbsp; &nbsp; <a href="https://github.com/GreyGuoweiChen/VirBot"> <u>Code</u> </a>
VirBot is an easy-to-use yet effective tool for identifying RNA viruses from metagenomic data. It leverages a comprehensive collection of RNA viral profile hidden Markov models (pHMMs), enabling the detection of conserved sequences despite the high mutation rates of RNA viruses. Besides the accurate identification, VirBot also provides taxonomic labels of the detected RNA viruses.

#### SegVir (2024) &nbsp; &nbsp; <a href="https://github.com/HubertTang/SegVir"> <u>Code</u> </a>
SegVir is designed to identify and reconstruct complete genomes of segmented RNA viruses from complex metatranscriptomic data. The tool utilizes both close and remote homology searches to detect conserved and divergent viral segments and introduces a new method to evaluate genome completeness based on protein clusters with similar functions.

#### RdRpBin (2022) &nbsp; &nbsp; <a href="https://doi.org/10.1093/bib/bbac011"> <u>Paper</u> </a>  &nbsp; &nbsp; <a href="https://github.com/HubertTang/RdRpBin"> <u>Code</u> </a>
RdRpBin can identify and classify the RNA virus reads in metagenomic data. It uses RNA-dependent RNA polymerase gene as marker gene, and combines alignment-based strategies and graph-based learning models to do viral composition analysis and novel RNA virus discovery in metagenomic data.

### Tools for Plasmid

#### PLASMe (2023) &nbsp; &nbsp; <a href="https://doi.org/10.1093/nar/gkad578"> <u>Paper</u> </a>  &nbsp; &nbsp; <a href="https://github.com/HubertTang/PLASMe"> <u>Code</u> </a>
PLASMe is a tool to identify plasmid contigs from short-read assemblies using the Transformer. PLASMe capitalizes on the strength of alignment and learning-based methods. Closely related plasmids can be easily identified using the alignment component in PLASMe, while diverged plasmids can be predicted using order-specific Transformer models.

### Other tools
#### SourceID-NMF (2024)  &nbsp; &nbsp; <a href="https://github.com/ZiyiHuang0708/SourceID-NMF"> <u>Code</u> </a>
SourceID-NMF is a microbial source tracking tool. It utilizes a non-negative matrix factorization (NMF) algorithm to trace the microbial sources contributing to a target sample. By leveraging taxa abundances in both available sources and the target sample, SourceID-NMF estimates the proportions of these sources present in the target sample.



