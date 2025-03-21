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

- **Python** (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn, Statsmodel)
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

### 2️⃣ Install Dependencies



```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

Open happiness_project.ipynb and execute cells in order.

### 4️⃣ Deactivate Virtual Environment

When finished working in the repo, deactivate the virtual environment.

```bash
# For Linux/Mac and GitBash
deactivate
```

---

### 5️⃣ Summary of Virtual Environment Commands

| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

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
