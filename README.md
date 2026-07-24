# Named Entity Recognition using BERT

## Overview

This project demonstrates Named Entity Recognition (NER) using the Hugging Face Transformers library with the pre-trained `dslim/bert-base-NER` model.

The model identifies named entities from text such as:

- Person
- Organization
- Location
- Miscellaneous entities

---

## Technologies Used

- Python
- Hugging Face Transformers
- BERT
- PyTorch
- Jupyter Notebook

---

## Dataset

No custom dataset is required.

The project uses the pre-trained model:

`dslim/bert-base-NER`

---

## Example

### Input

```text
Sundar Pichai is the CEO of Google and lives in California.
```

### Output

| Entity | Type |
|---------|------|
| Sundar Pichai | Person |
| Google | Organization |
| California | Location |

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Usage

Open the notebook:

```
Name Entity Recognition.ipynb
```

Run all cells.

---

## Model Used

- Hugging Face Transformers
- dslim/bert-base-NER

---

## Future Improvements

- Build a Streamlit web application
- Support custom-trained NER models
- Accept PDF and document inputs
- Visualize entities with colored highlights

---

## Author

Sejal Patole

AI & Machine Learning Enthusiast