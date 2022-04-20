# Gerber_et_al_2022: scRNAseq Analysis of HSPCs in WT and PyMT mice


This github project contains the link to the raw data, the filtered data and the software to support the publication of Gerber et al. Within this repository you will find R scripts and data to analyse 10x scRNAseq experiments. We also provide supporting material including lists of differentially expressed genes and pathways. Any queries about the software or supporting documents can be made to Jason Cosgrove (jason.cosgrove@curie.fr)

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


In this study we wish to determine if breast cancer can impact on myeloid cell development in the bone marrow. For that purpose we are using the spontaneous breast cancer mouse model MMTV-PyMT. MMTV-PyMT is spontaneous mouse model of breast cancer. Genetically engineered female mice express the tumor oncogene PyMT under the MMTV promoter, leading to progressive (hyperplasia, adenoma, early and late carcinoma) tumor development in mammary glands. In the C57/Bl6 background, female developed palpable tumor around the age of 14w, and have a maximal tumor burden between the age of 18w to 25w old. Our preliminary results show an increase #hematopoiesis in tumor bearing mice with elevated numbers of early hematopoietic progenitors in the bone marrow of tumor bearing mice compared to littermate #control. In periphery (blood, spleen, tumor) we also find increased numbers of myeloid cells (monocyte, granulocytes, dendritic cells). Taken together these data suggest that cancer development impact on myelopoiesis in the bone marrow leading to increase production of myeloid cells in the periphery.To better understand the impact of cancer on hematopoiesis we are planning to perform single cell RNA sequencing on the HSPCs on tumor bearing mice compared to tumor free mice.

Cells from each condition were sequenced on the 10X Genomics platform, a droplet based approach to isolate single-cells for sequencing. As described in AlJahani et al (2018): "Droplet-based single-cell gene expression approaches use microfluidic chips to isolate single cells along with single beads in oil-encapsulated droplets, using microfluidics to bring oil, beads, and cell suspensions together in such a way that each droplet contains at most a single cell.20 The beads are coated with DNA oligos that are composed of a poly(T) tail at the 3′ end for the capture of cellular mRNAs, and at the 5′ end both a cell barcode that is identical for every oligo coating an individual bead and a library of individual unique molecular identifier (UMI) barcodes of high diversity, each UMI different for every oligo on the bead. The transcripts from each individual cell captured and labeled by the DNA oligos attached to a bead within the droplets are reverse transcribed, amplified with PCR, and sequenced using a high-throughput platform, after breaking and pooling droplet contents. The resulting sequences are aligned to a reference genome in order to annotate each transcript with its gene name. The cell barcodes on the aligned sequences allow for the computational linking of each gene transcript to its cell of origin. The number of copies of individual gene transcripts expressed in each individual cell is tallied using the UMIs, allowing the assembly of digital gene expression matrices (DGEs), which are tables of cell barcodes and gene counts."
  
 MMTV: mouse mammary tumor virus
 PyMT: Polyomavirus middle T antigen
