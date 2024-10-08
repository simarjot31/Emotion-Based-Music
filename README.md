# Emotion-Based-Music
This code creates a Streamlit web application called "Emotion Based Music Recommender," which detects emotions using real-time webcam footage and suggests songs based on those emotions. It utilizes MediaPipe's Holistic model for facial and hand landmark detection, along with a pre-trained Keras model for emotion classification. Users can input their preferred language and singer, and the app opens a YouTube search for songs that match the detected emotion. The predicted emotion is displayed on the video feed, and the app maintains user session states to track whether an emotion has been captured. Overall, it provides an interactive way to recommend music based on users' emotions.

# Implementation Steps
  1. Set Up Environment:
     Install required libraries:
        **pip install streamlit streamlit-webrtc opencv-python numpy mediapipe keras**
     Ensure you have the model (model.h5) and labels (labels.npy) files available in your project directory.

  2. Launch the App:
     Run the app from the command line:
        **streamlit run app.py**
