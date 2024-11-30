![Screenshot (1)](https://github.com/user-attachments/assets/700be522-f4e2-4b25-85c7-9b85196a318b)
HPC Power Consumption Reduction and Monitoring
This project demonstrates how machine learning can be applied to reduce and monitor power consumption in High-Performance Computing (HPC) environments, such as supercomputers. The goal is to predict power consumption based on system parameters like CPU, GPU, and RAM usage, and dynamically adjust system resources to optimize energy usage.

Overview
In this project, we:

Simulate system data (CPU, GPU, RAM usage) and power consumption.
Train a machine learning model (Random Forest Regressor) to predict power consumption.
Dynamically adjust system resources to reduce power consumption when predicted usage exceeds a threshold.
Key Features
Data simulation with CPU, GPU, and RAM usage.
Random Forest Regressor to predict power consumption.
Dynamic resource adjustment to reduce CPU usage when power consumption exceeds a predefined threshold.
Visualizations to show actual vs predicted power consumption, and adjusted CPU usage.
Requirements
To run the project, you need the following Python libraries:
numpy
pandas
matplotlib
scikit-learn
Run the main script: Execute the following Python script to start the demo:
python main.py
This will simulate the data, train the machine learning model, make predictions, and visualize the results.
Review the Results: After running the script, the following outputs will be displayed:
A graph comparing actual vs predicted power consumption.
A second graph showing the adjusted CPU usage to reduce power consumption.
Model Details
The model used in this project is a Random Forest Regressor, which is a type of ensemble learning model used for regression tasks. It aggregates the predictions from multiple decision trees to improve accuracy and reduce overfitting.
Features: CPU usage, GPU usage, RAM usage.
Target: Power consumption.
Evaluation: Mean Squared Error (MSE) is used to evaluate the model's performance.
Dynamic Adjustment Logic
If the predicted power consumption exceeds a threshold (e.g., 70 units), the CPU usage is reduced by 20% to optimize power consumption.
Results and Visualizations
Example Output:
Actual vs Predicted Power Consumption: A line plot comparing the real power consumption and the values predicted by the model.
Adjusted CPU Usage: A line plot showing the changes made to CPU usage in response to predicted power consumption exceeding the threshold.
Conclusion
This project showcases how machine learning can help optimize energy usage in HPC environments by predicting power consumption and adjusting resources accordingly.
