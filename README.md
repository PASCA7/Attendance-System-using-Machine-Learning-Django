## Automatic Attendence System using Machine Learning(Django)
## Functionality Supported
- Admin and Student Login
- Admin : Register new Student.
- Admin : Add Student photos to the training dataset.
- Admin: Train the model.
- Admin: View attendance reports of all Students. Attendance can be filtered by date or Student. 
- Student - View attendance reports of self.

## Built Using
- **OpenCV** - Open Source Computer Vision and Machine Learning software library
- **Dlib** - C++ Library containing Machine Learning Algorithms
- **face_recognition** by Adam Geitgey 
- **Django**- Python framework for web development.

### Face Detection
- Dlib's HOG facial detector.

### Facial Landmark Detection
- Dlib's 68 point shape predictor

### Extraction of Facial Embeddings
- face_recognition by Adam Geitgey

### Classification of Unknown Embedding 
- using a Linear SVM (scikit-learn==0.20.4)


