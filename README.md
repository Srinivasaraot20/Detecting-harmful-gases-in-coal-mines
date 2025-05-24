# 🛡️ Detecting Harmful Gases in Coal Mines

A Machine Learning-based system to detect and alert about harmful gas levels in coal mines using real-time sensor data. This project is aimed at enhancing worker safety by providing predictive insights and early warnings through trained models like Random Forest and KNN.

---

## 👨‍💻 Author

**Srinivasa Rao Talari**  
🎓 B.Tech Final Year – Artificial Intelligence & Machine Learning  
🔗 GitHub: [Srinivasaraot20](https://github.com/Srinivasaraot20)

## 🔄 Sample Workflow

1. 📥 **Data Input**
   - Load dataset: `coal_mine_gas_realistic_dataset.csv`
   - Features: CH₄ (Methane), CO, Temperature, Humidity
   - Label: Safe / Hazard

2. 🧹 **Data Preprocessing**
   - Handle missing values
   - Normalize or scale data
   - Encode categorical variables (if any)

3. 🧠 **Model Selection**
   - Choose algorithm: Random Forest / KNN

4. 🏋️‍♂️ **Model Training**
   - Split dataset into training and test sets
   - Train model on training data

5. 🔍 **Model Evaluation**
   - Predict on test data
   - Calculate accuracy, precision, recall, confusion matrix

6. 📈 **Prediction**
   - Input: New sensor data
   - Output: Safe or Hazard prediction

7. 🚨 **Action**
   - If "Hazard" detected:
     - Trigger alert (e.g., buzzer, LED, GSM alert, LoRa message)


## 📦 Project Structure
Detecting-harmful-gases-in-coal-mines/
├── coal_mine_gas_realistic_dataset.csv # Cleaned dataset
├── knn_model.py # KNN model for prediction
├── rf_model.py # Random Forest model
├── model.py # Combined interface script (optional)
├── README.md # Project documentation




---

## 📊 Dataset

- `coal_mine_gas_realistic_dataset.csv`  
  Contains real-world simulated data of gas levels like:
  - Methane (CH₄)
  - Carbon Monoxide (CO)
  - Humidity
  - Temperature
  - Time-based readings
  - Labels (Safe / Hazard)

---

## 🧠 Machine Learning Models

Two algorithms have been implemented for harmful gas prediction:

1. **Random Forest Classifier**
   - Good accuracy
   - Handles imbalance and variance well

2. **K-Nearest Neighbors (KNN)**
   - Simple and effective for real-time classification

Each model was trained, tested, and validated using performance metrics like:

- Accuracy
- Precision
- Recall
- Confusion Matrix

---


📈 Results
Random Forest Accuracy: ~92%
KNN Accuracy: ~88%
Confusion Matrix and classification reports are printed in terminal.

🌐 Applications
🏭 Underground coal mine safety
📡 IoT-based safety helmets
🚨 Automated early warning systems
📲 Integration with GSM/LoRa alert modules


🛡️ Future Scope
Deploy models in embedded edge devices like Raspberry Pi + LoRa
Integrate with cloud platforms (e.g., ThingSpeak)
Extend dataset with live sensor feeds
Add deep learning and anomaly detection support

