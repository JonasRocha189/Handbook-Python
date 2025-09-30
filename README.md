# 🐍 Python Handbook for Data & Analytics

A comprehensive **Python Handbook** designed as a personal reference for **Data Science, Business Analytics, Machine Learning, and Data Engineering** projects.  
The goal is to provide a structured, practical guide that progresses from basic Python concepts to advanced applications.

---

## 📚 Table of Contents

## [0. Introduction](./0-Basics)
- Python Installation (Anaconda, venv, pip)
- Virtual Environments (venv, conda)
- Package Management (pip, pipx, poetry)
- Using IDEs and Notebooks (VS Code, PyCharm, Jupyter, Colab)
- PEP8 and Coding Best Practices
- Project Organization (folders, modules, packages)

---

## [1. Python Fundamentals](./1-Fundamentals/)
- Basic Syntax and Comments
- Native Data Types: `int`, `float`, `bool`, `str`
- Type Conversion
- Operators: arithmetic, logical, relational
- Data Structures:
  - `list`, `tuple`, `set`, `dict`
  - Common Methods and Operations
- Control Flow:
  - `if`, `else`, `elif`
  - `for`, `while`
  - `break`, `continue`, `pass`
- Functions:
  - Declaration, parameters, return
  - Built-in functions
  - Docstrings and best practices
- Scope and Global vs Local Variables
- Introduction to Type Hints (`typing`)

---

## 2. Advanced Data Handling
- List, Dictionary, and Set Comprehensions
- Generators and Generator Expressions
- String Manipulation:
  - Slicing, string methods
- Regular Expressions (`re`)
- Dates and Times (`datetime`, `calendar`)
- Working with Numbers (`math`, `decimal`, `fractions`)
- File Handling:
  - Reading and Writing (`open`, `with`)
  - CSV, JSON, YAML
  - Compression (`zipfile`, `tarfile`)
- System Modules:
  - `os`, `sys`, `shutil`, `pathlib`

---

## 3. Object-Oriented Programming (OOP)
- Classes and Objects
- Attributes and Methods
- Encapsulation and Access Modifiers
- Inheritance and Polymorphism
- Class and Static Methods and Attributes
- Magic/Dunder Methods (`__init__`, `__str__`, `__repr__`)
- Abstract Classes (`abc`)
- Data Classes (`dataclasses`)
- Property Decorators (`@property`)
- Composition vs Inheritance

---

## 4. Advanced Functions & Control
- Anonymous Functions (`lambda`)
- `map`, `filter`, `reduce`
- Decorators and Higher-Order Functions
- Context Managers (`with`)
- Error Handling:
  - `try`, `except`, `else`, `finally`
  - Raising Exceptions (`raise`)
  - Custom Exceptions
- Logging (`logging`)
- Automated Testing (`unittest`, `pytest`)
- Profiling & Optimization (`cProfile`, `line_profiler`)
- Async & Concurrency (`threading`, `multiprocessing`, `asyncio`)

---

## 5. Data Science with Python
- **NumPy**:
  - Arrays and Vectorized Operations
  - Broadcasting and Linear Algebra
- **Pandas**:
  - Series and DataFrames
  - Indexing and Selection
  - Filters, Aggregations, and `groupby`
  - Merging, Joining, Concatenation
  - Date and Time Handling
- **Visualization**:
  - Matplotlib
  - Seaborn
  - Plotly (optional)
- **Statistics**:
  - Descriptive Measures
  - Basic Probability
  - Distributions
  - Inference (t-tests, Chi-square)

---

## 6. Machine Learning & AI
- **Preprocessing**:
  - Data Cleaning
  - Scaling and Normalization
  - Categorical Encoding (One-Hot)
- **ML Models**:
  - Linear & Logistic Regression
  - Decision Trees and Random Forest
  - Gradient Boosting
  - k-NN, SVM
  - Clustering (k-Means, DBSCAN)
- **Model Evaluation**:
  - Metrics (MSE, RMSE, Accuracy, F1-score, ROC)
  - Cross-Validation
  - Pipelines (`sklearn.pipeline`)
- **Introduction to Deep Learning**:
  - TensorFlow or PyTorch
- **LLM Integration**:
  - Using APIs (OpenAI, LangChain)
  - Text Extraction and Analysis (NLP)

---

## 7. Integrations & Web
- HTTP Requests (`requests`)
- REST APIs and JSON
- Automation & Web Scraping:
  - BeautifulSoup
  - Selenium
- Web Development:
  - Flask, FastAPI, Streamlit
- Workflow Automation:
  - Integration with n8n and ETL Pipelines
  - Task Scheduling (cron, Airflow)

---

## 8. Data Engineering
- Database Connections:
  - Basic & Advanced SQL
  - `sqlite3`, SQLAlchemy
  - BigQuery Connections
- ETL/ELT:
  - Extraction, Transformation, Loading
  - Pipeline Best Practices
  - Handling Large Datasets
  - Optimization and Parallelization

---

## 9. Best Practices & Deployment
- Python Project Structure
- Documentation (docstrings, Sphinx)
- Version Control with Git/GitHub
- Using `.env` and Environment Variables
- Packaging and Publishing Python Packages
- Containers (Docker)
- Deploying Models and Apps
