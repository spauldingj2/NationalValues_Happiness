# National Values and Happiness

**Author**: Jeanne Spaulding

**Project Repository**: https://github.com/spauldingj2/NationalValues_Happiness

## Project Overview

This project will look at the potential correlation between national values as assessed by the **World Values Survey (WVS)** and happiness according to the **World Happiness Report (WHR)** for the year 2018. Data will be stored in a **SQLite database**, and analyzed via multiple linear regression analysis using **Python**.


## Features & Visualizations

- Happiness score & Values Indices: 
    - Scatterplots for association of values with happiness
    - Correlation Matrix for strength of relationship among variables
    - Multiple Linear Regression of values indices as predictors of happiness score 


## Data Sources

- **World Values Survey**: Data regarding insights into societal beliefs, values, and cultural norms of people across the world. 
- **World Happiness Report**: Data regarding happiness across countries utilizing life evaluations from the Gallup World Poll.  

## Technologies Used

- **Python** (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn, Statsmodels)
- **SQLite** (for local database)
- **Jupyter Notebook** 
- **GitHub** (for version control)

## Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/spauldingj2/NationalValues_Happiness
```

After you have cloned the repository to your machine, navigate to the project folder in GitBash/Terminal.

```bash
cd [your_project_folder]
```

### 2️⃣ Create Virtual Environment & Install Dependencies

```bash
# Windows
python -m venv venv
# Mac/Linux
python3 -m venv venv

# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate   

pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

**Windows:** Access the jupyter server by copying and pasting one of the provided URLs in the output,
or CTRL + click the link in the output.

Open the happiness_project.ipynb file.  Execute each cell in order or select "Run All" at the top of the notebook.

### 4️⃣ Deactivate Virtual Environment

When finished working in the repo, deactivate the virtual environment.

```bash
# For Mac/Linux and Windows
deactivate
```

### 5️⃣ Summary of Virtual Environment Commands

| Command    | Mac/Linux                         | Windows                           |
| -------    | ---------                         | -------                           |
| Create     | `python3 -m venv venv`            | `python -m venv venv`             |
| Activate   | `source venv/bin/activate`        | `venv/Scripts/activate`    |
| Install    | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate`                      | `deactivate`                      |

---

## Troubleshooting

If errors occur:

- Ensure all dependencies are installed with pip install -r requirements.txt.
- Run jupyter notebook inside the virtual environment.
- Verify database files exist (happiness_database.db).

---

## License

This project is open-source under the MIT License.

---

## AI Disclaimer

Google Gemini was used as a co-intelligence resource when developing this project.

---

## Additional Documentation

- [Project Plan](SpauldingProjectPlan.docx)
- [Happiness Project Analysis](happiness_project.ipynb)
- [Data Dictionary](HappinessProject_DataDictionary.docx)
- [World Values Survey Codebook](WVS7_Codebook.pdf)


---

## References & Resources

- Cornell University. (2024).  Python for Data Science e-course. Class Notes
- Kreibich, J. (2010). Using SQLite, First Edition.
- Landup, D. (2021). Data Visualization in Python, First Edition.
- Navlani, A., Fandango, A., and Idris, I. (2021).  Python Data Analysis, Third Edition.
- Shields, W. (2020). SQL Quick Start Guide. 
- Tabachnick, B. and Fidell, L. (2007). Using Multivariate Statistics, Fifth Edition. 
- World Happiness Report. https://worldhappiness.report/
- World Values Survey. https://www.worldvaluessurvey.org/



