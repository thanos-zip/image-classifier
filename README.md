> ⚠️ This repo is a starting point, not a solution. 
> You will get stuck. That's the point. Google is your best friend.

# Image Classifier

> Upload any image and get an instant prediction of what's in it using a deep learning model.

## What You Will Learn
- How to build and use a CNN image classification model
- How to build a simple web UI with Streamlit
- How to work with PyTorch or TensorFlow in a real project

## Tech Stack
- Python
- PyTorch or TensorFlow
- Streamlit
- Pillow
- Render (deployment)

## Getting Started

### Prerequisites
- Python 3.9+ installed
- pip installed

### Installation
```bash
git clone https://github.com/thanos.zip/image-classifier
cd image-classifier
pip install -r requirements.txt
streamlit run app.py
```

## Project Structure
```
image-classifier/
├── app.py               # Streamlit UI lives here
├── model.py             # Load model and run predictions here
├── utils.py             # Image preprocessing helpers here
├── requirements.txt
└── README.md
```

## What To Build
- Load a pre-trained ResNet or MobileNet model
- Accept an image upload through the Streamlit UI
- Preprocess the image to match model input requirements
- Run the prediction and return the top 3 results with confidence scores
- Display results clearly with the uploaded image
- Deploy on Render

## Stretch Goals
- Fine tune the model on a custom dataset of your choice
- Add a camera input option — classify in real time
- Show a confidence bar chart for the top 5 predictions

## Resources
- https://pytorch.org/vision/stable/models.html
- https://docs.streamlit.io/library/api-reference
- https://pillow.readthedocs.io

---
Built for [@thanos.zip](https://instagram.com/thanos.zip) followers.
