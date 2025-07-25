# Sign Language Interpreter 🤟🧠

An interactive and educational web-based application that uses deep learning to recognize American Sign Language (ASL) gestures. This project helps bridge communication gaps between the hearing-impaired and others through real-time gesture recognition and gamified learning.

## 🚀 Features

- 🔤 **ASL Alphabet and Word Detection** using a CNN model
- 🎮 **Gamified learning modes**: Letter Guess & Word Formation
- 📷 Webcam or image upload support for gesture input
- ⚡ Real-time predictions using FastAPI
- 🧑‍🏫 Intuitive UI built with Streamlit for accessibility
- 🧪 Tested with 94%+ accuracy on clean ASL datasets

## 🛠️ Tech Stack

- **Frontend**: Streamlit, HTML/CSS
- **Backend**: FastAPI
- **Model**: Convolutional Neural Network (Keras + TensorFlow)
- **Libraries**: NumPy, OpenCV, Pillow, streamlit-webrtc
- **Tools**: Git, VS Code, Python

## 📦 How to Run

```bash
# Clone the repository
git clone https://github.com/ROHITKH1024/CODE-YANTRA.git
cd CODE-YANTRA

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install backend and frontend dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
