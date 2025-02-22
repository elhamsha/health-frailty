# AI for Frailty Detection  

This project utilizes AI to analyze and interpret complex data in order to pinpoint essential physiological and behavioral traits that could act as biomarkers for frailty. These identified biomarkers have the potential to play a crucial role in predicting and addressing frailty in individuals. By harnessing the power of AI, this research aims to enhance healthcare and enhance the quality of life for the elderly.
The project description can be found in 'FrailtyDetectionWithAI.pdf', while the solution is in 'ASolutionForFrailtyDetectionWithAI.pdf'. Please refer to these documents for more information.  

## 📂 Project Structure  
The project files are numbered. Please run them in order.
📂 Frailty Detection Project
│── 1_clinical_dataset_preprocess.ipynb # Preprocessing and normalizing the clinical dataset, saving it in clinical_dataset_corrected.csv
│── 2_clinical_dataset_classification.ipynb # Running Classification algorithms on the clinical dataset
│── 3_sensors_dataset_preprocess.ipynb # Preprocessing and normalizing the sensor dataset, saving it in sensors_dataset_corrected.csv
│── 4_percentage_in_rooms.ipynb # Calculating the percentage of time each individual spent in the following rooms:
│ # Bedroom, Bathroom, Living room, Kitchen. Saving results in percentage_in_rooms_dataset.csv
│── 5_clustering_in_merged.ipynb # Merging 'clinical' dataset with the 'percentage of time spent in rooms' dataset and running Clustering algorithms 

## 🚀 Features  

- **Classification**  
- **Clustering**  
- **Silhouette Coefficient**  
- **PCA (Principal Component Analysis)**  

## 🔧 Requirements  

- Python 3.x  
- Jupyter Notebook  
- Required libraries:  
  ```bash
  pip install numpy pandas matplotlib scikit-learn seaborn
  ```

## 📊 Usage
- Open the Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- Navigate to the desired .ipynb file and run the cells.

## 📜 License
This project is licensed under the MIT License.

