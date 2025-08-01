**ASL - American Sign Language Recognition**
An AI-powered application that recognizes American Sign Language gestures using computer vision and machine learning.

**Overview**
ASL is a deep learning-based project developed to assist communication for the hearing and speech impaired. The system captures hand gestures via webcam and predicts the corresponding alphabet or word using a trained Convolutional Neural Network (CNN). The application is designed for real-time usage and is structured to be scalable and modular.

**Features**
• Real-time gesture detection using webcam
• Model training on a custom ASL dataset
• Prediction and live classification of ASL letters
• Data preprocessing and augmentation support
• User-friendly interface for demo and testing
• Modular codebase with separate scripts for capture, training, prediction

**Tech Stack**
Language: Python
Libraries: OpenCV, NumPy, TensorFlow/Keras, Pandas
Model: CNN (Convolutional Neural Network)
IDE: VS Code / Jupyter
Others: Matplotlib, Scikit-learn

**Installation**
Clone the repository:

Create and activate a virtual environment (optional):
python -m venv venv  
source venv/bin/activate  # for Linux/macOS  
venv\Scripts\activate     # for Windows 
 
**Install dependencies:**
pip install -r requirements.txt

**Project Structure**

ASL-Recognition/


│
├── data/               # Dataset containing train/test images
│   ├── train/          
│   └── test/
│
├── model/              # Trained model weights (saved .h5 file)
│
├── src/                
│   ├── capture.py     
│   ├── train.py       
│   ├── predict.py     
│   └── utils.py       
│
├── README.md           
├── requirements.txt   
└── .gitignore          


🤝 **Contributions**
Feel free to fork and raise a pull request! Contributions are welcome.
For major changes, please open an issue first to discuss what you would like to change.

