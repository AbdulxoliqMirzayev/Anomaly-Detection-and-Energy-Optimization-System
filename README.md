# Anomaly Detection and Energy Optimization System

## Project Purpose
This project aims to revolutionize industrial operations by providing an AI-driven system to monitor equipment, detect anomalies, and optimize energy consumption. By leveraging advanced machine learning models, the system ensures improved productivity, reduced costs, and efficient energy management in manufacturing and industrial settings.

---

## Features
1. **Anomaly Detection:**
   - Identifies abnormal behavior in equipment using the Isolation Forest algorithm.
   - Detects deviations in parameters such as temperature, torque, rotational speed, and tool wear.

2. **Energy Consumption Analysis:**
   - Tracks and calculates energy usage for each piece of equipment.
   - Highlights areas with excessive energy consumption.

3. **Predictive Maintenance:**
   - Recommends optimal maintenance schedules to avoid unexpected breakdowns.
   - Minimizes downtime by identifying potential issues early.

4. **Interactive Visualization:**
   - Generates scatter plots, pie charts, and line graphs to illustrate anomalies and energy trends.
   - Provides detailed comparison between anomalous and normal equipment behavior.

5. **User-Friendly Interface:**
   - Built using **Gradio** for easy accessibility and real-time insights.

---

## Benefits to Our Organization
### 1. **Cost Savings:**
   - Anomalies are detected early, reducing emergency repairs and minimizing unnecessary maintenance costs.
   - Predictive maintenance avoids unplanned downtime, saving millions in operational losses.

### 2. **Improved Productivity:**
   - Ensures seamless operation of equipment, increasing manufacturing efficiency.
   - Reduces delays caused by unexpected equipment failures.

### 3. **Energy Efficiency:**
   - Optimizes energy consumption, cutting down operational expenses and promoting sustainability.
   - Helps identify underperforming equipment that consumes excessive energy.

### 4. **Data-Driven Decision Making:**
   - Detailed visualizations provide actionable insights, enabling better resource management and strategic planning.

### 5. **Competitive Advantage:**
   - Implementing cutting-edge AI technology positions our organization as an industry leader.

---

## How It Works
1. **Data Processing:**
   - Accepts equipment data in CSV format.
   - Key features like air temperature, process temperature, rotational speed, and torque are extracted for analysis.

2. **Model Training:**
   - The Isolation Forest algorithm is trained on historical data to detect anomalies.
   - Real-time monitoring flags deviations as they occur.

3. **Energy Optimization:**
   - Calculates energy consumption based on operational parameters.
   - Identifies inefficiencies and suggests improvements.

4. **Visualization:**
   - Provides clear and interactive charts to visualize anomalies and energy trends.
   - Allows comparison between anomalous and normal equipment.

---

## Global Context
Similar projects have delivered remarkable results worldwide:
- **General Electric (GE):**
  - Predictive maintenance saved over $1 billion annually by preventing downtime and optimizing operations.
- **Siemens:** 
  - Reduced energy consumption by 15% using anomaly detection in manufacturing plants.
- **Toyota:** 
  - Improved production efficiency and minimized operational disruptions with real-time anomaly detection.

These examples highlight the transformative impact of AI-driven anomaly detection systems on industrial processes.

---

## Technologies Used
1. **Programming Language:** Python
2. **Libraries and Tools:**
   - `pandas` and `numpy`: Data manipulation and analysis.
   - `scikit-learn`: Machine learning (Isolation Forest, evaluation metrics).
   - `matplotlib`: Visualization.
   - `gradio`: Interactive interface.
3. **Machine Learning Techniques:**
   - Isolation Forest for anomaly detection.
   - ROC-AUC for model evaluation.
4. **Data Processing:**
   - CSV files for equipment data.
   - Feature engineering for energy and anomaly analysis.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/anomaly-detection.git
   cd anomaly-detection
