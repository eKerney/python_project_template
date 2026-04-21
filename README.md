# python_project_template

## Overview
This is an example template for organizing a python data science project.    
You should use this structure to organize your final project.  It allows a clean separation of documentation, notebooks, and python scripts.  Reusing a similar format will make the project workflow more reusable for others in your organization.    

## Summary 
Provide a brief summary of your project here.   

## Installation
To set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/eKerney/python_project_template.git
   cd my-repo
   ```

2. **Create a virtual environment**:
   ```bash
   python -m .venv 

   ```

3. **Install dependencies**:
   ```bash
   # windows CMD
   .venv\Scripts\activate.bat
   pip install -r requirements.txt

   # powershell 
   # .\.venv\Scripts\Activate.ps1

   # bash 
   # source .venv/bin/activate

   ```

4. **Create requirements.txt**:
   ```bash
   pip freeze > requirements.txt 
   # create file with dependencies from existing environment
   ```

## Project Structure
- `notebooks/`: Jupyter notebooks for project workflows and prototyping.
- `src/`: Python modules with reusable functions (e.g., data processing, analysis).
- `data/`: Sample datasets or scripts to fetch data.
- `tests/`: Unit tests for functions in `src/`.
- `docs/`: Documentation files (see below for details).
- `requirements.txt`: Python dependencies for the project.
- `README.md`: Project overview (this file).
   
