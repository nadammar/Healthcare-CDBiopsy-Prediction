# 🏥 Biopsy Disease Progression Prediction (Celiac Disease)

![Biopsy Sample Classes](images/marsh_classes.png)

##  Project Overview

This project was completed during my **Healthcare Data Science Internship at IT Progress Online (July 2022 – August 2022)**. It is based on research focused on **Celiac Disease**, aiming to predict disease progression from biopsy images. The data was collected in collaboration with a biopsy laboratory and is **confidential**.

We initially experimented with **six classes** of biopsy images based on the Marsh classification system (based on doctors' and specialists' decisions):

* `marsh1`: 0 – Represents early-stage mucosal changes with minor abnormalities in intestinal tissue
* `marsh2`: 1 – Indicates more pronounced mucosal damage with noticeable inflammation
* `marsh3a`: 2 – Partial villous atrophy (initial stage of severe tissue damage)
* `marsh3b`: 3 – Marked villous atrophy with significant tissue deterioration
* `marsh3c`: 4 – Complete villous atrophy, the most severe form of mucosal damage
* `normal`: 5 – Healthy tissue with no signs of celiac disease or mucosal damage

After evaluation with medical specialists, we decided to focus only on **three final classes** for the prediction model which are marsh1 , marsh2 and normal .

## 🛠️ Key Contributions

* Collected and preprocessed confidential biopsy images categorized into Marsh classes.
* Trained and fine-tuned deep learning models (including **CNN** , **VGG16** and **ResNet**) to predict the progression of celiac disease from biopsy images.
* Developed a user-friendly **Flask web application** to showcase real-time model predictions and visualize results.
* Due to laboratory data privacy, the code shared in this repository uses a **limited subset of data** for demonstration purposes only.

## 📚 Tools & Technologies

* Python, TensorFlow/Keras, OpenCV
* VGG16 and ResNet architectures for deep learning
* Flask (for the web app)
* Image preprocessing and augmentation libraries
* Collaborative biopsy dataset from partnered medical laboratory

## ⚙️ Installation & Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nadammar/Healthcare-CDBiopsy-Prediction.git  
   cd Healthcare-CDBiopsy-Prediction  
   ```
2. **Set up your Python environment and install dependencies:**

3. **Prepare the dataset:**

   * Place biopsy images in the appropriate folders based on classes. (Data is confidential and not shared in this repository.)
   * 
4. **Train or load the pre-trained deep learning models:**

5. **Run the Flask web app to showcase predictions:**

   


## 👨‍💻 Author

Project developed by **Nada Ammar** during my **Healthcare Data Science Internship at IT Progress Online**, in collaboration with a biopsy laboratory, based on research on **Celiac Disease**.



