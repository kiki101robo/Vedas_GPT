# Vedas_GPT
# ENPM703 Final Project: Advanced NLP with Lifelong Learning Models

## Project Overview
This project explores the application of various Language Learning Models (LLMs) for processing and understanding Sanskrit texts. We evaluate models like MuRIL, BERT, SanBERT, and ByT5 to analyze their efficiency in handling the complexities of Sanskrit through fertility score metrics.

### Team: RoboTech Terps
- **Suraj Kalwaghe**
- **Tanmay Pancholi**
- **Kirti Kishore**

### Models Evaluated
- **MuRIL**: Trained specifically on Indian languages.
- **BERT**: General-purpose multilingual model.
- **SanBERT**: Fine-tuned specifically for Sanskrit.
- **ByT5**: Byte-level model trained on multiple languages.

## Objective
To determine the most efficient model for tokenizing Sanskrit texts by measuring the fertility score, which indicates the number of tokens generated per word by a tokenizer.

## Methodology
1. **Tokenizer Loading**: Utilize different tokenizers corresponding to each model.
2. **Fertility Score Calculation**:
   - Tokenize Sanskrit texts.
   - Calculate the average number of tokens per word.
3. **Visualization**:
   - Generate bar graphs comparing the fertility scores across different models.

## Results
The project includes detailed analysis and visual representations of how each model performs with respect to handling Sanskrit texts. Models like SanBERT and MuRIL show lower fertility scores, indicating higher efficiency in tokenization specific to Sanskrit.

### Fertility Score Insights
- **MuRIL and SanBERT**: Perform best, suggesting suitability for applications involving Sanskrit.
- **BERT**: Shows higher fertility scores, indicating less efficiency compared to language-specific models.
- **ByT5**: While comprehensive, its byte-level tokenization leads to higher token counts, which may not be ideal for all tasks.

![Fertility Score Comparison](model_vs_fertility.png)

## Files and Execution
- **[ENPM703_FinalProj.pdf]()**: Detailed project report.
- **Jupyter Notebook**: Contains all the scripts for running the analyses, including tokenization and fertility score calculations.

## Usage
To run the analysis:
```bash
python run_analysis.py
