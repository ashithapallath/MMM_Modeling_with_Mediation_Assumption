# MMM Modeling with Mediation Assumption

Analyzes a 2-year weekly marketing dataset to quantify how paid media, email/SMS, price, promotions, and followers drive Revenue, treating Google spend as a mediator for social/display channels.

---

##  Highlights
- Captures **price elasticity**, **promo lift**, and **diminishing returns** on spend.  
- Estimates how much **social/display channels work through Google vs directly**.  
- Uses **blocked/rolling time-series cross-validation** to avoid look-ahead bias.  

---

##  Repository Contents
| File | Description |
|------|-------------|
| `Assessment2_mmm_modeling_.ipynb` | Full notebook: data prep → modeling → diagnostics → insights |
| `README.md` | This file |
| `PROJECT_DOC.md` | Full project documentation with methodology and details |

---

##  Setup
```bash
git clone https://github.com/ashithapallath/MMM_Modeling_with_Mediation_Assumption.git
cd MMM_Modeling_with_Mediation_Assumption

python -m venv venv
source venv/bin/activate   # (or venv\Scripts\activate on Windows)

pip install -r requirements.txt
jupyter notebook Assessment2_mmm_modeling_.ipynb
