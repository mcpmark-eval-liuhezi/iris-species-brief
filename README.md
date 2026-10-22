# Iris Species Brief

A short handout segment recomputing every number from the raw source data rather than copying them from a textbook.

## Data source

All figures below were recomputed directly from the raw CSV (150 flowers, four measurement columns in centimetres, one species column) retrieved from the public [mwaskom/seaborn-data](https://github.com/mwaskom/seaborn-data) repository (`iris.csv`, columns `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`).

## Headline table

| Metric | Setosa | Versicolor | Virginica |
| --- | --- | --- | --- |
| Mean petal length (cm) | 1.46 | 4.26 | 5.55 |
| Mean petal width (cm) | 0.25 | 1.33 | 2.03 |
| Mean sepal length (cm) | 5.01 | 5.94 | 6.59 |
| Mean sepal width (cm) | 3.43 | 2.77 | 2.97 |
| Sample count | 50 | 50 | 50 |

## Observations

- **Mean petal length:** setosa 1.46 cm, versicolor 4.26 cm, virginica 5.55 cm — an almost threefold increase from the smallest to the largest species.
- **Largest mean sepal length:** virginica, at 6.59 cm.
- **Sample contribution:** each of the three species contributes exactly 50 flowers (150 in total).
- Every value above was independently recomputed from the retrieved data and agrees with the previous handout; no discrepancies were found.

## Provenance

As verified against the English Wikipedia article on the iris flower data set:

> The Iris flower data set or Fisher's Iris data set is a multivariate data set used and made famous by the British statistician and biologist Ronald Fisher in his 1936 paper *The use of multiple measurements in taxonomic problems* as an example of linear discriminant analysis. It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. Fisher's paper was published in the Annals of Eugenics (today the Annals of Human Genetics).

**Citation:** Fisher, R. A. (1936). "The use of multiple measurements in taxonomic problems." *Annals of Eugenics* (today the *Annals of Human Genetics*). Data collected by Edgar Anderson, who gathered the measurements to quantify the morphologic variation of three related Iris species. Two of the three species were collected in the Gaspé Peninsula. The data set itself consists of 50 samples from each of three species, with four features (sepal length, sepal width, petal length and petal width) measured per sample in centimetres.

## Reference

- "Iris flower data set," *Wikipedia, The Free Encyclopedia* — https://en.wikipedia.org/wiki/Iris_flower_data_set
- Raw data: https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv
