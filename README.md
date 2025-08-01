**ASL - American Sign Language Recognition System**
ASL is an intelligent real-time gesture recognition platform designed to recognize American Sign Language using machine learning and computer vision. This project aims to bridge communication gaps for the hearing and speech impaired by interpreting sign language gestures through webcam input.

**Features:**
Real-Time Sign Recognition: Detect and classify ASL alphabets via webcam using trained ML models.

User-Friendly Interface: Simple and intuitive GUI built with OpenCV for live interaction.

Image Preprocessing: Cropping, thresholding, and ROI detection for cleaner gesture recognition.

Dataset Augmentation: Train on large sets of images for robust accuracy.

Model Training & Evaluation: Built-in support for training your own CNN models using Keras.

Modular Codebase: Easily customizable for new gestures or languages.

**Tech Stack:**
Frontend
OpenCV – Webcam integration and UI visualization
Tkinter (if GUI is used for controls)

**Backend:**
Python – Core scripting language
TensorFlow/Keras – CNN model training and recognition
NumPy – Numerical operations
Matplotlib – Visualization of training metrics
OS / Shutil – File and directory handling
**

📁 Project Structure**

ASL/
├── data/                    
│   ├── train/              
│   └── test/               
├── model/                   
├── src/
│   ├── capture.py           
│   ├── train.py             
│   ├── predict.py           
│   └── utils.py            
├── README.md
└── requirements.txt     
    
**Installation:**
Step 1: Clone the Repository
git clone https://github.com/prejan/ASL.git
cd ASL

Step 2: Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Step 3: Install Dependencies
pip install -r requirements.txt

**Model Training:**
To train a new model on your dataset:
python src/train.py

**You can also use src/capture.py to generate new gesture images:
**python src/capture.py

 **Run Real-Time Recognition**
**Launch the live recognition from your webcam:**
python src/predict.py

**Sample Output**
Recognizes individual ASL letters (A–Z)
Displays prediction results live over the video feed
Optional: Save recognized sequences for translation

🤝 Contributing
We welcome contributions! Here’s how to get started:
Fork the repository.
Create your feature branch: git checkout -b feature/amazing-feature
Commit your changes: git commit -m 'Add amazing feature'
Push to the branch: git push origin feature/amazing-feature
Open a Pull Request
