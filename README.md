# Annual-developer-survey-analysis

The present data analysis project builds upon the 2023 survey and explores some of its features with emphasis on the data and business analysis field of industry.  
The survey data has already been cleaned by the stack overflow team and is ready to be used for anaylsis. As the survey result csv file is too large for githubs default upload I'll reference it here instead.  
It is part of my portfolio in data analysis. You can find the file at [insights.stackoverflow.com/survey](https://insights.stackoverflow.com/survey).

# Installation

You can view a rendered version of the notebook [here](SO-2023-survey.ipynb).  
Or a pdf version of the notebook [here](SO-2023-survey.pdf)

### Prerequisites
- **Python:** Ensure that Python is installed on your machine. You can download it from [python.org](https://www.python.org/).
- **Jupyter Lab:** Install Jupyter Lab using the following command in your terminal or command prompt:
  ```bash
  pip install jupyter lab
- **External Libraries:** Use `pip install` for library installation.
  ```bash
  pip install pandas numpy matplotlib ipywidgets scipy

### Steps  
1. **Download:** Download the Jupyter notebook file [SO-2023-survey.ipynb](SO-2023-survey.ipynb) from this repository to your local machine.

2. **Run Jupyter Lab Server:**
  - Open a terminal or command prompt.
  - Navigate to the directory where you saved the notebook file.
  - Run the following command:
    ```bash
    jupyter lab

3. **Access the notebook:**
  - Open your web browser and go to the URL displayed in the terminal.
  - Navigate to the notebook file and click on it to open.
    
4. **Interact with the Notebook:**
  - Execute code cells using the "Run" button or by pressing Shift + Enter.

# Usage
It is recommended to `Run all cells` as this ensures all cells to execute properly. 

# Structure
1. **SO-2023-survey.ipynb:** Jupyter notebook containing queries and figures about the Stackoverflow developer survey.

2. **SO-2023-survey.pdf:** Pdf rendition of the aforementioned jupyter notebook.

3. **README.md:** Instructions on how to get started, install dependencies, and use the Jupyter notebook.

4. **/stack-overflow-developer-survey-2023::** Schema of the survey listing question id, question name and question text body. 

# Dependencies
- **Python:** Version 3.10.12
- **Jupyter Lab:** Version 4.0.5
- **Libraries:**
  - NumPy: Version 1.25.2
  - pandas: Version 2.0.3
  - matplotlib: Version 3.7.2
  - IPython: Version 8.14.0
  - seaborn: Version 0.12.2

# License
This project is licensed under the MIT License - see the [LICENSE](license.txt) file for details.

# References
The survey data can be openly accessed via [insights.stackoverflow.com/survey](https://insights.stackoverflow.com/survey)


