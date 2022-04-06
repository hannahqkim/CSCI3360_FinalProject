# CSCI3360_FinalProject

1.0 Short Biological Introduction

	In humans, the fovea is a specialized area of the eye’s retina that is associated with our ability to see fine detail and color. However, the eyes of commonly used amniote models lack foveae. In contrast to many other lab animals, the brown anole lizard, Anolis sagrei, has a fovea. Therefore, my research lab has been one of the first labs to use the brown anole lizard model to study the development of the fovea. 
	One of my previous research projects explored fovea maturation in developing brown anoles that have not been genetically modified. Then, another one of my previous research explored how genetic mutations induced by CRISPR could potentially cause fovea hypoplasia (or the disappearance of the fovea) of hatchling lizards. Due to the similarities in datasets between these two projects, I converged the datasets to see if I could make an interesting data science project that could predict lizard ages and mutation based on characteristics that were gathered from the lizard, the lizard eye, and the fovea. 

1.1 Data Science Project Objective

	My initial objective for this project was to predict different genetic mutations (OCA and TYR vs WT) based on different attributes that were collected for both the wild-type and mutated lizard datasets. There are two reasons why I chose to change my objective (1) due to the unequal distribution of data that represented the mutated group vs the wild-type group and (2) because it was inaccurate for me to compare the wild type dataset directly to the mutated dataset. This comparison was inaccurate because the wild type dataset represented lizards of various ages while the mutated dataset represented lizards that were just hatched from their eggs. Therefore, I decided to change the class labels based on age and mutations. This way, the dataset would be more balanced as seen in these histograms.
