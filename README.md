# 🧬 Active Site Residue Explorer

This project reads a **protein `.pdb` file with a bound ligand**, and finds amino acid residues that are **within 5 Å** of the ligand atoms — highlighting likely active site residues.

It also generates a **3D visualization** using Py3Dmol, showing:
- 🩸 Residues near the ligand as red sticks
- 🧬 The rest of the protein as a cartoon

---

## 🚀 Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/active-site-residue-explorer/blob/main/Active_Site_Residue_Explorer.ipynb)

---

## 🔬 Features

✅ Upload a PDB file with a ligand or cofactor (HETATM)  
✅ Finds residues within **5 Å** of ligand atoms  
✅ Lists:
- Chain ID
- Residue name + number
- Distance to ligand  
✅ Interactive **3D visualization**:
- Cartoon for protein
- Red sticks for nearby residues (likely active site)

---

## 🛠 Tools Used

- Python
- BioPython (PDB module)
- Py3Dmol
- Pandas
- Google Colab

---

## 👨‍💻 Author

**Shubkarandeep Singh Judge**  
🎓 M.Sc. Biotechnology | 💻 Minor in Computer Science  
🌐 [GitHub: shubh-1909](https://github.com/shubh-1909)

---

## 📜 License

Licensed under the MIT License.
