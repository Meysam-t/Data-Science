# Leadership Categorization Analysis

Analysis of short written explanations of leadership behavior: word counts, categorization, and agreement across raters.

## Data

- `data.csv` — one row per explanation, with `Category 1` and, where an explanation spans more than one category, `Category 2`.
- `word_counts.csv` / `word_counts.xlsx` — word-frequency counts.

## Notebook

`leadership.ipynb` (Python, pandas) runs the analysis:

1. Word counts over the explanations.
2. Categorization analysis across raters.
3. Consensus vs. disagreement: cases where all raters agree vs. cases where they do not.

## Outputs

- `data_categorization_analysis*.xlsx` — categorization results, including author splits and an LLM-assisted pass (`data_categorization_analysis_llm.xlsx`).
- `categorized_explanations*.xlsx` — explanations with their assigned categories.

## Run it

Open `leadership.ipynb` in Jupyter. Requires pandas (and openpyxl for the Excel outputs).
