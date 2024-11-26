Persiapan Lingkungan
# Software:
- Python 3.8+,
- Flask/FastAPI untuk backend.
- Streamlit untuk UI.
- Pandas, Numpy untuk analitik data.
- TensorFlow/PyTorch untuk AI.
- Dataset: File sharia_datasets.csv sebagai data utama. Dataset ini akan diproses untuk pelatihan model chatbot.
- Hardware: Optimasi dengan QLoRA memungkinkan pelatihan dilakukan di laptop tanpa GPU.

# Tahap Data Analytics dan Preprocessing
- Analisis Dataset:
    - Load dataset menggunakan Pandas: pd.read_csv("sharia_datasets.csv").
  
- Analisis distribusi data:
    - Kolom "question" untuk input pertanyaan.
    - Kolom "answer" untuk output jawaban.
    - Deteksi anomali, missing values, atau data duplikat.

- Preprocessing Dataset:
    - Konversi teks menjadi lowercase.
    - Tokenisasi dengan library seperti nltk atau spaCy.
    - Penyusunan ulang data untuk mendukung pelatihan model.

_[In English]_ :

# Environment Preparation

- Software:

    - Python 3.8+

    - Flask/FastAPI for the backend

    - Streamlit for the UI

    - Pandas, Numpy for data analytics

    - TensorFlow/PyTorch for AI

    - Dataset: sharia_datasets.csv as the primary data source. This dataset will be processed for chatbot model
      training.

    - Hardware: Optimization with QLoRA allows training to be performed on a laptop without a GPU.

# Data Analytics and Preprocessing Stage

- Dataset Analysis:

    - Load dataset using Pandas: pd.read_csv("sharia_datasets.csv").

    - Data Distribution Analysis:

        - Column question for input questions.

        - Column answer for output answers.

    - Detect anomalies, missing values, or duplicate data.

- Dataset Preprocessing:

    - Convert text to lowercase.

    - Tokenization with libraries like nltk or spaCy.

    - Reorganize data to support model training.