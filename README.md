# Advancing Infant Distress Detection: Two- and Three-Way Classification in Real-World Audio Environments  

## 📌 Dataset Overview  

This repository contains the dataset used in our research paper:  
**"Advancing Infant Distress Detection: Two- and Three-Way Classification in Real-World Audio Environments"**  

The dataset is designed for training and evaluating machine learning models in detecting infant distress in **real-world audio environments**. It includes labeled **audio recordings** of different infant vocalizations, categorized into three primary classes:

- **Fuss** – Mild distress sounds that may escalate into crying.
- **Cry** – Intense distress signals indicating discomfort or strong emotional reactions.
- **Other (Non-Distress)** – Background noise, cooing, or other sounds that do not indicate distress.

---

📂 Dataset Structure  

The dataset consists of two main components:


- **`audio-data.zip`**: Contains raw `.wav` audio files recorded in natural environments.
- **`audio-labels.zip`**: Contains label folders corresponding to the audio files, mapping them to one of the three classes.

Each audio file in `audio-data.zip` has a corresponding label file in `audio-labels.zip`, ensuring a structured dataset.

---

## 🚀 Usage Instructions  

1. **Download & Extract Files**  
   ```sh
   unzip audio-data.zip -d audio-data/
   unzip audio-labels.zip -d audio-labels/
