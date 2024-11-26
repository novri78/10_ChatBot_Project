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