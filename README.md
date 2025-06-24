
📌 Face Attendance System
==============================

🎯 Overview:
-------------
This is a real-time 🎥 face recognition-based attendance system using OpenCV and the face_recognition library. It captures video from your webcam, recognizes known faces, and automatically ✅ marks attendance by storing names and timestamps in a CSV file.

✨ Features:
-------------
- 🎥 Real-time face detection and recognition
- 📝 Automatic attendance marking with time logging
- 📂 Easy to add new users by simply adding their images to the 'Training_images' folder

⚙️ Important Notes:
--------------------
❗ The following files and folders are NOT included in this repository:
- `Training_images/` folder (you need to create this and add face images yourself)
- `Attendance.csv` file (this will be automatically created when you run the code)

You MUST:
- Create a folder named `Training_images` in the project directory.
- Add clear, front-facing images to the `Training_images` folder.
- Example:
Training_images/
├── John.jpg
├── Alice.jpg
└── Bob.jpg

📂 Project Structure:
----------------------
- 📜 main.py              # Main Python script
- 📦 requirements.txt     # Python dependencies (basic packages only)
- 🖼️ Training_images/     # Folder for known people's images (you need to create this)
- 📄 Attendance.csv       # Auto-generated when you run the script

⚙️ Setup Instructions:
-----------------------
1. Clone the repository:
   git clone https://github.com/SrijaaimeenakshiM/Face-Attendance-System.git
   cd Face-Attendance-System

2. Install the basic requirements:
   pip install -r requirements.txt

3. Create the 'Training_images' folder and add images of known people.  
   The filename (without extension) will be used as the person's name.

4. Install system-level tools:
   - ✅ CMake: Download from https://cmake.org/download/ and **add to system PATH.**
   - ✅ Visual Studio C++ Build Tools: Download from https://visualstudio.microsoft.com/visual-cpp-build-tools/ and select "Desktop Development with C++"

5. Install the face recognition libraries:
   pip install dlib
   pip install face_recognition

🔥 Alternative (Recommended for Windows Users):
-----------------------------------------------
If you face issues installing dlib:
1. Download the precompiled dlib wheel from:
   https://www.lfd.uci.edu/~gohlke/pythonlibs/#dlib
   (Example: dlib‑19.24.2‑cp312‑cp312‑win_amd64.whl for Python 3.12)

2. Install using:
   pip install path\to\dlib‑19.24.2‑cp312‑cp312‑win_amd64.whl
   pip install face_recognition

🚀 Run the Project:
--------------------
python main.py

🖼️ How to Add New Faces:
--------------------------
- Add a new image to the 'Training_images' folder.
- Example:
   Training_images/
   ├── John.jpg
   ├── Alice.jpg

- The system will automatically read new images when you restart the code.

💡 Notes:
-----------
- 🎥 Make sure your webcam is properly connected.
- ✅ Ensure that the faces in the training images are clear and front-facing for best results.




