# Evolution of Romantasy
Comparative analysis between *Empyrean* (2023–2025) and classic sagas such as *The Mortal Instruments* (2007–2014).

## 📁 Structure
The repository is organized according to best practices for reproducible data science:

- `scripts/`: modular and autonomous code divided into 6 sequential scripts (preprocessing, sentiment analysis, topic modeling, character networks, recommendation system, etc.).
- `data/external/`: goodreads_rating.xlsx file with actual Goodreads ratings for 9 popular sagas.
- `data/raw/`: original textual corpus composed of books from *Empyrean*, *Shatter Me*, and *The Mortal Instruments* (for academic purposes only).
- `data/processed/`: serialized intermediate objects (.rds, .csv) that enable reproducibility without recalculating the entire workflow.
- `output/graficos/`: key visualizations ready to include in the report (sentiment evolution, character networks, narrative profile, comparative ratings).
- `informe_final.pdf`: deliverable document with hypothesis, methodology, results, and narrative interpretation.

## 📊 Key Results
- *Empyrean* shows a more collective narrative (network density = 2.04) compared to the individualism of *Shatter Me*.
- *Empyrean's* Goodreads rating (4.50) exceeds that of *Shadowhunters* (4.18), confirming its current resonance.
- Recommendation system based on emotional-structural profile.

## 📝 Note on Data
The analysis was performed with personal copies obtained legally.
