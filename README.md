# ⚽ LaLiga Football Storytelling Notebook (2023–24)

A deep, visual dive into the 2024–25 LaLiga season — exploring match results, upsets, red cards, goal patterns, team form, and more.

Built with curiosity, pandas, and a love for football — especially FC Barcelona.

---

## 📌 What This Project Covers

- Full data cleaning + preprocessing of LaLiga match data
- Team-level stats: wins, losses, draws, goals
- Time-series tracking of league table positions
- Visual breakdown of:
  - Upsets (low-ranked teams beating high-ranked)
  - Comebacks (from losing at halftime)
  - Red card impact on match results
  - Home vs Away performance
- A proxy Expected Goals (xG) model (based on team shooting stats)
- 10+ matplotlib/seaborn visualizations

---

## 📷 Sample Visuals
<img width="1184" height="584" alt="output" src="https://github.com/user-attachments/assets/d2c82246-1e73-4265-8fa1-a6099e3cb55e" />
<img width="980" height="484" alt="xG" src="https://github.com/user-attachments/assets/c410c0dc-8ba5-4b78-bc9e-bdd4c652bb60" />


---

## 🧠 Tech Stack

- Python 3.x  
- Jupyter Notebook  
- pandas  
- matplotlib  
- seaborn  
- numpy  

---

## 🔧 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/laliga-storytelling.git
cd laliga-storytelling

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install requirements
pip install -r requirements.txt

# Open the notebook
jupyter notebook laliga_analysis.ipynb
