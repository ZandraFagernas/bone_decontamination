Here you can find R Notebooks used for the manuscript "Cleaning the Dead: Optimized decontamination enhances palaeoproteomic analyses of a Pleistocene hominin tooth from Khudji, Tajikistan" by Fagernäs et al (DOI TBA).

**Code and data  files**

You will find two Rmd files in this repository:
 - bone_decontamination_cleaned_v4.Rmd contains all code for the decontamination method comparison, section 3.1 in the manuscript.
 - khudji_decontamination_cleaned_v3.Rmd contains all the code for the analysis of the Khudji dentine proteome, section 3.2 in the manuscript.

You can also here find the following file:
- identified_contaminants.txt which outlines which contaminants are present and what they are.

Supplementary materials in the manuscript contain metadata (Supplementary Data 1). All raw data and MaxQuant search results have been deposited to the ProteomeXchange Consortium via the PRIDE  partner repository with the dataset identifier PXD050393 (Equus sp.), and PXD050370 and 10.6019/PXD050370 (Homo sp.). These datasets will be made public upon publication of the manuscript. 

**Software**

The code was built using R v.4.3.0 (R Core Team, 2023).

The following R packages are required to execute the code:
- tidyverse v.2.0.0 (Wickham et al., 2019)
- janitor v.2.2.0 (Firke, 2023)
- ggpubr v.0.6.0 (Kassambara, 2023)
- car v.3.1.2 (Fox & Weisberg, 2019)
- vegan v.2.6.4 (Oksanen et al., 2022)
- BioStrings v.2.61.1 (Pagès et al., 2023)
- ape v.5.7.1 (Paradis & Schliep, 2019)
- Peptides v.2.4.6 (Osorio, 2015)
- Hmisc v.5.1.1 (Harrell, 2023)
- MASS v.7.3.58.4 (Venables & Ripley, 2002)
- MetBrewer v.0.2.0 (Mills, 2022)

To produce the files that are analysed here, the following software/code was used:
- MaxQuant v.2.1.3.0 (Cox & Mann, 2008)
- PEAKS v.11 (Zhang et al., 2012)
- deamidation.py (Mackie et al., 2018)

**References:**

Cox, J., & Mann, M. (2008). MaxQuant enables high peptide identification rates, individualized p.p.b.-range mass accuracies and proteome-wide protein quantification. Nature Biotechnology, 26(12), 1367–1372.

Firke, S. (2023). janitor: Simple Tools for Examining and Cleaning Dirty Data. 

Fox, J., & Weisberg, S. (2019). An R Companion to Applied Regression, Third Edition. Sage.

Harrell, F. E., Jr. (2023). Hmisc: Harrell Miscellaneous. 

Kassambara, A. (2023). ggpubr: “ggplot2” Based Publication Ready Plots. 

Mackie, M., Rüther, P., Samodova, D., Di Gianvincenzo, F., Granzotto, C., Lyon, D., Peggie, D. A., Howard, H., Harrison, L., Jensen, L. J., Olsen, J. V., & Cappellini, E. (2018). Palaeoproteomic Profiling of Conservation Layers on a 14th Century Italian Wall Painting. Angewandte Chemie, 57(25), 7369–7374.

Mills, B. R. (2022). MetBrewer: Color Palettes Inspired by Works at the Metropolitan Museum of Art. 

Oksanen, J., Simpson, G. L., Blanchet, F. G., Kindt, R., Legendre, P., Minchin, P. R., O’Hara, R. B., Solymos, P., Stevens, M. H. H., Szoecs, E., Wagner, H., Barbour, M., Bedward, M., Bolker, B., Borcard, D., Carvalho, G., Chirico, M., De Caceres, M., Durand, S., … Weedon, J. (2022). vegan: Community Ecology Package. 

Osorio, D. (2015). Peptides: A package for data mining of antimicrobial peptides. The R Journal. 

R Core Team. (2023). R: A Language and Environment for Statistical Computing. R Foundation for Statistical Computing. 

Pagès, H., Aboyoun, P., Gentleman, R., & DebRoy, S. (2023). Biostrings: Efficient manipulation of biological strings. 

Paradis, E., & Schliep, K. (2019). ape 5.0: an environment for modern phylogenetics and evolutionary analyses in R. Bioinformatics, 35, 526–528.

Venables, W. N., & Ripley, B. D. (2002). Modern Applied Statistics with S (Fourth). Springer. 

Wickham, H., Averick, M., Bryan, J., Chang, W., McGowan, L. D., François, R., Grolemund, G., Hayes, A., Henry, L., Hester, J., Kuhn, M., Pedersen, T. L., Miller, E., Bache, S. M., Müller, K., Ooms, J., Robinson, D., Seidel, D. P., Spinu, V., … Yutani, H. (2019). Welcome to the tidyverse. Journal of Open Source Software, 4(43) 1686. 

Zhang, J., Xin, L., Shan, B., Chen, W., Xie, M., Yuen, D., Zhang, W., Zhang, Z., Lajoie, G. A., & Ma, B. (2012). PEAKS DB: de novo sequencing assisted database search for sensitive and accurate peptide identification. Molecular & Cellular Proteomics: MCP, 11(4), M111.010587.

**License **

CC-BY 4.0
