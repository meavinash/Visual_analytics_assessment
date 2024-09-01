**Synthetic Classifiers Analysis**

**Overview**
This project provides a detailed analysis of two classifiers trained on a synthetic dataset of images. The dataset consists of 10,000 images—7,000 dog images and 3,000 cat images—projected onto a 2-dimensional plane. The classifiers, named Classifier A and Classifier B, both achieve an accuracy of 75%, but this project aims to dig deeper into their performance and behavior through visualizations and interactive tools.

**Problem Statement**
Given that both classifiers have identical overall accuracy, the objective of this analysis is to:

Determine Classification Accuracy:

Identify which images are correctly classified by both classifiers, only one of the classifiers, or neither.
Evaluate Classifier Performance by Class:

Analyze the performance of Classifier A and Classifier B with respect to the dog and cat classes.
Explore Data in the 2D Projection Space:

Assess the classifiers' performance on selected subsets of the data within the 2D projection.
Dataset
The dataset (Synthetic_2_classifiers.csv) contains the following columns:

x: X-coordinate of the image in the projected data space.
y: Y-coordinate of the image in the projected data space.
label: The actual label of the image (dog or cat).
classifierA_predicted_label: The label predicted by Classifier A.
classifierB_predicted_label: The label predicted by Classifier B.


Tasks and Visualizations

Task 1A: Data Manipulation and Scatter Plot
Objective: Generate a scatter plot that categorizes data points into three groups:
Correctly classified by both classifiers.
Correctly classified by only one classifier.
Not correctly classified by either classifier.
Visualization: The scatter plot shows the distribution of images in the 2D space, with different colors indicating the classification performance.

Output : 
![Task1a](https://github.com/user-attachments/assets/76a4a7fd-dffc-4f73-ab7e-21cc28a07dbd)

Task 1B: Custom Visual Encoding
Objective: Create a customized bar chart that visualizes the count of correct and incorrect classifications for each class (dog and cat) by both classifiers.

Visualization: The bar chart provides a clear comparison of the performance of both classifiers in predicting each class.

Output : ![Task1b](https://github.com/user-attachments/assets/d109cf77-a76a-4fa1-8596-5e906a23e501)


Task 1C: Linked Interactivity
Objective: Implement linked interactivity between the scatter plot and the bar chart, allowing users to filter data points in the scatter plot and see corresponding updates in the bar chart.

Visualization: When selecting points in the scatter plot, the bar chart dynamically updates to reflect the performance of the classifiers on the selected data points.

Output : ![Task1c](https://github.com/user-attachments/assets/2aa5e523-3102-47b0-91a5-620cc0199e73)



Task 2: Critical Analysis and Improvement

2A: Identify and discuss a flaw in one of the proposed visualizations.

    Identified Flaw - **Class Imbalance Representation**

2C: Propose a visualization modification to improve the analysis or suggest a way to extend the comparison to 20 classifiers.

    Modified Solution - **Bar chart comparison of Normalized Metrices of classified class (With Precision, Recall, F1 Score)**
    
![Task2c](https://github.com/user-attachments/assets/4774331a-0c84-4d5c-aadc-5ca9af2b3920)

    

Files in the Repository
Task.ipynb: The main notebook containing all code, visualizations, and analysis.
Synthetic_2_classifiers.csv: The dataset used for the analysis.
Task1a.png, Task1b.png, Task1c.png, Task2c.png: Screenshots of the generated visualizations.

**How to Run**
Clone the repository.
Open Task.ipynb in Jupyter Notebook or any compatible environment.
Ensure that Synthetic_2_classifiers.csv is in the same directory as the notebook.
Run the notebook cells to reproduce the analysis and visualizations.


Conclusion
**This project not only evaluates the performance of two classifiers but also highlights the importance of detailed analysis and visualization in understanding classifier behavior beyond just accuracy metrics. The interactive tools provided allow for an in-depth exploration of the classifiers' performance, offering insights that could inform further improvements.**
