# VxAfee 
## A hypothetical, open source, DIY-able personalized peptide vaccine design against 2019-nCoV. It might be interesting to test this in-vitro against a cell culture to determine what type of response there is using an ELISPOT assay.

## Disclaimer: 
Although it is believed peptide vaccines should be safer when produced correctly than traditional vaccines, synthesizing and using your own vaccine can be deadly or worse if you make a mistake. This design is intended for experienced companies, scientists, or organizations to implement with adequate resources and testing facilities.

## Background
2019-nCoV, is an emerging Coronavirus related to SARS and MERS is currently (as of January 2020). It has a lower lethality rate than SARS but appears to be spreading because symptoms take longer to develop.

## Biology you should already know:
MHC I is the molecule on the surface of all nucleated cells that presents fragments of proteins from inside the cell. When abnormal or non-self protein fragments are shown in the cleft of the MHC-I molecule, these activate CD8+ T cells to destroy the cell. The sequence of the peptides shown on MHC-I molecules is determined (well mainly) by an individual's HLA genes. The most common MHC I HLA gene in the West is HLA A\*02. The MHC II molecule is what APC cells (for example, dendritic cells or macrophages) use to present fragments of proteins found in the extracellular environment in the body. These are used to educate CD4+ helper T-cells against pathogens. The HLA-DR,DQ, or DP genes determine what protein fragments will  be displayed on the MHC-II. You need the MHC-II system activated against viruses because the you need the APC to produce IL-12 which will induce the Th1 pathway. The Th1 immune response is the anti-virus oriented response.

## Peptide vaccines versus other types
Read this article: https://www.frontiersin.org/articles/10.3389/fimmu.2014.00171/full

## Hypothetical possible usage method (don't do it unless you have prior experience and resource and certainly not without checking applicable laws):

1. Select the peptides to use in the vaccine by first determining the HLA-type of the individual to be vaccinated. A person's HLA-type can be found out by DNA testing.
2. Synthesize the MHC I **and** MHC II peptides corresponding the the HLA type of the individual. MHC I and MHC II peptides are needed to ensure a Th1 immune response. This can be done for under $100 with the right equipment. There are many companies that can synthesize peptides cheaply (for research purposes only). Solid Phase Peptide Synthesis (SPPS) can be used make the peptides, an open source SPPS machine design exists.
3. The vaccine must be delivered with a safe adjuvant. Alum, squalene, LPS or a mix thereof may suffice. Adjuvant selection is important in ensuring the optimal immune response. I lean towards Aluminium salts since it has the longest history and safety record.
4. As this is an untested vaccine. It may not even produce immunity against anything, or worse it may have some terrible side effects such as a cytokine storm (although such a thing has never happened for a short peptide vaccine the best of my knowledge). It is also not very clear or known yet how long any induced immunity would last. 

## Ways you can contribute:

1. Add or suggest more HLA types!

2. Next to each peptide sequence add the binding affinity and targeted viral gene .. for example for a peptide sequence in HLA-A\*02 you can add make it like this:
~~~~
Peptide sequence | viral gene name       | binding affinity in nM 
GLMWLSYFI        | membrane glycoprotein | 4.2                    
~~~~

3. Maybe add a dosage calculator ?


## Questions: 
johan@thefunquantum.com
