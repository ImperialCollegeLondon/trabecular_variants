# Genetic and phenotypic architecture of human myocardial trabeculation

Cardiac trabeculae form a network of muscular strands that line the inner surfaces of the heart. Their development depends on multiscale morphogenetic processes and, while highly conserved across vertebrate evolution, their role in the pathophysiology of the mature heart is not fully understood. We report variant associations across the allele frequency spectrum for trabecular morphology in 47,803 participants of the UK Biobank using fractal dimension analysis of cardiac imaging. We identified an association between trabeculation and rare variants in 56 genes that regulate myocardial contractility and ventricular development. Genome-wide association studies identified 68 novel loci in pathways that regulate sarcomeric function, differentiation of the conduction system, and cell fate determination. We found that trabeculation-associated variants were modifiers of cardiomyopathy phenotypes with opposing effects in hypertrophic and dilated cardiomyopathy. Together, these data provide insights into mechanisms that regulate trabecular development and plasticity, and identify a potential role in modifying monogenic disease expression.

## Content

### 1. [Automated-fractal-analysis](https://github.com/ImperialCollegeLondon/trabecular_variants/tree/main/automated-fractal-analysis)
Automated fractal analysis of segmented cardiac images using pre-existing image segmentations to determine a region of interest within the myocardium. For UK Biobank-specific code, please download https://github.com/UK-Digital-Heart-Project/AutoFD/tree/UKBB via zip.

### 2. [Fractal-analysis-processing](https://github.com/ImperialCollegeLondon/trabecular_variants/tree/main/fractal-analysis-processing)
Code for post-processing of fractal-analysis results including interpolation of FD values to a common number of slices across individuals, summary statistics of FD values per individual and a collection of functions for co-registration of myocardial and trabeculation outlines.

### 3. [Nine-slice-interpolation](https://github.com/ImperialCollegeLondon/trabecular_variants/tree/main/Ninesliceinterpolation)
Code for interpolation used in the paper.

### 4. [Figures](https://github.com/ImperialCollegeLondon/trabecular_variants/tree/main/Figures)
Code for figures and interpolation used in the paper.

## Citation

McGurk KA, Qiao M, Zheng SL, Sau A, Henry A, Ribeiro ALP, Ribeiro AH, Ng FS, Lumbers RT, Bai W, Ware JS, O'Regan DP. Genetic and phenotypic architecture of human myocardial trabeculation. _medRxiv_. 2024 [DOI:10.1101/2024.03.26.24304726](https://doi.org/10.1101/2024.03.26.24304726)
