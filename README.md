# Scandinavian Flavor Networks

> **Note:** This repository is for showcasing the research workflow and technologies used.  
> The actual code, data, and trained models are private due to research and IP restrictions.

---

## Overview

This project explores how flavor compounds have evolved across time and region in Scandinavian cuisine. The team is supervised by Professor Tangherlini (UC Berkeley), and consists of both undergraduate and graduate students. The pipeline processes scanned cookbook PDFs, extracts and translates recipes, maps ingredients to a flavor compound database, and produces insights through neural network models.

---

## Methodology

1. **Text Extraction**  
   - Parse scanned PDFs of historic Scandinavian cookbooks.
   - Convert to machine-readable text.

2. **Chunking and Translation**  
   - Break long texts into manageable chunks.
   - Translate to English via LLM calls (OpenAI API).

3. **Ingredient Normalization**  
   - Extract raw ingredients and relative quantities.
   - Standardize ingredient names and remove noise.

4. **Flavor Compound Mapping**  
   - Link each ingredient and cooking method to a curated database of flavor compounds.

5. **Analysis and Modeling**  
   - Build neural networks to:
     - Analyze flavor compound trends over time.
     - Compare regional flavor preferences across Scandinavia.

---

## Tech Stack

- **Language:** Python 3.x
- **Libraries:** pandas, numpy, scikit-learn, pytesseract (for OCR), matplotlib/seaborn
- **LLM API:** OpenAI GPT models for translation and semantic tasks
- **Database:** CSV / SQL flavor compound mappings
- **Modeling:** Simple feed-forward neural networks (PyTorch/Keras)

---

## Sample Results

- Temporal trends showing the rise and fall of key flavor profiles (for example, smoked flavors, fermentation).
- Regional comparisons revealing how Sweden, Norway, and Denmark differ in their ingredient preferences.
- Embedding visualizations showing clustering of similar flavor profiles.

*(The actual scripts are private — see `PRIVATE_REPO.md` for internal structure if you have access.)*

---

## Ethical and Legal Considerations

- Original cookbook PDFs are protected works — we use them for research only.
- Translations and outputs are not redistributed publicly.
- The pipeline code and model weights remain private to comply with research IP rules.

---

## Future Work

- Automate full pipeline with a CLI interface.
- Expand dataset beyond Scandinavian cuisine.
- Perform deeper statistical analysis on ingredient co-occurrence networks.
- Explore cross-cultural flavor evolution comparisons.

---

## Author and Attribution

Developed by **[The Flavor Networks Team]** as part of a research project on computational gastronomy.  
For questions or collaboration, reach out via [LinkedIn](https://linkedin.com/in/romundset).

This repository is shared under a **CC BY-NC 4.0** license — you may share and adapt the methodology for non-commercial use with attribution.

