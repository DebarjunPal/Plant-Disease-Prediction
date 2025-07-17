🌱 Plant Disease Prediction 🚀
Python TensorFlow Flask

Upload a plant leaf image and instantly get a prediction of its disease or health status!

✨ Features
🌿 Detects a wide variety of plant diseases from images
🤖 Powered by Deep Learning (TensorFlow)
🌐 User-friendly web interface (Flask)
📁 Simple image upload & instant results
📝 Custom plant disease info from JSON
📦 Repository Structure
Code
📁 static/           # Static files (images, CSS, JS)
📁 templates/        # HTML templates
📁 uploadimages/     # Uploaded images
📄 app.py            # Flask backend server
📄 Plant_Disease_Prediction.ipynb # Jupyter Notebook for model development
📄 plant_disease.json # Disease info data
🚀 Quick Start
Clone the repo

bash
git clone https://github.com/DebarjunPal/Plant-Disease-Prediction.git
cd Plant-Disease-Prediction
Install dependencies

bash
pip install -r requirements.txt
# Or install manually:
pip install flask tensorflow numpy
Run the app

bash
python app.py
Open your browser and visit
http://127.0.0.1:5000/

📸 How it works
Upload a plant leaf image.
The app preprocesses the image and feeds it into a trained deep learning model.
The model predicts the disease label (or healthy status).
You get the result on the same page, along with the uploaded image!
🧠 Technologies Used
TensorFlow for deep learning
Flask for web UI
Jupyter Notebook for model prototyping
NumPy & JSON for data handling
🌍 Supported Diseases
Apple 🍏 (scab, black rot, rust, healthy)
Blueberry, Cherry 🍒, Corn 🌽, Grape 🍇, Orange 🍊, Peach 🍑, Pepper 🫑, Potato 🥔, Raspberry, Soybean, Squash, Strawberry 🍓, Tomato 🍅, and more!
🙌 Contributing
Fork this repo
Create your feature branch: git checkout -b feature/awesome-feature
Commit your changes: git commit -m "✨ Add awesome feature"
Push to the branch: git push origin feature/awesome-feature
Open a Pull Request
📝 License
This project is for educational purposes. Please check the repo for any additional license information.

💡 Author
Debarjun Pal

Made with ❤️ for plant health!
