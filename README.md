🌳 Tree Audio Classifier
🎧 Classify tree species by analyzing their sounds using Machine Learning & Audio Processing.

📌 Overview
This project predicts tree species (like Mango, Neem, Coconut, Palm, Peepal, Ashok) from their audio recordings. It uses MFCC feature extraction with librosa and trains a Random Forest Classifier. The model is deployed using Gradio for an interactive web interface.

✅ Features
✔ Audio-based tree identification
✔ MFCC feature extraction
✔ Random Forest classification
✔ Gradio-powered user interface

📂 Dataset
Total samples: 48 audio files
Each species: Multiple recordings
Augmented with pitch shift & speed change

🛠 Tech Stack
Python
Librosa (Audio Processing)
Scikit-learn (Model Training)
Gradio (Web Interface)

⚙ How to Run
Open on Colab using the above button
Upload your tree audio dataset or use sample files
Train the model (Steps in notebook)
Launch the Gradio App for real-time predictions

🔍 How to Use
Upload a .wav audio file
The model predicts the tree species
View results in real-time on Gradio UI

📊 Results
Accuracy: 61.5%
Model: Random Forest Classifier
Saved as: tree_sound_model.pkl

🚀 Future Enhancements
✅ Add more species
✅ Use CNN or Deep Learning models
✅ Deploy on Hugging Face Spaces
