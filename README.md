# 📚 PubMed Paper Fetcher

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Poetry](https://img.shields.io/badge/Dependency%20Manager-Poetry-brightgreen) ![License](https://img.shields.io/badge/License-MIT-green)

A Python program to fetch research papers from PubMed with non-academic authors affiliated with pharmaceutical or biotech companies.

## 🚀 Features
- Fetch papers from PubMed based on user queries.
- Identify papers with authors affiliated with pharmaceutical/biotech companies.
- Save results as a CSV file or display them in the console.
- Modular design with CLI support.
- Published to TestPyPI for easy installation.

---

## 📁 Project Structure
```
.
├── pubmed_paper_fetcher/       # Module folder
│   ├── __init__.py             # Makes it a package
│   ├── cli.py                  # Command-line interface logic
│   └── fetcher.py              # Core functions for fetching and processing papers
├── README.md                   # Project documentation
├── pyproject.toml              # Poetry configuration file
├── results.csv                 # Example output file
├── .gitignore                  # Files to ignore in git
└── dist/                       # Distribution files for uploading to PyPI
```

---

## 📦 Installation
### 🔨 Using Poetry (Recommended)
1. Clone the repository:
```bash
 git clone https://github.com/supriya357/pubmed-paper-fetcher.git
 cd pubmed-paper-fetcher
```

2. Install dependencies:
```bash
poetry install
```

3. Build the package:
```bash
poetry build
```

4. Publish to TestPyPI (You have already done this):
```bash
poetry publish -r testpypi
```

---

## 💻 Usage
### Run the Command-Line Tool
```bash
poetry run get-papers-list "Your Query" -f results.csv -d
```
Example:
```bash
poetry run get-papers-list "COVID-19 vaccine" -f results.csv -d
```

### Arguments
- `query`: The search term you want to fetch papers for.
- `-f / --file`: Filename to save results as a CSV (optional).
- `-d / --debug`: Enable debug mode for detailed output (optional).

---

## 📚 How the Code is Organized
1. **`fetcher.py`** (Module):
   - Fetches paper details using the PubMed API.
   - Filters non-academic authors and company affiliations.
   - Saves results to CSV or displays them on the console.

2. **`cli.py`** (Command-line Interface):
   - Handles user inputs from the terminal.
   - Passes arguments to functions in `fetcher.py`.

3. **`pyproject.toml`** (Configuration File):
   - Manages dependencies and packaging using Poetry.

---

## 🧰 Tools Used
- **Python 3.8+**
- **Poetry** for dependency management and packaging.
- **Twine** for uploading packages to TestPyPI.
- **Requests** for making HTTP requests to the PubMed API.

---

## 🔗 Relevant Links
- [Python](https://www.python.org/)
- [Poetry](https://python-poetry.org/)
- [TestPyPI](https://test.pypi.org/)
- [GitHub Repo](https://github.com/supriya357/pubmed-paper-fetcher)

---

## 📄 License
This project is licensed under the MIT License.

## 📢 Contact
For any issues or suggestions, feel free to reach out!



