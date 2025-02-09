# QuantSeq Analysis Pipeline for the Chimera Project
This GitHub repo holds the [NextFlow](https://www.nextflow.io/) workflow for reproducible analysis of the RNA-seq datasets created in the [Chimera project](https://github.com/DimmestP/chimera_project_manuscript).

[QuantSeq](https://www.nature.com/articles/nmeth.f.376) is an RNA-seq assay that quantifies the 3'UTR isoforms of mRNA transcripts and enables investigations into alternative polyadenylation usage. 

The primary purpose of this experiment is to determine whether the insertion of decay motifs into the 3'UTRs of RPS3 and TSA1 terminators changes the usage of polyA sites.

Data was collected by Weronika in May 2021. Analysis was conducted by Weronika and Sam in May 2021.

# Status
I am still in the process of updating the workflow to function for paired end reads. I have currently updated the following process:
- [x] Fastqc
- [x] cutAdapters
- [x] alignHisat2
- [ ] samViewSort
- [ ] makeBedgraphs
- [ ] renameBamSample
- [ ] countAllmRNA
- [ ] runMultiQC
