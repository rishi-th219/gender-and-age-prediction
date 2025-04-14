
# Gender and Age Prediction from Facial Images

This project implements a machine learning pipeline to predict **gender** and **age** from facial images using pre-trained models. It is structured as a practical application of classical computer vision techniques combined with deep learning-based feature extraction.

## 📌 Project Highlights

- Uses OpenCV’s deep learning module (`cv2.dnn`) to load and run predictions using pre-trained Caffe models.
- Predicts:
  - **Gender**: Male / Female
  - **Age Group**: One of 8 predefined age bins
- Accepts input from:
  - Static images
  - Webcam streams

---

## 🧠 Models Used

Pre-trained models provided by OpenCV (Caffe-based):

- **Gender Classification**:
  - Model: `gender_net.caffemodel`
  - Prototxt: `gender_deploy.prototxt`
- **Age Classification**:
  - Model: `age_net.caffemodel`
  - Prototxt: `age_deploy.prototxt`

- **Age bins used:**
  - ['(0-2)', '(4-6)', '(8-12)', '(15-20)', '(25-32)', '(38-43)', '(48-53)', '(60-100)']

