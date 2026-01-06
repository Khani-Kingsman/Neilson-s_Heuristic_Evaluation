# Nielsen HCI Heuristic Evaluation Tool (GUI + PDF Export)

A **Python-based desktop application** that performs **heuristic usability evaluation** of websites using **Nielsen’s 10 Usability Heuristics**.  
The tool provides a **graphical user interface (GUI)** for entering a website URL, automatically analyzes the page, displays the results, and allows exporting the evaluation as a **PDF report**.

This project is suitable for **HCI coursework, usability analysis, academic research, and portfolio projects**.

---

## 📌 Features

- 🌐 Analyze any public website using a URL
- 🧠 Rule-based evaluation using **Nielsen’s 10 HCI heuristics**
- 🖥️ User-friendly **GUI (Tkinter)**
- 📋 Scrollable heuristic evaluation report
- 📄 **Export evaluation results as a PDF**
- 🎓 Designed for **educational and research use**

---

## 🧪 Nielsen’s 10 Usability Heuristics Covered

1. Visibility of System Status  
2. Match Between System and the Real World  
3. User Control and Freedom  
4. Consistency and Standards  
5. Error Prevention  
6. Recognition Rather Than Recall  
7. Flexibility and Efficiency of Use  
8. Aesthetic and Minimalist Design  
9. Help Users Recognize, Diagnose, and Recover from Errors  
10. Help and Documentation  

> ⚠️ Note:  
> This tool provides **automated heuristic indicators**.  
> Final usability conclusions should still involve **human judgment**.

---

## 🛠️ Technologies Used

- **Python 3.12+**
- **Tkinter** – Graphical User Interface
- **Requests** – HTTP requests
- **BeautifulSoup4** – HTML parsing
- **ReportLab** – PDF report generation

---

## 📦 Installation & Setup

### 1️⃣ Clone or Download the Project

You may either clone the repository:
```bash
git clone https://github.com/Khani-Kingsman/Neilson-s_Heuristic_Evaluation
cd Neilson-s_Heuristic_Evaluation
```
# How to Run
### Run the application using:
```bash
python "Heuristic Evaluation.py"
```
# (Optional but Recommended) Create a Virtual Environment
### Creating a virtual environment helps keep dependencies isolated.
```bash
python -m venv .venv
```
# Activate the Virtual Environment
### Windows (PowerShell):
```bash
.venv\Scripts\Activate.ps1
```
### If PowerShell blocks activation, run once:
```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```
### When activated, you should see:
```bash
(.venv) PS D:\>
```
# Install Dependencies
### Install the required Python libraries:
```bash
python -m pip install requests beautifulsoup4 reportlab
```
# How to Run
### Run the application using:
```bash
python "Heuristic Evaluation.py"
```
