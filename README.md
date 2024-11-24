# Kryptonite-N

Coursework for Mathematics for Machine Learning (70015) at Imperial College London. 

### General Objective

Inside of the repository inside the directory PaperAndInstructions studends will find the PDF for the mock paper titled `Kryptonite-n: A Simple End to Machine Learning Hype?'. This paper proposes a simple challege dataset which it claims is impossible for modern machine learning models. Students are tasked with writing a response that theoretically discusses and empirically shows that this is not the case, that the dataset can be solved by standard ML approaches. 

### Kryptonite-n

Inside of the Datasets directory, students will find several variants of the Kryptonite-n dataset, namely for (n = 9, 12, 15, 18, 24, 30 and 45). For each variant of the dataset, the Kryptonite-n paper suggests a "success" threshold meaning a model that achieves accuracy above its threshold will be considered to have solved the problem. To check that students have met this criteria they must submit labels for the "hidden-kryptonite-n-X.npy" files. When students submit their code their models labels must be contained in  "hidden-kryptonite-n-y.npy" files in the subdirectory "hiddenlabels". 

### Formatting

The zip file "ImpCMLAuthorPack.zip" contains Latex source code for the formatting instructions pdf. Students are advised to simply place these files in Overleaf in order to stay within the specified formatting. Papers should be between 4-6 pages.

### Directory Introduction

- `./models`: Store the `.keras` file for all n with two different models WDNN and FCNN
- `./hiddenlabels`: Store all the hidden labels for the hidden dataset using WDNN seed=42
- `WDNN.ipynb`: training and testing process of WDNN network
- `FCNN.ipynb`: training and testing process of FCNN network