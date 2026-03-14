Next Word Prediction using GRU

This project explores how deep learning models can learn patterns in language and predict the next word in a sentence.

The model was trained on text from Shakespeare's *Hamlet* using the NLTK Gutenberg corpus. By learning the sequence patterns in the text, the model can take a phrase like:

`To be or not to`

and predict the most likely next word.

---

Project Motivation

Language models are a fundamental part of modern AI systems such as chatbots, autocomplete tools, and text generation models.

This project was created to better understand:

- How sequence models process text
- How GRU networks handle sequential data
- How to deploy deep learning models using Streamlit

---

Project Structure

```
Next-Word-Prediction-NLP-GRU
│
├── next_word_GRU.py
├── next_word_GRU.h5
├── tokenizer.pickle
├── requirements.txt
└── README.md
```

---

Technologies Used

- Python
- TensorFlow / Keras
- NLTK
- NumPy
- Streamlit

---

How the Model Works

1. The text dataset is cleaned and tokenized.
2. Word sequences are generated from the corpus.
3. Each sequence is padded to a fixed length.
4. The GRU model learns to predict the next word given a sequence.
5. During prediction, the model selects the word with the highest probability.

---

Live Demo

You can try the deployed application here:

https://next-word-prediction-nlp-gru-dkkuctfe7ulkqqb6x5jpxd.streamlit.app/

Enter a short phrase and the model will predict the most probable next word.

---

Example

Input:

```
To be or not to
```

Output:

```
Next word: be
```

(The exact prediction depends on the trained model.)

---

Author

Mohammed Hussain Ali

This project was built as part of my learning journey in Natural Language Processing and Deep Learning.
