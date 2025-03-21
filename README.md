## 🖼️ Image Classifier - Sea Guardian ML Model 🌊

This repository contains the Python implementation of an Image Classification model developed to detect: 
✅ Oil Spills
✅ Plastic Accumulation Zones
✅ Illegal Waste Dumping
✅ Animal Recognition

The model was trained using satellite and aerial images to support environmental protection efforts as part of the Sea Guardian Project.

📂 Project Structure
image-classifier/
│
├── data/                 # Dataset (Images)
├── main.py               # Main script to preprocess and explore data
├── train.py              # Training script for the ML model
├── app.py                # Flask API to serve the model
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation (You're here!)
✅ Features
Image classification using CNN (Convolutional Neural Network)
Flask app to serve predictions via a web interface
Pre-trained model checkpoint saved for easy reuse
Modular Python scripts for better readability and updates
⚙️ Setup Instructions
1️⃣ Clone the Repository

git clone https://github.com/yourusername/image-classifier.git
cd image-classifier
2️⃣ Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
🚀 Running the Project
🔄 1. Data Preprocessing and Exploration
python main.py
🏋️ 2. Train the Model
Ensure the dataset is placed inside the data/ folder.
python train.py
🌐 3. Run the Flask Web App
python app.py
Visit http://127.0.0.1:5000/ in your browser to test the model.

📊 Dataset
The model was trained on a custom dataset containing categorized images of:
Oil spills
Plastic zones
Illegal dumping
Animals
Dataset is structured and stored in the data/ directory (not included due to size).
📦 Requirements
Major libraries used:

TensorFlow / Keras
NumPy
Pandas
Flask
OpenCV
Scikit-learn
Matplotlib
(Complete list in requirements.txt)

🌟 Future Improvements
Model optimization for real-time predictions
Deployment on cloud platforms (AWS/GCP)
Enhance dataset size and quality
Integration with a frontend UI
🤝 Contributing
Feel free to fork the repository and raise a pull request. Contributions to improve the model and its deployment are welcome!

📝 License
This project is licensed under the MIT License.










Search
