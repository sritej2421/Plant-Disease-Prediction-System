
# 🌱 Plant Disease Detection 🔎  

This **Plant Disease Detection** project is designed to leverage **Convolutional Neural Networks (CNN)** and deep learning techniques to identify and 
classify diseases in plants. The goal is to provide **farmers, researchers, and agriculture enthusiasts** with a **quick and reliable tool** to detect plant diseases simply by uploading images of plant leaves. 
This can help ensure **timely treatment** and reduce the risk of crop loss.

---

## 📂 Project Structure  

The project contains the following key files:

- `Plant_Disease_Detection.ipynb` — Jupyter Notebook used to train the deep learning model.
- `main_app.py` — Streamlit-based **web application** for plant disease prediction.
- `plant_disease_model.h5` — Pre-trained model file storing the learned weights.
- `requirements.txt` — List of required Python libraries.


## 🌿 How to Use  

Once the app is running, open your browser and visit: [http://localhost:8501](http://localhost:8501).  
You’ll see an interface where you can **upload a leaf image**, and the app will instantly predict if the plant has a disease or is healthy.

---

## 🧠 Model Training  

The CNN model was trained using the `Plant_Disease_Detection.ipynb` file.  
Key highlights of the training process:
- Dataset includes images of **healthy** and **diseased leaves**.
- CNN architecture was designed and optimized for **image classification**.
- After training, the model’s weights were saved as `plant_disease_model.h5` for future predictions.

---

## 🌐 Web Application  

The **Streamlit app** (`main_app.py`) provides a **simple user interface** to interact with the trained model.  
With a few clicks, users can upload images and receive **real-time predictions** — making plant disease detection **accessible and fast**.

---

## 🛠️ Requirements  

Make sure these packages are installed (already listed in `requirements.txt`):

```
Keras==2.8.0
numpy==1.21.4
streamlit==1.18.0
opencv-python-headless==4.5.3
tensorflow==2.7.0
```

---

## 📬 Want to Contribute?  

Feel free to **fork** the repo, submit **pull requests**, or suggest ideas to improve the model or app! 🌟

---

## 👤 Author  

**GANESH REDDY KOVVURI **  
