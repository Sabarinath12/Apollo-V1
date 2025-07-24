A deep learning model for audio classification, designed to detect AI-generated music.

Model architecture : EfficientNetB0 (Transfer Learning)

Framework: TensorFlow / Keras

Task: Binary Classification (AI Music vs. Real Music)

Input: Mel Spectrograms (224x224) generated from audio files.

Training Data: Trained on a balanced dataset of thousands of modern songs from sources like the Free Music Archive, NCS, and the Suno AI dataset on Kaggle, all standardized to a consistent bitrate.


<img width="800" height="600" alt="roc_curve" src="https://github.com/user-attachments/assets/26d26881-a097-49e9-ab73-664f2b87605c" />
