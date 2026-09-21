# 🐾 Cat vs Dog Identifier Web App

A clean, modernized [Streamlit](https://streamlit.io) web application that utilizes a deep learning Convolutional Neural Network (CNN) model built in TensorFlow/Keras to accurately classify images of cats and dogs.

## ✨ Features
* **Modern UI:** Outfitted with a premium, sleek glassmorphism aesthetic and a dark glowing backdrop.
* **Real-time Inference:** Drag and drop an image to get instant classification outputs.
* **Confidence Metric:** Displays a percentage score mapping the model's confidence in its choice.

## 🛠️ Local Setup Instructions

Follow these steps to run this application on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abhangvipul/Cat-Dog-Classifier-Webapp
   cd Cat-Dog-Classifier-Webapp
   ```

2. **Set up a compatible virtual environment (Python 3.12 or 3.13 recommended):**
   ```bash
   py -3.13 -m venv myenv
   myenv\Scripts\activate
   ```

3. **Install the dependencies:**
   ```bash
   pip install streamlit tensorflow pillow numpy opencv-python
   ```

4. **Launch the Streamlit web application:**
   ```bash
   streamlit run app.py
   ```