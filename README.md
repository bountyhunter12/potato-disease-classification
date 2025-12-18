# Potato Disease Classification

A deep learning–based plant disease classification system that predicts potato leaf diseases from images using a trained TensorFlow/Keras CNN model and a Streamlit web interface.

![Preview](./images/ui.png)

---

## Features

- Image-based potato disease classification
- Pre-trained CNN model (`.h5`) for inference
- Image preprocessing using Pillow and NumPy
- Streamlit-based interactive web UI
- Supports JPG, JPEG, and PNG images
- Real-time prediction on uploaded images

---

## Tech Stack

### Frontend
- Streamlit

### Backend
- Python
- TensorFlow / Keras
- NumPy
- Pillow

### Model
- Convolutional Neural Network (CNN)
- Trained on potato leaf disease images

---

## Setup

### 1. Clone the repository
```bash
git clone https://github.com/bountyhunter12/potato-disease-classification.git
cd potato-disease-classification
```
## Project Structure
### 2. Create a virtual environment
```bash
python -m venv venv
```
Activate it:

```
# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate
```
### 3. Install dependencies
```
pip install -r app/requirements.txt
```


### 6. Run the Streamlit app
```
streamlit run app/main.py
```

Visit:
http://localhost:8501

## Contributing

Pull requests are welcome.


## License

MIT License.
