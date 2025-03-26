# Scientfic_File_Converstion_Tool

A web-based file conversion platform for cheminformatics and drug discovery workflows. This tool allows users to convert between various molecular file formats such as SMILES, MOL2, SDF, and visualize them using 2D molecular images.

---

## 🌐 Live 

https://web-production-b4c53.up.railway.app/

---

## 🚀 Features

- ✅ Convert SMILES to MOL2 and other chemical formats
- 👁️ View molecular structures as 2D PNG images
- 🛠️ Backend integrated with **RDKit** and **Open Babel**
- 📁 User-friendly interface inspired by tools like *I Love PDF*
- ✏️ Input validation and error handling for unsupported or malformed inputs

---

## 📄 Supported File Formats

- **Input**: SMILES (.smi), SDF, MOL2, MOL
- **Output**: MOL2, SDF, MOL, PNG image of the molecule

---

## ⚖️ Technology Stack

- **Frontend**: HTML/CSS + Django templates 
- **Backend**: Django, RDKit, Open Babel
- **Image Generation**: RDKit's 2D depiction tools

---

## 📚 How It Works

1. User uploads a molecular file or pastes a SMILES string
2. Tool validates the input structure
3. RDKit parses and converts the molecule
4. Open Babel handles conversion to desired output formats
5. RDKit renders the molecule as PNG for side-by-side visualization

---

## 📅 Example Use Case

A researcher uploads a SMILES string like `CCO`, and chooses MOL2 as output. The system returns:

- A MOL2 file to download
- A PNG image showing the 2D structure of ethanol

---


## 🚫 Limitations

- Currently supports only 2D image rendering
- Conversion depends on installed RDKit/Open Babel capabilities
- Not all edge cases (e.g., malformed input) are fully covered

---


