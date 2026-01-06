
# PDB Batch v1

**PDB Batch v1** is an interactive, notebook-based bioinformatics pipeline for
deep structural and mutational comparison of wild-type and mutant protein
structures using PDB files.

---

## ✨ Key Features
- Chain-aware sequence extraction from PDB structures
- Frameshift-safe global sequence alignment
- Accurate detection of substitutions, insertions, and deletions
- Color-coded mutation-mapped sequence visualization
- SIFT-like and PolyPhen-like functional impact prediction
- Physicochemical profiling (MW, pI, GRAVY, stability)
- Ramachandran plot generation
- Side-by-side interactive 3D structure visualization
- Direct redirection to PolyPhen-2 and SIFT web tools

---

## 🎨 Mutation Colouring System

- **Black**: Conserved (unchanged) residues  
- **Red**: Deleted residues or lost wild-type residues  
- **Green**: Inserted residues (gain in mutant)  
- **Purple**: Substituted mutant residues  

This enables instant visual interpretation of mutation landscapes.

---

## 🧬 Sequence-to-Structure Animation (Code-Based)

```text
WT:  MALWMRLLPLLALLALWGPDPAAAFVNQHL...
MT:  MALWMRLLPLLALLALWGPDPA--FVNQHL...
      ||||||||||||||||| |||||  |||||
LOSS:                 ^^
GAIN:                    ++
```
This text-based animation illustrates mutation flow without static images.

---

## 🚀 Usage
1. Run the notebook in Google Colab
2. Upload wild-type and mutant PDB files
3. Review mutation tables and color-mapped sequences
4. Explore structural and functional impacts interactively

---

## 🧪 Scientific Applications
- Variant effect interpretation
- Protein engineering
- Cancer mutation analysis
- Structural bioinformatics education

---

## 👤 Author
**Muhammad Sohaib Hassan**
