---
layout: supplement
page_name: supplement
year: 2020
abstract_description: "The three-dimensional conformation of a genome can be profiled using Hi-C, a technique that combines chromatin conformation capture with high-throughput sequencing. However, structural variations often yield features that can be mistaken for chromosomal interactions. Here, we describe a computational method HiNT (Hi-C for copy Number variation and Translocation detection), which detects copy number variations and interchromosomal translocations within Hi-C data with breakpoints at single base-pair resolution. We demonstrate that HiNT outperforms existing methods on both simulated and real data. We also show that Hi-C can supplement whole-genome sequencing in structure variant detection by locating breakpoints in repetitive regions."
link: "./wang-et-al-genome-biology-2020"
link_text: "Wang et al, HiNT: a computational method for detecting copy number variations and translocations from Hi-C data, Genome Biology, 2020"
data_files:
    - title: "BWAIndex"
      nested-files:
        - title: "BWAIndex_hg19.zip"
          src: "BWAIndex_hg19.zip"
          size: "3.2 GB"
        - title: "BWAIndex_hg38.zip"
          src: "BWAIndex_hg38.zip"
          size: "3.2 GB"
        - title: "BWAIndex_mm10.zip"
          src: "BWAIndex_mm10.zip"
          size: "2.8 GB"
    - title: "Background Matrices"
      nested-files:
        - title: "backgroundMatrices_hg19.zip"
          src: "backgroundMatrices_hg19.zip"
          size: "3.7 GB"
        - title: "backgroundMatrices_hg38.zip"
          src: "backgroundMatrices_hg38.zip"
          size: "3.8 GB"
        - title: "backgroundMatrices_mm10.zip"
          src: "backgroundMatrices_mm10.zip"
          size: "3.1 GB"
    - title: "ref Data"
      nested-files:
        - title: "refData_hg19.zip"
          src: "refData_hg19.zip"
          size: "8.9 GB"
        - title: "refData_hg38.zip"
          src: "refData_hg38.zip"
          size: "1.1 GB"
        - title: "refData_mm10.zip"
          src: "refData_mm10.zip"
          size: "840 MB"
    - title: "Test Data"
      src: "testData.zip"
      size: "1.9 GB"
---