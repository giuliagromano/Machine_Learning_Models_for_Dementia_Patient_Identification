# Machine_Learning_Models_for_Dementia_Patient_Identification
This project aims to train and evaluate different Machine Learning models for identifying patients with dementia. 
The dataset used is OASIS Brains Datasets, Oasis-2.

## Dataset & Preprocessing
The original dataset includes multiple visits per patient. A preprocessing step was performed to retain only one record per patient, avoiding data leakage.
A **feature matrix** was then extracted to represent relevant clinical and demographic information.

## Model Training & Evaluation
The dataset was split into **training** and **test sets** to evaluate model performance.
Two classification models were implemented and compared:
  - **Logistic Regression**
  - **Decision Tree**

The **Logistic Regression model** showed higher accuracy and was selected as the final model for prediction.
## Final Experiment
A new subject is introduced to the system, and the model predicts whether the patient is likely to develop dementia based on the input features.

---

# Modelli di Machine Learning per l'Identificazione di Pazienti con Demenza

Questo progetto ha l'obiettivo di addestrare e valutare diversi modelli di Machine Learning per identificare pazienti affetti da demenza.  
Il dataset utilizzato è OASIS Brains Datasets, Oasis-2.

## Dataset e Pre-elaborazione dei dati
Il dataset originale includeva più visite per ciascun paziente. È stato quindi effettuato un preprocessing per mantenere **un solo record per paziente**, evitando così il data leakage. Successivamente è stata estratta una **matrice delle features** contenente le informazioni cliniche e demografiche rilevanti.

## Addestramento ed Evaluazione dei Modelli
Il dataset è stato suddiviso in **training set** e **test set** per valutare le prestazioni dei modelli.  
Sono stati implementati e confrontati due modelli di classificazione:
- **Logistic Regression**
- **Decision Tree**

Il modello di **Logistic Regression** ha mostrato una maggiore accuratezza ed è stato scelto come modello finale per la predizione.

## Esperimento Finale
Un nuovo soggetto viene introdotto nel sistema, e il modello predice se il paziente è a rischio di sviluppare demenza sulla base delle feature fornite.
