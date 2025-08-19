# SC-Genomics
This is a repo that contains relevant info regarding single-cell DNA (exome and whole genome) sequencing computational analysis and interpretation, including protocols, pipelines, peak calling algorithms, benchmarking articles, and applications of these techniques.

The specific focus is on single-cell cancer genomics.

## Early Work

### Whole-genome molecular haplotyping of single cells
H Christina Fan, Jianbin Wang, Anastasia Potanina, & Stephen R Quake. _Nature Biotechnology_ (2011). https://doi.org/10.1038/nbt.1739

This was the first demonstration of single-cell haplotyping on cell-lines and cells from human blood, using a genome-wide SNP array. This method set the stage for single-cell genomics and microfluidic-based single cell sequencing.

### Tumour evolution inferred by single-cell sequencing
Nicholas Navin, et al. Tumour evolution inferred by single-cell sequencing. _Nature_ (2011). https://doi.org/10.1038/nature09807

This was the first demonstration of single-cell DNA sequencing across the whole genome from a human tumor, and was used to reconstruct and model the evolutionary history of the tumor. The authors were able to identify distinct subpopulations that likely gave rise to clonal expansions with divergent structural variations containing potent oncogenes. 

### Genome-wide copy number analysis of single cells (_Nature Protocols_)
Timour Baslan, et al. Genome-wide copy number analysis of single cells. _Nature Protocols_ (2012). https://doi.org/10.1038/nprot.2012.039

This is an accompanying detailed protocol based on the previous paper. 

### MALBAC method for single-cell DNA sequencing
Chenghang Zong, Sijia Lu, Alec R. Chapman, and X. Sunney Xie. Genome-Wide Detection of Single-Nucleotide and Copy-Number Variations of a Single Human Cell. _Science_ (2012). https://doi.org/10.1126/science.1229164

### Copy number analysis in circulating tumor cells
Xiaohui Ni, Minglei Zhuo, Zhe Su, Jianchun Duan, Yan Gao, Zhijie Wang, Chenghang Zong, et al. Reproducible copy number variation patterns among single circulating tumor cells of lung cancer patients. _PNAS_ (2013). https://doi.org/10.1073/pnas.1320659110

## Later Papers
Chongyi Chen, Dong Xing, Longzhi Tan, Heng Li, Guangyu Zhou, Lei Huang, and X. Sunney Xie. Single-cell whole-genome analyses by Linear Amplification via Transposon Insertion (LIANTI). _Science_ (2017). https://doi.org/10.1126/science.aak9787

Anna K. Casasent et al. Multiclonal Invasion in Breast Tumors Identified by Topographic Single Cell Sequencing. _Cell_ (2018). https://doi.org/10.1016/j.cell.2017.12.007

### Acoustic Cell Tagmentation (ACT) method; _Nature_, 2021:
Darlan C. Minussi, Michael D. Nicholson, Hanghui Ye, et al. Breast tumours maintain a reservoir of subclonal diversity during expansion. _Nature_ (2021). https://doi.org/10.1038/s41586-021-03357-x

And accompanying computational methods manuscript (pre-print), copyKit:

Darlan Conterno Minussi, et al. Resolving clonal substructure from single cell genomic data using CopyKit. bioRxiv (2022). https://doi.org/10.1101/2022.03.09.483497

GitHub Repo for copyKit: https://github.com/navinlabcode/copykit

### Cancer Grand Challenges IMAXT Paper; _Nature_, 2022:
Tyler Funnell, Ciara H. O’Flanagan, Marc J. Williams, et al. Single-cell genomic variation induced by mutational processes in cancer. _Nature_ (2022). https://doi.org/10.1038/s41586-022-05249-0

Kaile Wang, Tapsi Kumar, et al. Archival single-cell genomics reveals persistent subclones during DCIS progression. _Cell_ (2023). https://doi.org/10.1016/j.cell.2023.07.024

Yiyun Lin, Junke Wang, et al. Normal breast tissues harbour rare populations of aneuploid epithelial cells. _Nature_ (2024). https://doi.org/10.1038/s41586-024-08129-x

## Good Review Articles on this topic:
Nicholas Navin. Cancer genomics: one cell at a time. _Genome Biology_ (2014). https://doi.org/10.1186/s13059-014-0452-9

Nicholas Navin. The first five years of single-cell cancer genomics and beyond. _Genome Research_ (2015). [DOI: 10.1101/gr.191098.115](https://genome.cshlp.org/content/25/10/1499.full)

Alexander Davis, Ruli Gao, & Nicholas Navin. Tumor evolution: Linear, branching, neutral or punctuated?. Biochimica et Biophysica Acta (BBA) - Reviews on Cancer (2017). https://doi.org/10.1016/j.bbcan.2017.01.003

Anna S. Nam, Ronan Chaligne & Dan A. Landau. Integrating genetic and non-genetic determinants of cancer evolution by single-cell multi-omics. _Nature Reviews Genetics_ (2021). https://doi.org/10.1038/s41576-020-0265-5

## Other modalities (scATAC-seq, scHi-C, scCUT&Tag, etc.) for cancer genomics and tumor evolution

### Single-cell CUT&Tag for cancer genomics and tumor evolution
Derek H. Janssens, et al. Automated CUT&Tag profiling of chromatin heterogeneity in mixed-lineage leukemia. _Nature Genetics_ (2021). https://doi.org/10.1038/s41588-021-00941-9

Steven J. Wu, Scott N. Furlan, et al. Single-cell CUT&Tag analysis of chromatin modifications in differentiation and tumor progression. _Nature Biotechnology_ (2021). https://doi.org/10.1038/s41587-021-00865-z

### Single-cell ATAC-seq for cancer genomics and tumor evolution
Kaile Wang, Zhenna Xiao, Yun Yan, et al. Simple oligonucleotide-based multiplexing of single-cell chromatin accessibility. _Molecular Cell_ (2021). https://doi.org/10.1016/j.molcel.2021.09.026

### Single-cell Hi-C / contact maps for cancer genomics and tumor evolution
Xiaotao Wang, Yu Luan, & Feng Yue. EagleC: A deep-learning framework for detecting a full range of structural variations from bulk and single-cell contact maps. _Science Advances_ (2022). https://doi.org/10.1126/sciadv.abn9215

Lei Chang, Yang Xie, et al. Droplet Hi-C enables scalable, single-cell profiling of chromatin architecture in heterogeneous tissues. _Nature Biotechnology_ (2024). https://doi.org/10.1038/s41587-024-02447-1

### Single-cell and spatial RNA-seq for inferring copy number alterations and tumor evolution
Ruli Gao, et al. Delineating copy number and clonal substructure in human tumors from single-cell transcriptomes. _Nature Biotechnology_ (2021). https://doi.org/10.1038/s41587-020-00795-2

Diane Zhang, et al. SlideCNA: spatial copy number alteration detection from Slide-seq-like spatial transcriptomics data. _Genome Biology_ (2025). https://doi.org/10.1186/s13059-025-03573-y

### Single-cell methylation profiling for inferring copy number alterations and tumor evolution
Ruth V. Nichols, Lauren E. Rylaarsdam, et al. Atlas-scale single-cell DNA methylation profiling with sciMETv3. _Cell Genomics_ (2025). https://doi.org/10.1016/j.xgen.2024.100726

