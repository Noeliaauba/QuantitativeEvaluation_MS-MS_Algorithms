# QuantitativeEvaluation_MS-MS_Algorithms
The project entails a quantitative assessment and a comparative analysis of various algorithms with respect to the Tanimoto scores obtained from the structural similarity using a spectra dataset. This work focuses on the evaluation of the Cosine Greedy, Modified Cosine and Spec2vec algorithms on a list of fragments previously filtered to harmonize the signal, allowing us through cross-comparison to calculate the coefficients that indicate the degree of similarity obtained by each algorithm. 
We aim to determine whether these metrics reflect the similarity in a manner consistent with the Tanimoto score as ground truth, so we can determine the accuracy of each algorithm by the RMSE, being spec2Vec the most accurate for smaller bins, but it is less effective for bins larger than 0.8, while the Cosine algorithms provide similar outcomes, but the differences in these results increase with higher bins, so Modified Cosine is slightly better

All the mentioned algorithms belong to the library of matchms, an open-source Python package developed for importing, processing, and comparing MS/MS. The library transforms a massive amount of data, in this case of mass spectra from metabolites into a large processed spectral data enabling the similarity comparisons. 
To employ matchms is necessary to create the appropriate environment to make use of it, following the next steps:

• Install matchms in a new virtual environment on the terminal of our computer with conda.
- With Anaconda Navigator (a software that provides an interface) change the digital 
environment to the created one, in this case“proyecto”, where are installed libraries
for the project such as matplotlib (visualize graphics), numpy (numerical computing),
matchms (mass spectrometry data analysis), rdkit (Obtation of molecules structure),
spec2vec (A machine learning-based algorithm).
• Launch Jupyter Notebook software to elaborate the code that import the data of spectra
and implements the methods for the quantitative evaluation.
