🚗 Drowsiness Detection System
A real-time driver drowsiness detection system using OpenCV, Dlib, and Flask. This project monitors a driver's eye aspect ratio (EAR) to detect signs of drowsiness and trigger an alert sound when necessary.

📌 Features
✅ Real-time eye monitoring using a webcam
✅ Detects drowsiness based on the Eye Aspect Ratio (EAR)
✅ Alerts the driver with a warning sound
✅ Simple web interface using Flask
✅ Uses Dlib’s 68 facial landmark predictor

🛠 Tech Stack
Python
OpenCV (for face and eye detection)
Dlib (for facial landmarks)
Flask (for web-based video streaming)
Pygame (for playing alert sounds)

🚀 Installation & Setup
1️⃣ Clone the Repository

git clone https://github.com/your-username/Drowsiness-Detection.git
cd Drowsiness-Detection

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Download Pre-trained Model

Download the Dlib facial landmarks model from this link, extract it, and place it inside the models/ folder.

4️⃣ Run the Application

python app.py
Now, open http://127.0.0.1:5000/ in your browser.

📁 Project Structure
csharp
Copy
Edit
Drowsiness-Detection/
│── app.py                  # Main Flask app
│── templates/
│   └── index.html          # HTML frontend
│── static/                 # (Optional) CSS, JS, images
│── models/
│   └── shape_predictor_68_face_landmarks.dat  # Dlib model
│── music.wav               # Alert sound file
│── requirements.txt        # Dependencies
│── README.md               # Project documentation

🔮 Future Enhancements
🔹 Improve accuracy with deep learning models
🔹 Deploy as a mobile app
🔹 Add support for multiple drowsiness levels
