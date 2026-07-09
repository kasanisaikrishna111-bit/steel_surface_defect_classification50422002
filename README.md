Dataset Overview
"Our dataset contains 1,075 steel surface images divided into five defect classes: Deburring, Inclusion, Rolled Pit, Silk Spot, and Waist Folding."
Dataset Loading
"The images are stored in separate folders. We loaded them automatically, and each folder name was used as the image label."
Data Preprocessing
"All images were resized to 224 × 224 pixels and normalized to improve model performance."
Data Augmentation
"We applied rotation, zoom, and horizontal flip to increase image variety and improve learning."
Train-Test Split
"The dataset was divided into 80% training and 20% validation data."
Model
"We used a simple CNN model to learn image features and classify the five defect types."
Training
"The model was trained using the Adam optimizer with early stopping to avoid unnecessary training."
Results
"The model achieved 69.34% validation accuracy, but performed better on classes with more images."
Conclusion
"The model can classify steel defects, but balancing the dataset can further improve its performance."
