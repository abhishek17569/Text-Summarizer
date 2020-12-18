# Text Summarization
Automatic data summarization is part of machine learning and data mining. The main idea of summarization is to find a subset of data which contains the "information" of the entire set. Such techniques are widely used in industry today

Setting up the Python environment

---
First, install the following packages.



Next, install the following Pip packages.

```bash
pip install flask
pip install -r requirements.txt
pip install bert-extractive-summarizer
pip install spacy==2.1.3
pip install transformers==2.2.2
pip install neuralcoref
python -m spacy download en_core_web_md
 
 ```

Start the application,
```bash
python run.py
```
Open "http://127.0.0.1:5000/" in browser.

