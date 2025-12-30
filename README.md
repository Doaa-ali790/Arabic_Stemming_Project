# Arabic Stemming Project

This project aims to compare five Arabic stemming algorithms:

1. Khoja Stemmer
2. Light Stemmer
3. ISRI Stemmer
4. Kamel Stemmer
5. Farasa Stemmer

## Project Structure

Arabic_Stemming_Project/
│
├── input.txt # Original Arabic text for testing
├── gold_standard.txt # Reference roots for comparison
│
├── outputs/ # Folder to store stemmer outputs
│ ├── output_khoja.txt
│ ├── output_light.txt
│ ├── output_isri.txt
│ ├── output_kamel.txt
│ └── output_farasa.txt
│
├── stemmers/ # Stemmer scripts
│ ├── khoja_stemmer.py
│ ├── light_stemmer.py
│ ├── isri_stemmer.py
│ ├── kamel_stemmer.py
│ └── farasa_stemmer_demo.py
│
├── comparison.py # Script to compare stemmers
├── comparison_results.csv # Final comparison results
│
└── README.md # This file

markdown


## How to Use

1. Place the Arabic text you want to test in `input.txt`.
2. Place the reference roots in `gold_standard.txt`.
3. To run each stemmer:
   - Open Jupyter Notebook or use Python.
   - Run the script for the desired stemmer from the `stemmers/` folder.
4. To compare all stemmers:
   - Run `comparison.py`.
   - It will generate `comparison_results.csv` and display a comparison table in the console.

## Requirements

- Python 3.10+
- Libraries: `pandas`, `farasa`, `tabulate` (optional)

```bash
pip install pandas tabulate farasa
Notes
