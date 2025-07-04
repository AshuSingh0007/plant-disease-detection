# Plant 🌱 Disease  Detection 🔎

Plant Disease Detection is an innovative machine learning project that harnesses the power of Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The primary objective is to offer farmers and agricultural experts a valuable tool for swift plant health diagnosis, facilitating timely intervention and minimizing the risk of crop loss.

## 📊 Dataset

We have used the Plant Disease Detection Dataset from **Kaggle**, which contains a wide variety of labeled plant leaf images across different crop types and disease categories. This dataset served as the foundation for training our CNN model effectively.


## Project Structure 📂

The project comprises essential components:

- `Plant_Disease_Detection.ipynb`: Jupyter Notebook with the code for model training.
- `main_app.py`: Streamlit web application for plant disease prediction.


- ## Usage 🌿

Once the application is running, open your web browser and navigate.Upload an image of a plant leaf, and the system will predict if it is affected by any disease.

## Model Training 🧠

The model was trained using the `Plant_Disease_Detection.ipynb` notebook. It employs a Convolutional Neural Network architecture to classify plant images into different disease categories.
## Web Application 🌐

The web application (`main_app.py`) empowers users to interact with the trained model. Upload plant images, and the application provides real-time predictions regarding the health of the plant.

## Requirements  🛠️

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0


