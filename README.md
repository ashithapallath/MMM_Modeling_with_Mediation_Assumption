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
<img width="1013" height="787" alt="image" src="https://github.com/user-attachments/assets/96367103-bb19-4c29-b4d8-0a07310eed94" />
<img width="1037" height="547" alt="image" src="https://github.com/user-attachments/assets/c2c4be56-6116-461c-ad62-83c2c0e9b508" />
<img width="1038" height="374" alt="download" src="https://github.com/user-attachments/assets/a3e5b09d-7ca3-4148-8e62-aab9fba019af" />
<img width="667" height="374" alt="download (1)" src="https://github.com/user-attachments/assets/36ae62e3-2013-4a73-b90d-112654014bd4" />
<img width="703" height="547" alt="image" src="https://github.com/user-attachments/assets/dac34d34-71bc-4b8d-bcd1-4824b0b7ab92" />




##  Setup
```bash
git clone https://github.com/ashithapallath/MMM_Modeling_with_Mediation_Assumption.git
cd MMM_Modeling_with_Mediation_Assumption

python -m venv venv
source venv/bin/activate   # (or venv\Scripts\activate on Windows)

pip install -r requirements.txt
jupyter notebook Assessment2_mmm_modeling_.ipynb
