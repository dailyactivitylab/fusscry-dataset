# Advancing Infant Distress Detection: Two- and Three-Way Classification in Real-World Audio Environments

## 📌 Dataset Overview

This repository contains the dataset used in our research paper:\
**"Advancing Infant Distress Detection: Two- and Three-Way Classification in Real-World Audio Environments"**

The dataset is designed for training and evaluating machine learning models in detecting infant distress in **real-world audio environments**. It includes labeled **audio recordings** of different infant vocalizations, categorized into three primary classes:

- **Fuss** – Mild distress sounds that may escalate into crying.
- **Cry** – Intense distress signals indicating discomfort or strong emotional reactions.
- **Other (Non-Distress)** – Background noise, cooing, or other sounds that do not indicate distress.

---

## 📂 Dataset Structure

The dataset consists of two main components:

- \`\`: Contains raw `.wav` audio files recorded in natural environments.
- \`\`: Contains label folders corresponding to the audio files, mapping them to one of the three classes.

Each audio file in `audio-data.zip` has a corresponding label file in `audio-labels.zip`, ensuring a structured dataset.

---

## 🚀 Usage Instructions

### **Accessing the Dataset**

Due to GitHub's size limitations, we are hosting a sample dataset on GitHub using Google Drive. Once accepted, we will publish the full dataset on a platform that allows large data hosting.

You can access the sample audio dataset from the following Google Drive link: [Download Sample Audio Data](https://drive.google.com/file/d/1CY72Nw8ERDwyDquFXl-bw4FUMQPnaQaM/view?usp=drive_link) but corresponding labels are there on this github

### **Download & Extract Files**

```sh
unzip audio-labels.zip -d audio-labels/
```

