## 🌱 Plant Disease Detection System for Sustainable Agriculture
This project is a web-based application that uses a deep learning model to identify plant diseases from leaf images. It is designed to assist farmers and agricultural professionals in diagnosing plant diseases early, improving crop yield and promoting sustainable farming practices.

📖 Features
Disease Recognition: Upload an image of a plant leaf to detect potential diseases.
User-friendly Interface: Streamlit-based web application with an intuitive layout.
Support for Multiple Plant Species: Detects diseases in crops like apples, grapes, tomatoes, and more.
Pre-trained Model Integration: Utilizes a TensorFlow model trained on a comprehensive dataset of plant leaf images.
📋 Prerequisites
Before you begin, ensure you have the following installed:

Python 3.7+
pip (Python package manager)
Git
🛠️ Installation
Clone the repository:

git clone https://github.com/manikan2848y/Plant_disease_new.git
cd Plant_disease_new
Install dependencies:

pip install -r requirements.txt
Download the pre-trained model:

Ensure trained_plant_disease_model.keras is in the project directory.
🚀 Usage
Run the Streamlit application:

streamlit run main.py
Open the application in your browser at http://localhost:8501.

Navigate through:

HOME Page: Learn about the project.
DISEASE RECOGNITION: Upload a plant leaf image to detect diseases.
📊 Supported Plant Diseases
The application can detect the following plant diseases:

Apple: Apple scab, Black rot, Cedar apple rust, Healthy
Blueberry: Healthy
Cherry: Powdery mildew, Healthy
Corn (Maize): Cercospora leaf spot, Common rust, Northern leaf blight, Healthy
Grape: Black rot, Esca (Black Measles), Leaf blight, Healthy
Orange: Citrus greening (Haunglongbing)
Peach: Bacterial spot, Healthy
Pepper (Bell): Bacterial spot, Healthy
Potato: Early blight, Late blight, Healthy
Strawberry: Leaf scorch, Healthy
Tomato: Bacterial spot, Early blight, Late blight, Leaf mold, Septoria leaf spot, Spider mites, Target spot, Yellow leaf curl virus, Mosaic virus, Healthy
🧠 Model Details
The deep learning model is built using TensorFlow and trained on the PlantVillage Dataset containing thousands of labeled plant leaf images.

Key features of the model:

Image input size: 128x128 pixels
Activation function: Softmax for multiclass classification
Optimizer: Adam
Loss function: Categorical crossentropy
👨‍💻 Contributing
Contributions are welcome! Follow these steps:

Fork the repository.
Create a new branch:
git checkout -b feature-name
Commit your changes:
git commit -m "Add feature-name"
Push to your branch:
git push origin feature-name
Submit a pull request.
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

📧 Contact
For questions or feedback, reach out to:

Name: [Sujith Kumar]
GitHub: [https://github.com/ASKumar07/Plant-Disease-Detection-Using-AI]
Email: [aakramsujithkumar777@gmail.com]
Feel free to copy-paste this into your README file and customize further as needed! Let me know if you'd like to adjust anything. 😊
