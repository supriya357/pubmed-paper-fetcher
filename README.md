Task Description
 Your task is to write a Python program to fetch research papers based on a user-specified query. The
 program must identify papers with at least one author affiliated with a pharmaceutical or biotech
 company and return the results as a CSV file.
 Problem Details
 1. Source of Papers
 ○ Fetchpapersusing the PubMed API
 ○ Theprogramshouldsupport PubMed's full query syntax for flexibility.
 2. Output Requirements
 ○ Returntheresults as a CSV file with the following columns:
 ■ PubmedID:Uniqueidentifier for the paper.
 ■ Title: Title of the paper.
 ■ Publication Date: Date the paper was published.
 ■ Non-academicAuthor(s): Names of authors affiliated with non-academic
 institutions.
 ■ CompanyAffiliation(s): Names of pharmaceutical/biotech companies.
 ■ Corresponding Author Email: Email address of the corresponding author.
 3. Command-line Program Features
 ○ Acceptthequeryasacommand-line argument.
 ○ Providethe following options:
 ■-hor--help:Display usage instructions.
 ■-dor--debug:Printdebug information during execution.
 ■-for--file:Specifythe filename to save the results. If this option is not
 provided, print the output to the console.
 4. CodeOrganization and Environment
 ○ VersionControl:
 ■ UseGitforversion control. The code must be hosted on GitHub.
 ○ DependenciesandSetup:
 ■ UsePoetryfordependency management and packaging.
 ■ Ensurethatrunning poetry install sets up all dependencies.
 ○ Execution:
 ■ Provideanexecutable command named get-papers-list via Poetry.
 5. Documentation
 ○ IncludeaREADME.mdfilewith the following details:
 ■ Howthecodeisorganized.
■ Instructions on how to install dependencies and execute the program.
 ■ Mentionanytools (e.g., LLMs or libraries) used to build the program, along with
 relevant links.
 6. Evaluation Criteria
 ○ Functional Requirements:
 ■ Adherencetotheproblem statement.
 ■ Ability to fetch and filter results correctly.
 ○ Non-functional Requirements:
 ■ Typedpython: Using types everywhere.
 ■ Performance: Efficiency of API calls and processing.
 ■ Readability: Clear and maintainable code with appropriate comments and
 docstrings.
 ■ Organization: Logical separation of concerns (e.g., modular functions and
 classes).
 ■ Robustness: Error handling for invalid queries, API failures, or missing data.
 Bonus points
 Each of these additional points
 1. Break the program into two parts: a module and a command line program that uses the module.
 2. Publish the module in test-pypi.
 Notes
 ● YouarefreetouseLLMtools or other resources to assist in development– please s
 ● Clearly document any external tools used in the README.md.
 ● Assumetheprogramwill be evaluated by automated scripts, so strict adherence to conventions
 is required.
 ● Howtoidentify non-academic authors? You can apply any heuristics (email addresses, words like
 university, labs etc).

## 📌 Helpful Links
- [PubMed API Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25499/)
- [Poetry Documentation](https://python-poetry.org/docs/)
- [TestPyPI](https://test.pypi.org/)

---

## 📢 Contact
For any issues or suggestions, feel free to reach out!

