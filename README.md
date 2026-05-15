# AI Tagline Generator using FLAN-T5

An NLP-based AI system that generates creative and context-aware brand taglines using Google's FLAN-T5 transformer model. The project fine-tunes a sequence-to-sequence language model on branding and slogan datasets to generate high-quality marketing taglines from company information.

---

## Features

- Generate AI-powered brand taglines
- Fine-tuned FLAN-T5 model
- Context-aware slogan generation
- Uses company name, category, and description
- Creative text generation with sampling strategies
- Custom dataset training support

---

## Model Used

- Google FLAN-T5 Base
- Hugging Face Transformers
- Seq2Seq Text Generation Architecture

---

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Pandas
- Datasets Library
- Google Colab

---

## Dataset Format

The dataset contains:

| Column | Description |
|---|---|
| company | Company/brand name |
| category | Business category |
| description | Company description |
| slogan | Target tagline |

Example:

```csv
company,category,description,slogan
Nike,Fashion,Sportswear and athletic products,Just Do It
