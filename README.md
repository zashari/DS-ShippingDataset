# On-time vs Late Delivery on a Shipping Company

### **Introduction:**
Greetings! I'm excited to share an overview of my ongoing project, where I'm utilizing R for Exploratory Data Analysis (EDA), Visualization, and constructing a Regression Polynomial Model. The primary goal is to predict whether a product will be delivered on-time or experience delays.

### **Project Overview:**
I've started by loading the necessary libraries and importing the dataset, which I've named "Shipping," containing information about various aspects of the shipping process in an e-commerce context.

### **Exploratory Data Analysis (EDA):**
To get a sense of the dataset, I've displayed the first 10 rows, showcased its structure, and performed a comprehensive summary using the skimr package. I also checked for missing values to ensure data integrity.

### **Data Visualization:**
Visualizing correlations between numeric variables, I employed a heatmap to provide a clear overview. Additionally, I explored the frequency distribution of categorical variables such as Warehouse Block, Mode of Shipment, Product Importance, Gender, and Class.

The dataset's intricacies were further unveiled through bar plots, box plots, and scatter plots. Each visualization aimed to uncover patterns, relationships, and potential insights into the shipping dynamics.

### **Regression Polynomial Model:**
Moving on to modeling, I preprocessed the dataset by converting categorical variables into factors and split it into training and testing sets. For the predictive model, I chose a Regression Polynomial Logistic Model. The model was trained on the training set and then tested on the testing set for evaluation.

### **Model Evaluation:**
The performance of the model was assessed using a confusion matrix, providing insights into True Positives, True Negatives, False Positives, and False Negatives. Accuracy and F1-score were calculated to gauge the model's overall performance.

### **Conclusion:**
The preliminary results suggest promising outcomes in predicting timely deliveries. As the project progresses, further refinements and analyses will be conducted to enhance the model's accuracy and reliability. Stay tuned for more updates on this exciting journey into predictive analytics and logistics forecasting!
