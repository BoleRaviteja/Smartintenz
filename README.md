🧠 Team ID : LTVIP2025TMID43878

Team Size : 4

👨‍💻 Team Members

Team Leader : Dalavai Ruchitha

Team member : Bole Ravi Teja

Team member : Boddupalli Venkata Hemalatha

Team member : Chaganti Dharmaja

🧬 HematoVision: Advanced Blood Cell Classification Using Transfer Learning
HematoVision is a deep learning-powered web application designed to classify microscopic images of blood cells into one of four categories:

🔴 Eosinophil
🟢 Lymphocyte
🟡 Monocyte
🔵 Neutrophil
This intelligent diagnostic tool leverages Transfer Learning with MobileNetV2 to deliver high-accuracy predictions in real-time, wrapped in a clean and intuitive Flask-based web interface.

🚀 How It Works
📤 Upload a microscopic image of a blood cell.
🔍 The model processes the image using deep learning.
📈 You get the predicted class along with a preview of the uploaded image.
This makes HematoVision an ideal assistant for biomedical learners, educators, and early-stage researchers.

⚙️ Features
✅ Real-time image classification
✅ Built-in preprocessing pipeline with OpenCV
✅ Lightweight model (MobileNetV2) for quick inference
✅ Web interface with smooth UX and visual feedback
✅ Base64 image embedding for fast, secure previews

🛠️ Tech Stack
Layer	Technologies Used
Model	TensorFlow / Keras with MobileNetV2
Backend	Python, Flask
Image Ops	OpenCV for image preprocessing
Frontend	HTML5, CSS3 (light theme with stunning UI)

📁 Project Structure
HematoVision/
├── app.py               # Main Flask application
├── Blood Cell.h5        # Pretrained MobileNetV2 model (~60MB)
├── requirements.txt     # Project dependencies
├── static/              # Uploaded image storage
└── templates/           # HTML templates
    ├── home.html        # File upload and landing page
    └── result.html      # Prediction result display page
    
💻 Run Locally
You can run this project easily on your local system. Just follow these steps:

2️⃣ Create a Virtual Environment (Optional but recommended)
python -m venv venv
venv\Scripts\activate       # On Windows
# source venv/bin/activate  # On macOS/Linux
3️⃣ Install the Required Packages
pip install -r requirements.txt
4️⃣ Start the Flask App
python app.py
Then open your browser and go to: 🔗 http://127.0.0.1:5000

📸 Sample Output
🧠 The application shows the predicted blood cell type alongside the uploaded image, providing instant visual confirmation.

👨‍🔬 Future Enhancements
Integration with mobile camera input
Batch image classification
Confidence score visualization
CSV download for prediction logs
🙌 Acknowledgements
Thanks to the open-source community for datasets, MobileNetV2 pretrained weights, and Flask ecosystem.
