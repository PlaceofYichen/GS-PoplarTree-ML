# GS_PoplarTree_ML

Learning to build a deep learning model based on the data of poplar tree genotypes, then to predict the phenotypes for them by building a Convolutional Neural Network(CNN) model; also to provide visualization of the prediction results.

### About poplar data 

- Five traits: "Jmax25", "Rdlight25", "Resistwp25", "WUEref" and "Av_Diameter_mm"; 
- Three thresholds: "1e-05", "1e-04" and "0.001".
  
### Procedures

- Firstly, we start with selecting one trait from the Poplar datasets, because we want to illustrate the general idea of building this model;
- Step by step, we read the selected data, prepare the data, build the CNN model and train the model, make prediction, and visualize the results;
- Then, we move to and work on the whole dataset, which contains 5 traits and 3 p-values. We apply the model to each traits and compare the results of the traits. Results are visualized, too;
- In addition, we apply another model to the whole dataset and visualize the new results;
- Compare the results between two different models;
- Conlude and discuss.

### Results

- Please see "results" folder for more.
![Prediction](/results/prediction/Prediction.png)
![loss_CNN_RF_1E-4](/results/loss/loss_CNN_RF_1E-4.png)
![ValLoss_CNN_RF_1E-3](/results/val_loss/ValLoss_CNN_RF_1E-3.png)

### Conclusions

- The performance on 'Rdilight25' datasets is competently well overall;
- The smaller the p-value, the stronger stability of the model, and the better the relative comprehensive performance.

### Discussions

-  The possible reason for the limitation of the model is that the dataset is not sufficiently large. Theoretically speaking, the model will perform better on a large dataset;
- Models like Linear Regression could also be applied to this problem.

### Notes

- Using the model fitting measure to calculate the loss instead of accuracy. 
- The objective function is to reduce the Mean Square Error (MSE) as much as possible.

## More implementation is on the way.
