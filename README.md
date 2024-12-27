# student-gpa-prediction-optimization
A deep learning project aimed at predicting first-year college GPA using high school SAT scores and GPA. The project evaluates various optimization techniques, such as SGD, Momentum, RMSProp, Adam, and more, to enhance model performance.
----
# Student GPA Prediction with Optimization Techniques  

## Overview  
This project demonstrates the application of deep learning techniques to predict the first-year GPA of college students based on their SAT scores and high school GPA. Prodigy University aims to enhance its admission process by leveraging predictive analytics to identify students who are likely to excel academically. The project evaluates and compares the performance of various optimization techniques to improve model efficiency and accuracy.  

---

## Features  

### **Data Preprocessing**  
- Converted raw data into NumPy arrays for seamless manipulation.  
- Standardized features to ensure consistent scaling across variables, enhancing model performance.  

### **Neural Network Architecture**  
- Designed a fully connected neural network (Multi-Layer Perceptron) with:  
  - Two hidden neurons.  
  - Activation functions such as ReLU and Sigmoid for better feature learning.  

### **Optimization Techniques**  
- Evaluated multiple optimization algorithms, including:  
  - **Stochastic Gradient Descent (SGD)**  
  - **Batch Gradient Descent**  
  - **Mini-Batch Gradient Descent**  
  - **Momentum**  
  - **Nesterov Momentum**  
  - **AdaGrad**  
  - **RMSProp**  
  - **Adam**  

### **Evaluation Metrics**  
- Calculated **Mean Squared Error (MSE)** to measure model accuracy.  

### **Visualization**  
- Plotted training and validation loss curves for each optimizer.  
- Showcased the impact of different optimization techniques on model convergence and learning stability.  

---

## Technologies Used  
- **Python**  
- **PyTorch**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  

---

## How to Use  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/GovindaTak/student-gpa-prediction-optimization.git
   ```  

2. **Navigate to the project directory**:  
   ```bash
   cd student-gpa-prediction-optimization
   ```  

3. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```  

4. **Run the Jupyter Notebook**:  
   ```bash
   jupyter notebook Student_GPA_Prediction.ipynb
   ```  

---

## Results and Insights  
- **Stochastic Gradient Descent (SGD)**: Achieved rapid updates but displayed higher variance in learning.  
- **RMSProp**: Provided consistent and efficient convergence, making it the best performer for this dataset.  
- **Adam**: Demonstrated excellent convergence with balanced updates, ranking second.  
- Visualizations highlighted the differences in training and test loss across all optimization methods.  

---

## Project Structure  
- **Dataset**: Contains historical SAT and GPA scores.  
- **Notebook**: Includes the implementation of the neural network and optimization techniques.  
- **Results**: Displays evaluation metrics and visual insights from training and testing.  

---

## License  
This project is licensed under the **MIT License**. Refer to the [LICENSE](LICENSE) file for details.  
