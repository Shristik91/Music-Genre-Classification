🎵 Music Genre Classification Using Machine Learning

📌 Project Overview

Music Genre Classification is a Machine Learning project that automatically identifies the genre of a music track based on its audio features.

The system analyzes audio signals, extracts important features, and uses a trained Machine Learning model to classify music into different genres.

This project demonstrates the application of Machine Learning and audio signal processing in music analysis.

🎯 Objectives

- To classify music into different genres automatically.
- To extract meaningful features from audio files.
- To train and evaluate Machine Learning models.
- To improve music classification using audio signal processing.
- To build an easy-to-use music genre prediction system.

🛠️ Technologies Used

- Programming Language: Python
- Libraries: NumPy, Pandas, Librosa
- Machine Learning: Scikit-learn
- Data Visualization: Matplotlib, Seaborn
- Frontend: Streamlit (if implemented)
- Development Environment: Jupyter Notebook / VS Code

🎼 Music Genres

The model can be trained to classify music into genres such as:

- Blues
- Classical
- Country
- Disco
- Hip-Hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

⚙️ Project Workflow

1. Dataset Collection: Collect music audio files for different genres.
2. Data Preprocessing: Load and prepare audio files.
3. Feature Extraction: Extract audio features such as MFCC, Chroma, Spectral Centroid and Zero Crossing Rate.
4. Model Training: Train a Machine Learning classification model.
5. Model Evaluation: Evaluate the model using suitable performance metrics.
6. Prediction: Predict the genre of new audio files.

🧠 Machine Learning Algorithms

Depending on the implementation, the project can use:

- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree

📂 Project Structure

Music-Genre-Classification/
│
├── dataset/
│   ├── blues/
│   ├── classical/
│   ├── country/
│   └── ...
│
├── models/
│   └── trained_model.pkl
│
├── notebooks/
│   └── music_genre_classification.ipynb
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore

Modify the structure according to the actual files in your repository.

🚀 Installation and Execution

1. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

2. Navigate to the Project Folder

cd Music-Genre-Classification

3. Install Required Libraries

pip install -r requirements.txt

4. Run the Application

If using Streamlit:

streamlit run main.py

📊 Expected Output

The system accepts an audio file, processes its audio features, and predicts the corresponding music genre.

Example:

Input: Music Audio File

Predicted Genre: Jazz

The example is illustrative, not an actual model result.

🔮 Future Enhancements

- Integrate Deep Learning models such as CNN.
- Improve classification performance.
- Support more music genres.
- Develop a user-friendly web application.
- Enable real-time audio classification.

🎓 Learning Outcomes

- Understanding Machine Learning classification.
- Working with audio datasets.
- Audio feature extraction using Librosa.
- Model training and evaluation.
- Python application development.

👩‍💻 Author

Shristi kumari

B.Tech – Computer Science and Engineering (AI & ML)

⭐ Acknowledgement

This project was developed as part of learning and exploring Machine Learning, Python programming, and audio signal processing.

---

If you find this project useful, consider giving it a ⭐ on GitHub!
