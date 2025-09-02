<h1 align="center">🔠 Text Representation & Vectorization</h1>

<p align="center">
  <strong>A complete guide to transforming raw text into numerical representations</strong><br>
  Covers One-Hot Encoding, Bag of Words, N-Grams, TF-IDF, and Word2Vec with visualization.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project demonstrates multiple <strong>text vectorization techniques</strong> used in Natural Language Processing (NLP).  
It converts raw text into structured numerical vectors that can be used by Machine Learning and Deep Learning models.
</p>

<ul>
  <li>🔡 <strong>One-Hot Encoding</strong>: Simple categorical representation</li>
  <li>📝 <strong>Bag of Words (BoW)</strong>: Word occurrence matrix</li>
  <li>📖 <strong>N-Grams</strong>: Capture word sequences (bigrams & trigrams)</li>
  <li>📊 <strong>TF-IDF</strong>: Weighted importance of words</li>
  <li>🧠 <strong>Word2Vec</strong>: Semantic embeddings using <code>gensim</code></li>
  <li>🎨 <strong>3D Visualization</strong>: PCA + Plotly for word embeddings</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>✅ Implements <strong>One-Hot, BoW, N-Grams, TF-IDF</strong></li>
  <li>✅ Builds and trains a <strong>Word2Vec</strong> model on sample data</li>
  <li>✅ Supports <strong>similarity checks</strong> (e.g., Arya ↔ Sansa)</li>
  <li>✅ Uses <strong>PCA</strong> for dimensionality reduction</li>
  <li>✅ Visualizes word embeddings in <strong>3D interactive plots</strong></li>
</ul>

<hr>

<h2>🧠 How It Works</h2>

<ol>
  <li>Encode categorical text with <code>OneHotEncoder</code></li>
  <li>Convert sentences into <strong>Bag of Words</strong></li>
  <li>Capture word sequences with <strong>N-Grams</strong></li>
  <li>Apply <strong>TF-IDF</strong> for weighted representation</li>
  <li>Train a <strong>Word2Vec</strong> model on tokenized sentences</li>
  <li>Reduce dimensions with <strong>PCA</strong></li>
  <li>Visualize embeddings using <strong>Plotly 3D scatter plots</strong></li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
text-representation-vectorization/
├── Text Representation and Vectorization.ipynb   ← Main Notebook
├── README.md                                     ← Project Documentation
└── requirements.txt                              ← Dependencies 
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  
  <pre><code>git clone https://github.com/yourusername/text-representation-vectorization</code></pre>

  <li>Install dependencies</li>

  <pre><code>pip install pandas numpy scikit-learn nltk gensim plotly</code></pre>

  <li>Run the notebook in Google Colab or Jupyter</li>

  <pre><code>jupyter notebook "Text Representation and Vectorization.ipynb"</code></pre>
</ol>

<hr>

<h2>🧪 Sample Output</h2>

- One-Hot Encoded:  
  <code>[[1. 0. 0.] [0. 1. 0.] [0. 0. 1.]]</code>  

- Bag of Words (Vocabulary):  
  <code>{'people': 2, 'watch': 3, 'movie': 1, 'mehadi': 0, 'write': 4, 'comment': 5}</code>  

- TF-IDF Matrix:  
  <code>[[0.58 0.58 0.58] [0.71 0.71 0.00] ... ]</code>  

- Word2Vec Similarity:  
  <code>similarity('arya','sansa') → 0.76</code>  

- 3D Embedding Visualization:  
  <i>Interactive scatter plot of words in vector space</i>  

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehadi Hassan</strong> as part of an NLP project on text representation & feature engineering.
</p>

<hr>

<p align="center">⭐ Star this repo if you found it helpful for your NLP journey!</p>
