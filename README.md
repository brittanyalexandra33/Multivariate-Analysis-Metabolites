## Multivariate-Analysis-Metabolites

## Objective
This project involves analyzing blood metabolite measurements following the consumption of whey protein beverages in a crossover design study. The data consists of measurements taken at different time points for three different meals (control, meal B, and meal C) containing varying amounts of whey protein. The focus is on 52 metabolites that showed significant differences across the meals.

## Data 
The file “metab-selected.csv” contains measurements of selected blood metabolites following consumption of a whey protein beverages.
All deatils can be found in Joblin-Mills et al, Frontiers in Clinical Diabetes 3: 10.3389/fcdhc.2022.980856.

## Key Contributions:

* Conducted principal components analysis (PCA) on the log-transformed and scaled data to identify patterns and variability in the metabolite abundance.
* Generated a scree plot to visualize the proportion of variability explained by each principal component. The first component accounted for 29.4% of the variability, while the second component accounted for 9.5%.
* Examined the correlation between the first principal component score and the original metabolite variables. Identified metabolites with strong positive correlations, including L.Lysine, X1.Methylpyrrolinium, Pipecolic.acid_2, L.Tyrosine, and more.
* Assessed the representation of essential amino acids affected by the consumed meals, highlighting the well-represented amino acids (Lysine, Isoleucine, Methionine, and Tryptophan) and partially represented amino acids (Histidine, Leucine, Phenylalanine).
* Created visualizations of the first principal component score against time, showing distinct patterns for each meal and allowing for a comparison of the response to whey protein consumption.
* Detected an outlier in the control meal at time 0, identified as participant LD4227.
* Plotted the time course of the first principal component score for each meal, observing delayed response patterns in participant LD4227 for meals B and C.

## Why the project is useful
* In my project, I employed various statistical techniques such as principal component analysis (PCA), correlation analysis, data visualization, and outlier identification to meticulously analyze the data.

* The project involved applying statistical techniques like principal component analysis (PCA), correlation analysis, data visualization, and outlier identification, which allowed for a thorough analysis of the data.

* The project provided an opportunity to apply my interest in nutrition to investigate how whey protein intake affects blood metabolites, contributing to a broader understanding of nutrition and health.
