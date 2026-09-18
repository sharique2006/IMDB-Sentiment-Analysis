# IMDB-Sentiment-Analysis
Built an IMDB Movie Sentiment Analysis project using Simple RNN, TensorFlow/Keras, and Streamlit. The model classifies movie reviews as Positive or Negative using NLP and word embeddings.
🎬 IMDB Sentiment Analysis using Simple RNN

A deep learning NLP project that classifies IMDB movie reviews as Positive or Negative using a Simple Recurrent Neural Network (RNN).

🚀 Tech Stack:
• Python
• TensorFlow / Keras
• NumPy
• Streamlit
• NLP
• Simple RNN
• Word Embedding

⚙️ Installation:
pip install tensorflow numpy streamlit

▶️ Run:
python -m streamlit run main.py

🧠 How it works:
1. IMDB reviews are loaded using Keras.
2. Reviews are converted into numerical sequences.
3. Sequences are padded to a fixed length.
4. Embedding converts words into vector representations.
5. Simple RNN processes the review sequence.
6. Sigmoid output predicts Positive or Negative sentiment.

📁 Includes:
• Trained RNN model
• Jupyter notebooks
• Streamlit web application
• IMDB sentiment prediction
