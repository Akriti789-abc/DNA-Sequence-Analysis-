# 🧬 DNA Sequence Analysis

## 📖 Overview
This project performs DNA sequence analysis using Python. It reads FASTA files and extracts meaningful biological insights such as nucleotide frequency, GC/AT content, motif detection, ORF identification, and amino acid composition.

---

## 📂 Data
- **Input File:** `cds.fna22.txt`
- **Download Source:** NCBI → Nucleotide Database → Export as **FASTA (.fna / .fasta / .fa)** file  
   
---

## 🔬 Analysis Performed
- Nucleotide frequency calculation (A, T, G, C)  
- GC and AT content percentage  
- Motif search (default motif: `ATG`)  
- ORF detection and positional mapping  
- DNA-to-protein translation  
- Amino acid composition analysis  

---

## 📊 Key Findings
| Feature | Result |
|----------|---------|
| GC Content | **41.29%** |
| AT Content | **58.71%** |
| Total ORFs Found | **115** |
| Dominant Amino Acids | **Serine (S)**, **Glutamic Acid (E)** |
| Inference | Moderately stable DNA with multiple coding regions |

---

## 🎯 Purpose
To automate DNA sequence examination and enable faster, accurate insights into genomic composition and protein-coding potential for research and biotechnology applications.

---

## ⚙️ Dependencies
- Python ≥ 3.10  
- Biopython  
- Google Colab (for file upload interface)
- Collections (Python built-in module)

---

## 🚀 Usage

1. Upload your DNA sequence file in **FASTA format** (e.g., `cds.fna22.txt`).
2. Run the analysis script:
   ```python
   python dna_analysis.py

---

## 👩‍🔬 Author

|Name:Akriti Saini|  
|B.Tech Biotechnology|  
|Institution: Banasthali Vidyapeeth|  

