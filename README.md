# 🇷🇼 Kinyarwanda Speech Translation Evaluation Framework

This project implements a **qualitative evaluation pipeline** for Kinyarwanda speech translation outputs. It uses **textual references and hypothesis files** to compute a range of NLP evaluation metrics including BLEU, CHRF, WER, CER, and ROUGE.

---

## 🎯 Objectives

- Evaluate **machine-generated Kinyarwanda translations**
- Compare system predictions with gold references
- Compute standardized NLP metrics for quality assessment
- Support batch evaluation from CSV datasets

---

## 🔍 Key Features

- ✅ BLEU and CHRF (n-gram overlap)
- ✅ WER and CER (edit distance-based metrics)
- ✅ ROUGE-1, ROUGE-2, ROUGE-L (recall-oriented summarization metrics)
- ✅ Command-line driven evaluation
- ✅ CSV output of all metric scores for easy analysis

---

## 🧰 Requirements

Install the required packages:

```bash
pip install evaluate pandas numpy sacrebleu rouge_score jiwer
