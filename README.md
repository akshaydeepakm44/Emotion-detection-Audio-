# Emotion-detection

This Python-based model analyzes audio features (pitch, tone, intensity) from uploaded CSV files to predict the user's emotional state (happy, sad, angry, neutral). Ideal for customer service, mental health apps, or voice assistants!

How It Works
Input: Users upload a CSV file with audio features (e.g., MFCCs, spectral centroid, chroma).

Processing:

Uses Librosa for feature extraction (if raw audio is provided).

Scikit-learn/TensorFlow for mood classification (pre-trained model).

Output: Returns the predicted mood + confidence scores.
