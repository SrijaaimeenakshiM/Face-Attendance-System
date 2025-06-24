📌 Face Attendance System
==============================

🎯 Overview:
-------------
This is a real-time 🎥 face recognition-based attendance system using OpenCV and the face_recognition library. The system captures video from your webcam, recognizes known faces, and automatically ✅ marks attendance by storing names and timestamps in a CSV file.

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
```bash
Training_images/
├── John.jpg
├── Alice.jpg
└── Bob.jpg
```

📂 Project Structure:
----------------------
- 📜 main.py              # Main Python script
- 📦 requirements.txt     # Python dependencies
- 🖼️ Training_images/     # Folder containing images of people to recognize (create this folder and add images)
- 📄 Attendance.csv       # Auto-generated CSV to store attendance logs

⚙️ Setup Instructions:
-----------------------
1. Clone the repository:
   ```bash
   git clone https://github.com/SrijaaimeenakshiM/Face-Attendance-System.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Face-Attendance-System
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a folder named 'Training_images' and add images of known people.
   The filename (without extension) will be used as the person's name.

5. Run the project:
   ```bash
   python main.py
   ```

🖼️ How to Add New Faces:
--------------------------
- Add a new image to the 'Training_images' folder.
- Example:
   ```bash
   Training_images/
   ├── John.jpg
   ├── Alice.jpg
   ```
- The system will automatically read new images when you restart the code.

💡 Notes:
-----------
- 🎥 Make sure your webcam is properly connected.
- ✅ Ensure that the faces in the training images are clear and front-facing for best results.

