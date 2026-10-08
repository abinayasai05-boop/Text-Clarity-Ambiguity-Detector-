# Text Clarity & Ambiguity Detector

## 📌 Project Overview

**Text Clarity & Ambiguity Detector** is a Natural Language Processing (NLP) based application that analyzes written text and identifies problems that may make the text difficult to understand.

The system detects vague words, uncertain language, ambiguous references, long sentences, repeated words, and readability issues. It generates a **Clarity Score** and **Ambiguity Score** along with suggestions for improving the text.

## 🎯 Objectives

- Detect unclear and ambiguous text
- Identify vague words and expressions
- Detect uncertain language
- Identify potentially ambiguous pronouns
- Analyze sentence length
- Measure text readability
- Generate a clarity score
- Provide useful improvement suggestions

## ✨ Features

- 🔍 **Clarity Detection**
- ⚠️ **Ambiguity Detection**
- 📝 **Vague Word Detection**
- 💬 **Uncertain Language Detection**
- 🔗 **Pronoun Ambiguity Detection**
- 📏 **Sentence Length Analysis**
- 📖 **Readability Analysis**
- 📊 **Clarity & Ambiguity Scores**
- 💡 **Improvement Suggestions**
- 📋 **Multiple Text Analysis**
- 📈 **Clarity Score Visualization**

## 🛠️ Technologies Used

- Python
- Google Colab
- Natural Language Processing (NLP)
- NLTK
- TextStat
- Pandas
- Matplotlib
- IPyWidgets
- Regular Expressions

## 🔄 Working Process

```text
User Input
    ↓
Text Preprocessing
    ↓
Word & Sentence Analysis
    ↓
Vague Word Detection
    ↓
Uncertain Language Detection
    ↓
Pronoun Ambiguity Detection
    ↓
Sentence Length Analysis
    ↓
Readability Analysis
    ↓
Clarity Score Calculation
    ↓
Final Classification
    ↓
Suggestions for Improvement
```

## 📊 Classification

| Clarity Score | Result |
|---|---|
| 80–100 | Clear |
| 60–79 | Needs Improvement |
| 0–59 | Ambiguous |

## 🧪 Example

### Input

```text
I will send the thing later and maybe they can check it.
```

### Detected Problems

- Vague word: `thing`
- Vague expression: `later`
- Uncertain word: `maybe`
- Ambiguous reference: `they`
- Ambiguous reference: `it`

### Output

```text
Clarity Score: Needs Improvement
Ambiguity Score: High

Suggestions:
- Replace vague words with specific information.
- Clearly identify who "they" refers to.
- Clearly identify what "it" refers to.
- Use a specific deadline instead of "later".
```

## 📦 Installation

Run the following command in Google Colab:

```python
!pip install -q textstat nltk pandas matplotlib
```

Then run the project code cells provided in the notebook.

## ▶️ How to Run

1. Open **Google Colab**.
2. Create a new notebook.
3. Install the required libraries.
4. Run the import and analysis code.
5. Enter your text.
6. Click **Analyze Text**.
7. View the clarity score, ambiguity score, detected problems, and suggestions.

## 📁 Project Structure

```text
Text-Clarity-Ambiguity-Detector/
│
├── Text_Clarity_Ambiguity_Detector.ipynb
├── README.md
└── requirements.txt
```

## 🚀 Future Enhancements

- AI-based sentence rewriting
- Context-aware ambiguity detection
- Grammar correction
- Multilingual text analysis
- Machine learning based clarity classification
- Voice input and speech analysis
- Web application interface
- Transformer-based NLP models
- Automatic before/after text comparison

## 👩‍💻 Project Type

**TSA – Text/Speech Analytics Project**

**Domain:** Natural Language Processing / Artificial Intelligence

**Platform:** Google Colab

## 📄 License

This project is created for educational and academic purposes.
