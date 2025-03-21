# 📚 PubMed Paper Fetcher - Python Package

A Python program to fetch research papers from PubMed based on a user-specified query. It identifies papers with at least one author affiliated with pharmaceutical or biotech companies and returns the results as a CSV file.

---

## 🌟 Features
- 🔍 Fetches papers from PubMed API using full query syntax.
- 📄 Outputs results as a CSV file with details:
  - **PubmedID**: Unique identifier for the paper.
  - **Title**: Title of the paper.
  - **Publication Date**: Date of publication.
  - **Non-academic Authors**: Authors affiliated with non-academic institutions.
  - **Company Affiliations**: Names of pharmaceutical/biotech companies.
  - **Corresponding Author Email**: Email of the corresponding author.
- 📦 Packaged with Poetry.
- 📤 Published on TestPyPI.

---

## 📁 Project Structure
```
📂 pubmed_paper_fetcher/
│
├── 📄 __init__.py      (Makes it a package)
├── 📄 cli.py           (Command-line interface logic)
├── 📄 fetcher.py       (Module containing core functionalities)
```

---

## ⚙️ Installation

### Clone the Repository
```bash
$ git clone https://github.com/YourUsername/pubmed-paper-fetcher-supri267.git
$ cd pubmed-paper-fetcher-supri267
```

### Install Dependencies
Ensure you have Poetry installed. If not, install via:
```bash
$ pip install poetry
```

Install project dependencies:
```bash
$ poetry install
```

---

## 🚀 Usage

### Command-Line Interface
1. **To fetch papers and display them on console:**
```bash
$ poetry run get-papers-list "COVID-19 vaccine"
```

2. **To save results to a CSV file:**
```bash
$ poetry run get-papers-list "COVID-19 vaccine" -f results.csv
```

3. **To enable debug mode for detailed logs:**
```bash
$ poetry run get-papers-list "COVID-19 vaccine" -d
```

---

## 🔧 Testing the Module (TestPyPI)
Create a virtual environment:
```bash
$ python -m venv test-env
$ .\test-env\Scripts\activate  (Windows)
$ source test-env/bin/activate    (Linux/Mac)
```

Install the package:
```bash
$ pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple pubmed-paper-fetcher-supri267
```

Run the tool:
```bash
$ get-papers-list "Machine learning" -d
```

---

## 📚 Tools & Libraries Used
- **Python** (>=3.8)
- **Requests** (API interaction)
- **Poetry** (Dependency management & Packaging)
- **Twine** (Publishing to TestPyPI)

---

## 📌 Helpful Links
- [PubMed API Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25499/)
- [Poetry Documentation](https://python-poetry.org/docs/)
- [TestPyPI](https://test.pypi.org/)

---

## 📢 Contact
For any issues or suggestions, feel free to reach out!

