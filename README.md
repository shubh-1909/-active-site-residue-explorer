# 🧬 Active Site Residue Explorer

This project reads a **protein `.pdb` file with a bound ligand**, and finds amino acid residues that are **within 5 Å of the ligand atoms** — highlighting likely active site residues.

It also generates an interactive **3D visualization** using Py3Dmol:
- 🧬 Protein shown as a cartoon
- 🩸 Nearby residues (likely active site) highlighted as red sticks

---

## 🚀 Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/active-site-residue-explorer/blob/main/Active_Site_Residue_Explorer.ipynb)

---

## 🔬 Features

✅ Uploads a `.pdb` file containing a protein + ligand (HETATM)  
✅ Identifies all residues **within 5 Å of the ligand**  
✅ Outputs a clean table listing: 
- Chain ID
- Residue name & number
- Approx distance to ligand  
✅ Visualizes structure in 3D with Py3Dmol:
- Cartoon backbone
- Red sticks on active site residues

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

This project is licensed under the MIT License.
