# Software Quality Prediction

A comprehensive machine learning project to predict software module quality using various code metrics. This project includes data processing, exploratory data analysis (EDA), supervised learning with multiple classification models (including Neural Networks), and unsupervised clustering.

## 🚀 Features
- **Exploratory Data Analysis**: Automated correlation heatmaps and distribution plots.
- **Supervised Learning**: Comparison of 8 models including Random Forest, SVM, and MLP (Neural Network).
- **Unsupervised Learning**: K-Means clustering to identify hidden patterns in code complexity.
- **Automated Reporting**: Generates a professional PDF report following university standards.

## 📊 Performance
The **Neural Network (MLPClassifier)** achieved the highest performance with **91.4% Accuracy**.

## 🛠️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd CSE422
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn reportlab
   ```
3. Generate charts and metrics:
   ```bash
   python generate_report_charts.py
   ```
4. Compile the PDF report:
   ```bash
   python compile_pdf.py
   ```

## 📂 Project Structure
- `software_quality_dataset.csv`: The raw dataset.
- `Software_Quality_Prediction.ipynb`: Interactive analysis and model experimentation.
- `generate_report_charts.py`: Automated script for producing high-quality visualizations.
- `compile_pdf.py`: Script to generate the final PDF report.
- `assets/`: Directory containing all generated visualizations and metrics.
- `Software_Quality_Project_Report.pdf`: The final compiled report.

## 📜 License
This project is for educational purposes as part of the CSE422 course.
