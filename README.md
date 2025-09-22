# 🏥 Hospital Registry Program (Tkinter Learning Project)

This is an **early learning project** where I built a simple **patient registry system** using Python’s `tkinter` for GUI and text file storage for persistence.  
The goal was to practice **GUI programming, file handling, validation logic, and structuring larger programs**.

---

## 🚀 Features & Functionality
- **Registration System**
  - Collects patient details: name, birthday, gender, phone number, and address.  
  - Auto-assigns a **unique patient number**, doctor, and room number.  
  - Saves patient info into `data.txt`.  

- **Doctor Interface**
  - View all registered patients.  
  - Search by patient number.  
  - Discharge patients (removes them from `data.txt`).  

- **Patient Interface**
  - Edit personal info: **address** or **phone number**.  
  - Patient number validation before edits.  

- **Validation & Error Handling**
  - Phone number must be exactly **10 digits**.  
  - Ensures no empty fields.  
  - Gender must be `male`, `female`, or `other`.  
  - Error messages shown in the GUI.  

- **Data Management**
  - `data.txt` serves as a simple persistent “database.”  
  - Records stored as space-separated lines.  
  - Includes functions to read, write, update, and delete records.  

---

## 🧠 What I Practiced & Learned
- **Tkinter Basics**
  - Creating windows, labels, entries, buttons, and canvas.  
  - UI positioning with `create_window` and shapes.  

- **File Handling in Python**
  - Appending (`a`), overwriting (`w`), and reading (`r`).  
  - Converting lines into lists (`split`) for easy record manipulation.  

- **Validation Logic**
  - Input checks for empty fields, valid gender, and 10-digit numbers.  

- **Program Structure**
  - Modular functions (`registration_validation`, `assign_doctor`, `change_address`, etc.).  
  - Managing global Tkinter widget references.  

- **Randomization**
  - Assigns doctors and room numbers randomly with constraints.  

---

## 📂 Project Structure
```
registry.py   # Main Tkinter program
data.txt      # Patient data storage (starts empty)
README.md     # Documentation
```

---

## 🛠️ Installation & Usage
```bash
# Clone the repository
git clone https://github.com/JihanChowdhury334/registry-program.git
cd registry-program

# Run the program
python registry.py
```

⚠️ Make sure an empty `data.txt` file exists in the project folder before running.

---

## 🎯 Purpose
This project is **not production-ready**, but an **early learning exercise** that helped me practice:
- GUI development with Tkinter  
- File-based persistence in Python  
- Input validation and error handling  
- Breaking down a large program into smaller functions  
