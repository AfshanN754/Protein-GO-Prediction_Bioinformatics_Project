# Protein GO Term Prediction  

Predicts Gene Ontology (GO) functional annotations from protein sequences using machine learning.

## 🚀 Features  
- **FASTA & GO Term Processing**: Extracts protein IDs and sequences from FASTA files; aligns with GO term annotations.  
- **k-mer Feature Extraction**: Converts sequences into 3-mer frequency vectors.  
- **Multi-Label Classification**: Uses `OneVsRestClassifier` with `MultinomialNB` to predict GO terms.  
- **Evaluation Metrics**: Reports Hamming loss (0.014) and subset accuracy (70.2%).  

## 📦 Dependencies  
- Python 3.10+  
- `biopython`, `scikit-learn`, `pandas`  

## 🔧 Installation  
```bash
pip install biopython scikit-learn pandas

**## 🧪 Usage**
Place your FASTA file (YEAST.fasta) and GO term file (AllProteinswithFunctions-Bakers Yeast.txt) in BioinformaticsProject/.

**## Run the Jupyter notebook:**
jupyter notebook BioinformaticsProject.ipynb

**## 📊 Results**
Metric	        Score
Subset Accuracy	70.2%
Hamming Loss	  0.014

**##📜 License**
MIT
