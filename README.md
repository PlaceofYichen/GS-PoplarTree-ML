# GS_PoplarTree_ML

Learning to build a deep learning model 
based on the data of poplar tree genotypes, 
then to predict the phenotypes for them
by building a Convolutional Neural Network(CNN) model; 
also to provide visualization of the prediction results.

## About poplar data

- Five traits: "Jmax25", "Rdlight25", "Resistwp25", "WUEref" and "Av_Diameter_mm"; 
- Three thresholds: "1e-05", "1e-04" and "0.001".
  
## Procedures

- Firstly, we start with selecting a random trait with a random p-value arbitrarily ('Av_Diameter_mm_0.001.geno' and 'pheno_Av_Diameter_mm_0.001' in this example);
- Step by step, we read the selected data, prepare the data, build the CNN model and train the model, make prediction, and visualize the results;
- Then, we work on the whole dataset, which contains 5 traits and 3 p-values. We apply the model to each traits and compare the results of the traits. Results are visualized, too.
- In addition, we apply another model ('Random Forest' in this example) to the whole dataset and visualize the new results;
- Conlude and discuss.

## Thoughts

- I used the model fitting measure to calculate the loss only instead of accuracy. Improving is on the way.
