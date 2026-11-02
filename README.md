# Computational Gastronomy Research | Chronological Research Archive

**Researcher:** Satyam Singh  
**Institution:** Indraprastha Institute of Information Technology Delhi (IIIT-Delhi)  
**Research Area:** Computational Gastronomy, Data Science, Statistical Modelling, Food Pairing and Network Science  
**Research Supervisor:** Prof. Ganesh Bagler  
**Archive Type:** Chronological Research Documentation

---

## About This Repository

This repository maintains a chronological record of my research journey in **Computational Gastronomy**, documenting the research papers studied, discussions, datasets explored, experiments conducted, analytical implementations, findings, limitations and proposed future directions.

The archive is organised meeting-wise to preserve the progression of the research rather than presenting the work as a collection of disconnected projects.

Each meeting folder contains relevant research material, including:

- Research papers and reference literature.
- Meeting-wise research logs.
- Exploratory Data Analysis (EDA) reports.
- Experimental results and statistical analyses.
- Visualisations and interpretations.
- Methodological improvements and revised findings.

The objective is to maintain a traceable record of how the research evolved: from understanding existing computational gastronomy literature to implementing published methodologies on real recipe datasets, identifying limitations and developing more rigorous analytical approaches.

**The folders are arranged chronologically.** Earlier meetings establish the theoretical foundations, while later meetings document practical implementations, refinements and extensions.

---

## Research Overview

Computational Gastronomy applies computational methods, data science, statistical modelling and network analysis to understand food, recipes, ingredients and culinary patterns.

The research documented here explores questions such as:

- How are ingredients distributed across recipes?
- Do ingredient frequencies follow statistical scaling laws?
- How does culinary vocabulary grow as more recipes are observed?
- What relationships exist between recipe size and ingredient information?
- Can ingredient co-occurrence reveal recurring culinary combinations?
- How do culinary patterns differ across cuisines and recipe collections?
- Can network science identify important ingredient relationships?
- How do data quality, ingredient normalization and dataset composition influence statistical conclusions?
- Can recipe-level patterns be connected to flavour chemistry and molecular food pairing?

The work progresses through three broad stages.

### 1. Literature Review and Conceptual Foundations

Studying existing research papers to understand the theoretical and computational foundations of:

- Food pairing and shared flavour compounds.
- Culinary patterns across regional cuisines.
- Recipe generation and computational creativity.
- Ingredient co-occurrence and statistical associations.
- Hierarchical clustering of world cuisines.
- Statistical laws governing culinary design.

### 2. Dataset Exploration and Methodological Reproduction

Applying methodologies and analytical questions from the studied literature to available recipe datasets, including:

- What's Cooking?
- CulinaryDB.
- Extended Recipes datasets.
- CocktailDB.

This stage involves data inspection, preprocessing, ingredient extraction, normalization, exploratory analysis, statistical modelling and visualization.

### 3. Refinement and Research Extensions

Critically evaluating initial findings and improving the analytical methodology through:

- Sensitivity analysis.
- Alternative normalization strategies.
- Statistical robustness checks.
- Distribution fitting.
- Hierarchical clustering.
- Ingredient co-occurrence networks.
- Network backbone extraction.
- Multiple-testing correction.
- Alternative statistical null models.

---

## Repository Structure

```text
CHRONOLOGICAL ORDER/
│
├── README.md
│
├── Meet 0/
│   ├── Analysis of Food Pairing in Regional Cuisines of India.pdf
│   ├── Ratatouille_A_tool_for_Novel_Recipe_Generation.pdf
│   └── Meet-0_logs.txt
│
├── Meet 1/
│   ├── Meet-1_log.txt
│   └── Spices form the basis of food pairing in indian cuisine.pdf
│
├── Meet 2/
│   ├── Data-Driven_Investigations_of_Culinary_Patterns_in_Traditional_Recipes_Across_the_World.pdf
│   └── Meet-2_logs.txt
│
├── Meet 3/
│   ├── Culinary_Patterns_Final_Report.pdf
│   └── Meet-3_log.txt
│
├── Meet 4/
│   ├── culinarydb_eda_report.pdf
│   └── Meet-4_log.txt
│
├── Meet 5/
│   ├── Hierarchical Clustering of World Cuisines.pdf
│   └── Meet_5log.txt
│
├── Meet 6/
│   ├── culinarydb_eda_report.pdf
│   └── Meet-6_log.txt
│
├── Meet 7/
│   ├── recipes_extended_eda_report.pdf
│   └── Meet-7_log.txt
│
├── Meet 8/
│   ├── Universal Statistical laws governing culinary design.pdf
│   └── Meet-8_log.txt
│
├── Meet 9/
│   ├── CocktailDB_EDA_Research_Report-1.pdf
│   └── Meet-9_log.txt
│
└── Meet 10/
    ├── CocktailDB_EDA_Research_Report_Modified.pdf
    └── Meet-10_log.txt
```

*Note: The structure reflects the current archive. File names and capitalization are preserved as they appear in the directory.*

---

# Chronological Research Progression

## Meet 0 – Introduction to Computational Gastronomy

**Focus:** Understanding food pairing, regional cuisines and computational recipe generation.

### Papers Studied

1. *Analysis of Food Pairing in Regional Cuisines of India*
2. *Ratatouille: A Tool for Novel Recipe Generation*

### Key Concepts Explored

- Food pairing hypothesis.
- Ingredient-level flavour profiles.
- Shared flavour compounds between ingredients.
- Regional differences in ingredient combinations.
- Computational approaches to recipe generation.
- LSTM and GPT-2-based recipe generation.
- Evaluation of generated recipes using text-based metrics such as BLEU.

### Research Questions

- How can ingredient compatibility be quantified using shared flavour compounds?
- Does ingredient co-occurrence necessarily imply flavour compatibility?
- Can generated recipes be evaluated using chemical or culinary properties rather than textual similarity alone?
- How might ingredient quantities and compound concentrations influence food-pairing measurements?

### Research Direction

The initial discussions established the need to understand existing food-pairing methodologies before attempting extensions.

One potential research direction was to investigate quantity- or concentration-aware food-pairing measures rather than treating all shared flavour compounds equally.

This was a proposed extension, not an implemented result.

---

## Meet 1 – Food Pairing and Spices in Indian Cuisine

**Focus:** Further exploration of food-pairing mechanisms in Indian cuisine.

### Reference Paper

*Spices form the basis of food pairing in Indian cuisine*

### Key Concepts

- Role of spices in regional culinary combinations.
- Shared flavour compounds.
- Ingredient combinations in traditional Indian recipes.
- Regional culinary patterns.
- Chemical explanations behind ingredient pairing.

### Research Significance

This meeting extended the initial understanding of food pairing by examining the role of spices and their contribution to culinary combinations.

It provided additional context for studying Indian regional food patterns and the relationship between traditional ingredient usage and flavour chemistry.

---

## Meet 2 – Data-Driven Investigation of Culinary Patterns

**Focus:** Understanding large-scale statistical patterns in traditional recipes.

### Reference Paper

*Data-Driven Investigations of Culinary Patterns in Traditional Recipes Across the World* — Singh and Bagler (2018).

### Key Concepts Studied

- CulinaryDB and FlavorDB.
- Ingredient alias normalization.
- Ingredient frequency distributions.
- Recipe-level ingredient co-occurrence.
- Shared flavour compounds.
- Cuisine-level food-pairing tendencies.
- Randomized control models.
- Ingredient-category-based randomization.
- Z-scores and statistical comparison.

### Important Methodological Concepts

The paper investigates food pairing through the overlap of flavour compounds between ingredients.

For ingredients \(i\) and \(j\), shared flavour compounds can be represented as:

\[
N_s(i,j)=|F_i\cap F_j|
\]

where \(F_i\) and \(F_j\) represent their flavour-compound sets.

Recipe-level and cuisine-level aggregation allows food-pairing tendencies to be compared against randomized baselines.

### Research Questions

- How should ingredient aliases be resolved?
- How does ingredient-frequency imbalance affect food-pairing analysis?
- What is the influence of ingredient-category composition?
- How reliable are randomized baselines?
- Can quantity information improve the original food-pairing measure?
- How could cooking transformations affect flavour-compound availability?

### Research Direction

The immediate objective was to move from paper understanding to dataset exploration and reproduction of relevant analyses.

---

## Meet 3 – Culinary Patterns: Initial Data Analysis

**Focus:** Practical investigation of recipe data and culinary patterns.

### Research Material

`Culinary_Patterns_Final_Report.pdf`

### Dataset Exploration

This stage involved practical exploratory analysis of recipe data, including the What's Cooking? dataset.

The analysis focused on:

- Recipe and cuisine distributions.
- Ingredient frequency.
- Recipe-size distributions.
- Ingredient diversity across cuisines.
- Common ingredients.
- Ingredient-category composition.
- Differences in recipe characteristics across cuisine labels.

### Analytical Objectives

- Understand the structure of the dataset.
- Identify missing values and duplicates.
- Examine ingredient popularity.
- Compare recipe sizes across cuisines.
- Generate visualizations for major descriptive patterns.
- Establish the limitations of the dataset relative to CulinaryDB and FlavorDB-based research.

### Important Distinction

What's Cooking? provides recipe ingredients and cuisine labels, but does not provide the complete flavour-compound mappings required to reproduce the chemical food-pairing analysis from the Singh and Bagler paper.

Consequently, ingredient co-occurrence analysis and descriptive EDA should not be confused with shared-flavour-compound analysis.

---

## Meet 4 – CulinaryDB Exploratory Data Analysis

**Focus:** Exploration of the original CulinaryDB dataset.

### Research Material

`culinarydb_eda_report.pdf`

### Dataset

CulinaryDB.

### Research Objectives

- Understand the structure of the original recipe corpus.
- Investigate ingredient distributions and cuisine composition.
- Examine recipe-size characteristics.
- Explore ingredient-category distributions.
- Investigate ingredient popularity.
- Establish a baseline for reproducing relevant analyses from the literature.

### Research Significance

This stage shifted the analysis towards the actual CulinaryDB corpus rather than relying only on an alternative recipe dataset.

The report belongs to the CulinaryDB analysis stage. It should be considered separately from the What's Cooking? analysis and the later extended-recipe dataset.

---

## Meet 5 – Hierarchical Clustering of World Cuisines

**Focus:** Studying hierarchical clustering as a method for understanding culinary similarities and differences.

### Reference Paper

*Hierarchical Clustering of World Cuisines*

### Key Concepts Studied

- Frequent itemset mining.
- FP-Growth.
- Minimum support.
- Ingredient co-occurrence patterns.
- Authenticity-based clustering.
- Cuisine-specific ingredient prevalence.
- Binary feature representations.
- Hierarchical Agglomerative Clustering (HAC).
- Jaccard similarity and distance.
- Cosine similarity.
- Euclidean distance.
- Dendrogram interpretation.
- K-means clustering.
- Elbow method and within-cluster sum of squares.

### Important Questions

- How does FP-Growth differ from Apriori?
- How does the minimum-support threshold affect frequent patterns?
- How can cuisine authenticity be quantified?
- How should positive and negative ingredient prevalence be interpreted?
- Which distance metrics are appropriate for sparse binary ingredient vectors?
- How reliable are clusters obtained from ingredient-only representations?
- How can clustering be validated beyond visual dendrogram inspection?

### Research Significance

This paper introduced a different perspective on culinary patterns.

Rather than focusing only on pairwise flavour overlap, hierarchical clustering investigates similarities between cuisines through their ingredient and other recipe-related feature representations.

It provided the methodological foundation for later clustering experiments.

---

## Meet 6 – Extended CulinaryDB Analysis

**Focus:** Further investigation and refinement of CulinaryDB-based exploratory analysis.

### Research Material

`culinarydb_eda_report.pdf`

### Research Objectives

- Continue the original CulinaryDB analysis.
- Investigate recipe and ingredient distributions.
- Examine cuisine-level composition.
- Explore hierarchical relationships between cuisines.
- Investigate ingredient co-occurrence patterns.
- Examine authenticity-based ingredient representations.
- Generate dendrograms and supporting heatmaps.
- Compare different distance metrics and clustering representations.

### Analytical Components Documented in the Report

- Ingredient-category composition heatmap.
- Recipe-size distributions.
- Ingredient frequency-rank distributions.
- Most frequent ingredients.
- Cuisine-wise recipe counts.
- Unique ingredient vocabulary by cuisine.
- Hierarchical clustering using Euclidean distance.
- Hierarchical clustering using Jaccard distance.
- Authenticity-based clustering.
- Cuisine similarity heatmap.
- K-means elbow analysis.
- Cuisine-specific ingredient distributions.
- Recipe-source analysis.

### Research Significance

The analysis moved beyond basic descriptive EDA towards a more structured investigation of culinary relationships.

The use of different distance measures and authenticity-based features helped examine how representation choices influence the resulting hierarchy.

The limitations of the available CulinaryDB release remained important: the full cooking-process, utensil and flavour-compound information required for every analysis in the reference literature was not available in the supplied CSV data.

---

## Meet 7 – Extended Recipes EDA

**Focus:** Exploring additional recipe attributes beyond ingredients and cuisine.

### Research Material

`recipes_extended_eda_report.pdf`

### Variables Explored

- Recipe names.
- Categories.
- Ratings.
- Votes.
- Preparation time.
- Nutritional information.
- Ingredient counts.

### Analytical Objectives

- Examine missingness across recipe metadata.
- Investigate rating and vote distributions.
- Parse preparation-time information.
- Explore nutritional distributions.
- Examine relationships between popularity, preparation time and ingredient counts.
- Generate descriptive visualizations.

### Key Methodological Considerations

The analysis required handling multiple types of missingness and inconsistent textual representations.

Preparation time and nutrient values needed parsing before statistical analysis.

The report was descriptive in nature and should be distinguished from the later CocktailDB statistical-law implementation.

---

## Meet 8 – Universal Statistical Laws Governing Culinary Design

**Focus:** Studying statistical scaling laws and their application to culinary systems.

### Reference Paper

*Universal Statistical Laws Governing Culinary Design*

### Major Concepts Studied

#### Zipf's Law

Investigates how ingredient frequency changes with ingredient rank.

\[
f(r)\propto r^{-\alpha}
\]

#### Heaps' Law

Investigates vocabulary growth as additional recipes are observed.

\[
V(R)=KR^\beta
\]

#### Menzerath–Altmann Law

Investigates relationships between recipe size and the average information content of its components.

#### Nutrient Distributions

Investigates statistical distributions of nutritional properties and the possible applicability of log-normal and other candidate distributions.

### Research Questions

- Do ingredient frequencies follow a power-law-like distribution?
- How does vocabulary grow with corpus size?
- Does recipe size influence average ingredient information?
- Do nutrient quantities follow log-normal distributions?
- How do culinary statistical laws vary across different recipe domains?
- Which conclusions are sensitive to corpus composition and preprocessing?

### Research Significance

This paper established the theoretical foundation for the subsequent CocktailDB implementation.

The next research stage translated these statistical questions into concrete analyses using a specialized cocktail recipe corpus.

---

## Meet 9 – Initial CocktailDB Implementation

**Focus:** Implementing the statistical framework of *Universal Statistical Laws Governing Culinary Design* on CocktailDB.

### Research Material

`CocktailDB_EDA_Research_Report-1.pdf`

**Original Report Length:** 39 pages.

### Dataset

CocktailDB.

### Main Analytical Components

1. Dataset inspection and data-quality audit.
2. Duplicate detection and record handling.
3. Missing-value analysis.
4. Ingredient extraction and normalization.
5. Recipe-size distributions.
6. Ingredient-frequency analysis.
7. Zipf's law.
8. Heaps' law.
9. Menzerath–Altmann analysis.
10. Nutrient parsing and distribution fitting.
11. Ingredient co-occurrence analysis.
12. Pointwise Mutual Information (PMI).
13. Ingredient network visualization.
14. Spearman correlation analysis.
15. Principal Component Analysis (PCA).

### Statistical and Computational Techniques

- Log-log linear regression.
- Discrete power-law fitting.
- Likelihood-ratio comparisons.
- Random recipe permutations.
- Vocabulary-growth modelling.
- Nonlinear least-squares fitting.
- Information-content calculations.
- Distribution fitting.
- Kolmogorov–Smirnov distances.
- Spearman correlations.
- Bootstrap resampling.
- Standardization and PCA.
- Ingredient co-occurrence matrices.
- PMI-based network construction.

### Initial Findings

The analysis identified concentrated ingredient reuse and sublinear vocabulary growth.

However, the observed statistical patterns did not necessarily reproduce every result from the global recipe corpus.

The cocktail-specific domain, smaller recipe corpus, short recipe sizes, ingredient normalization and incomplete metadata all influenced the results.

### Problems Identified

- Sensitivity of Zipf exponents to rank intervals.
- Dependence on ingredient normalization.
- Short recipe-size range for Menzerath–Altmann analysis.
- Strongly skewed votes, preparation times and nutrient quantities.
- Missing nutritional and category information.
- Source heterogeneity.
- Difficulty interpreting selected ingredient networks.
- Difference between co-occurrence and flavour compatibility.

### Outcome

The 39-page report established the initial implementation and provided the baseline for subsequent refinement.

---

## Meet 10 – CocktailDB Refinement and Extended Statistical Analysis

**Focus:** Improving, validating and extending the initial CocktailDB implementation.

### Research Material

`CocktailDB_EDA_Research_Report_Modified.pdf`

**Modified Report Length:** 66 pages.

The modified report retains the original 39-page report and appends 27 pages of additional analysis and corrections.

### Major Modifications

#### 1. Zipf Robustness

- Tested multiple rank intervals.
- Examined exponent stability.
- Investigated residual curvature.
- Compared normalized and literal-string ingredient representations.
- Added resampling-based sensitivity analysis.

**Important finding:** A single invariant Zipf exponent was not supported across all tested rank intervals.

#### 2. Heaps' Law Visualization

- Added vocabulary-growth boxplots at fixed recipe counts.
- Examined variation across random recipe orderings.
- Added further diagnostics for fitted beta values.

**Important finding:** Vocabulary growth remained sublinear, with the reconstructed mean beta approximately 0.757.

#### 3. Correlation Analysis

- Added numerical annotations to correlation heatmaps.
- Used a diverging colour scale centred at zero.
- Included pairwise sample counts.
- Investigated strong nutrient correlations.
- Examined subgroup differences.

**Important finding:** Strong nutrient correlations and weak popularity-related associations needed different interpretations.

#### 4. Logarithmic Transformations

- Added matched raw and log1p plots.
- Retained zero values.
- Examined extreme observations.
- Improved visualization of heavily skewed variables.

**Important finding:** Log1p improved visualization but did not make every distribution Gaussian or establish log-normality.

#### 5. Hierarchical Ingredient Clustering

- Constructed recipe-membership representations.
- Calculated Jaccard similarity.
- Used average-linkage hierarchical clustering.
- Generated dendrograms and heatmaps.
- Evaluated cuts using silhouette scores.

**Important finding:** The maximum silhouette score was only 0.020 at k = 3, indicating weak global cluster separation.

#### 6. Improved Co-occurrence Network

- Made edge-width mappings explicit.
- Distinguished corpus prevalence from PMI and Jaccard similarity.
- Clarified network thresholds.
- Compared ingredient co-occurrence with different association measures.

#### 7. Full Network and Disparity-Filter Backbone

- Constructed full ingredient co-occurrence graphs.
- Compared normalized and literal-string representations.
- Implemented the disparity filter.
- Examined multiple alpha thresholds.
- Compared OR and AND endpoint rules.
- Applied Benjamini–Hochberg multiple-testing sensitivity.
- Compared against Fisher exact tests.

**Important finding:** The alpha = 0.05 disparity backbone retained only 3.53% of edges, 6.20% of nodes and 31.53% of total pair-incidence weight.

Passing the disparity filter did not automatically establish positive ingredient-pair enrichment.

#### 8. PCA Sensitivity Analysis

- Repeated PCA using log1p-transformed nutrient inputs.
- Used the same complete-case observations and eight nutrient variables.
- Compared explained variance and loadings against the original-scale PCA.

### Additional Methodological References

- Clauset, Shalizi and Newman (2009): *Power-law Distributions in Empirical Data*.
- Serrano, Boguñá and Vespignani (2009): *Extracting the Multiscale Backbone of Complex Weighted Networks*.
- Benjamini and Hochberg (1995): *Controlling the False Discovery Rate: A Practical and Powerful Approach to Multiple Testing*.

### Overall Outcome

This stage shifted the research from initial implementation towards systematic robustness analysis.

Rather than relying only on the appearance of statistical plots and network visualizations, the modified report investigated how conclusions changed with:

- Ingredient representation.
- Rank intervals.
- Transformations.
- Clustering methods.
- Network thresholds.
- Statistical null models.
- Multiple-testing corrections.

The modified report also documented corrections to earlier interpretations and distinguished exploratory findings from statistically established conclusions.

---

# Datasets Referenced Across the Research

| Dataset | Research Context | Main Purpose |
|---|---|---|
| What's Cooking? | Initial culinary EDA | Cuisine-wise recipe and ingredient exploration |
| CulinaryDB | Culinary pattern investigation | Recipe composition, ingredient distributions and clustering |
| Extended Recipes dataset | Extended EDA | Ratings, votes, preparation time, categories and nutrients |
| CocktailDB | Statistical-law implementation | Zipf, Heaps, Menzerath–Altmann, nutrient analysis and ingredient networks |
| FlavorDB | Literature and potential extension | Ingredient flavour-compound information |

**Important:** These datasets are not interchangeable. Their schemas, coverage, sample sizes and available metadata differ. Results from one dataset should not be attributed to another.

---

# Common Research Methodologies

The following methodologies appear across different stages of the archive.

## Data Processing

- Data auditing.
- Missing-value analysis.
- Duplicate detection.
- Text normalization.
- Ingredient extraction.
- Alias resolution.
- Feature construction.
- Numeric parsing.
- Data transformation.

## Exploratory Data Analysis

- Frequency distributions.
- Histograms.
- Boxplots.
- Violin plots.
- Empirical cumulative distribution functions.
- Heatmaps.
- Scatter plots.
- Rank-frequency plots.
- Distribution comparisons.

## Statistical Modelling

- Linear and nonlinear regression.
- Power-law fitting.
- Log-normal and alternative distribution fitting.
- Correlation analysis.
- Bootstrap resampling.
- Permutation analysis.
- Confidence intervals.
- Kolmogorov–Smirnov statistics.
- Fisher exact tests.
- Multiple-testing correction.

## Network Science

- Ingredient co-occurrence matrices.
- Pointwise Mutual Information.
- Weighted ingredient networks.
- Jaccard similarity.
- Hierarchical clustering.
- Disparity-filter backbone extraction.
- Network threshold sensitivity.
- Connected-component analysis.

## Dimensionality Reduction and Clustering

- Standardization.
- Principal Component Analysis.
- Hierarchical Agglomerative Clustering.
- K-means.
- Silhouette evaluation.
- Dendrogram interpretation.

---

# Important Research Principles

The following principles guide the interpretation of the analyses documented in this archive.

1. **Reproducibility:** Data cleaning, normalization rules, model settings and statistical assumptions should be documented.

2. **Dataset awareness:** Findings must be interpreted in the context of the dataset's size, coverage and domain.

3. **Separation of observation and inference:** A visible pattern is not automatically a validated statistical relationship.

4. **Effect size matters:** Statistical significance alone does not establish practical or scientific importance.

5. **Normalization sensitivity:** Ingredient identity decisions can change vocabulary size, frequencies, scaling exponents and network topology.

6. **No unsupported causal claims:** Correlation and co-occurrence do not establish causation or flavour compatibility.

7. **Robustness:** Important conclusions should be tested across reasonable methodological alternatives.

8. **Transparent limitations:** Missing data, source heterogeneity and unavailable variables should be documented rather than hidden.

9. **Historical preservation:** Earlier results should remain traceable when an analysis is revised. Modifications and corrections should be documented explicitly.

10. **Clear distinction between completed and proposed work:** A research direction should not be presented as an implemented result unless it has actually been carried out.

---

# How to Navigate This Repository

The repository is arranged chronologically.

If you want to understand the research progression:

1. Start with **Meet 0–2** for the foundational literature on food pairing and culinary patterns.
2. Explore **Meet 3–7** for dataset exploration, CulinaryDB analysis, hierarchical clustering and extended recipe EDA.
3. Read **Meet 8** to understand the statistical laws that motivated the CocktailDB experiments.
4. Study **Meet 9** for the initial 39-page CocktailDB implementation.
5. Compare it with **Meet 10** for the subsequent 66-page refined report and its additional statistical analyses.

Each meeting log provides the corresponding meeting's research context and progression.

The PDF reports contain the associated analytical documentation, figures and results.

---

# Notes on Reproducibility and Scope

This repository is primarily a **research documentation archive**.

It contains meeting logs, research papers and analytical reports. It should not automatically be treated as a complete executable codebase.

Some reports document their methodology, libraries, preprocessing rules and analytical results without including every original source script or intermediate data file.

Therefore:

- A documented result is not necessarily independently reproducible from the PDF alone.
- Dataset versions and preprocessing decisions must be considered when comparing results.
- Reconstructed analyses should be distinguished from the original implementation.
- Reported numerical values should be traced to their respective report and research stage.
- Proposed future experiments should remain separate from completed work.

For exact implementation details, the corresponding source notebooks, scripts and datasets should be consulted whenever available.

---

# Future Research Directions

Potential directions emerging from the research include:

- Developing a more systematic ingredient ontology.
- Improving ingredient entity resolution and alias handling.
- Integrating recipe datasets with flavour-compound databases.
- Investigating quantity-aware and concentration-aware food-pairing metrics.
- Comparing ingredient co-occurrence with chemical flavour similarity.
- Developing stronger recipe-level statistical null models.
- Investigating cooking processes and ingredient transformations.
- Evaluating the generality of culinary scaling laws across different recipe corpora.
- Exploring richer representations of culinary structure using network science and machine learning.

These are research directions and should not be interpreted as completed contributions unless documented in a subsequent meeting log.

---

## Acknowledgements

This research is conducted under the guidance of **Prof. Ganesh Bagler** at **IIIT-Delhi**, in the area of Computational Gastronomy.

The archive documents the progression of the research through literature study, experimentation, critical evaluation and methodological refinement.

---

*Maintained as a chronological record of research meetings, experiments, findings and future directions.*