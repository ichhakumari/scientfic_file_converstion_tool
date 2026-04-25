# Scientfic_File_Converstion_Tool : CONV Ana

live : https://web-production-4e327.up.railway.app/

A web-based file conversion platform for cheminformatics and drug discovery workflows. This tool allows users to convert between various molecular file formats such as SMILES, MOL2, SDF, and visualize them using 2D molecular images.

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

<img width="1365" height="603" alt="image" src="https://github.com/user-attachments/assets/c6bef275-fb94-450e-a299-0eeb0c094173" />

<img width="1362" height="605" alt="image" src="https://github.com/user-attachments/assets/07679520-bf41-4a9b-9909-c1c493f65c19" />

<img width="1365" height="596" alt="image" src="https://github.com/user-attachments/assets/a7c26211-23de-486f-af97-aec2832d064d" />

<img width="1353" height="592" alt="image" src="https://github.com/user-attachments/assets/55abf806-71a1-4cea-b082-7f2a9db0f425" />

<img width="1365" height="599" alt="image" src="https://github.com/user-attachments/assets/afdecae3-3cb7-4684-b84b-171e6da5e2dc" />



