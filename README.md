# 🧠 End-to-End Data Science Project

A complete production-grade ML pipeline built using modular architecture: from data ingestion to model evaluation, with YAML config-driven design, component-based codebase, and frontend API endpoints. Ideal for real-world deployment & recruiter showcase.

---

## ⚙️ Workflows – ML Pipeline

1. 🔽 **Data Ingestion**
2. ✅ **Data Validation**
3. 🔁 **Data Transformation** – Feature Engineering, Data Preprocessing
4. 🤖 **Model Trainer**
5. 📊 **Model Evaluation** – using **MLflow** & **DagsHub**

---

## 🧠 Full Project Workflow

1. 🛠️ Update `config.yaml`
2. 🧬 Update `schema.yaml`
3. 📊 Update `params.yaml`
4. 🧱 Update the `config_entity.py` under `entity`
5. ⚙️ Update the `Configuration Manager` under `src/config/`
6. 🧩 Update the `components`:  
   - `data_ingestion.py`  
   - `data_validation.py`  
   - `data_transformation.py`  
   - `model_trainer.py`  
   - `model_evaluation.py`  
7. 🧃 Create Pipelines:  
   - `data_ingestion_pipeline.py`  
   - `data_validation_pipeline.py`  
   - `data_transformation_pipeline.py`  
   - `model_trainer_pipeline.py`  
   - `model_evaluation_pipeline.py`  
   - `prediction_pipeline.py`  
8. 🚀 Run with `main.py`

---

## 🌐 Frontend

- `app.py`: Flask App
- `templates/`: `index.html`, `results.html`
- API Endpoints:
  - `/predict`
  - `/train`
  - `/batch-predict`

---

## 🧰 Tech Stack

- Python 🐍
- Scikit-learn 🔍
- Pandas & NumPy 📊
- MLFlow 🔄
- Flask 🌐
- YAML-based Configuration 📄
- Docker 🐳 (optional)
- GitHub Actions CI/CD ⚙️

---

## 🧾 Folder Structure

```
.gthub/
    └── workflows/
config/
    └── config.yaml
research/
    ├── 1_data_ingestion.ipynb
    ├── 2_data_validation.ipynb
    ├── 3_data_transformation.ipynb
    ├── 4_model_trainer.ipynb
    ├── 5_model_evaluation.ipynb
src/
 └── datascience/
     ├── components/
     │   ├── data_ingestion.py
     │   ├── data_validation.py
     │   ├── data_transformation.py
     │   ├── model_trainer.py
     │   └── model_evaluation.py
     ├── config/
     │   └── configuration.py
     ├── entity/
     │   └── config_entity.py
     ├── pipeline/
     │   ├── data_ingestion_pipeline.py
     │   ├── data_validation_pipeline.py
     │   ├── data_transformation_pipeline.py
     │   ├── model_trainer_pipeline.py
     │   ├── model_evaluation_pipeline.py
     │   └── prediction_pipeline.py
     ├── utils/
     │   └── common.py
templates/
    ├── index.html
    └── results.html
params.yaml
schema.yaml
requirements.txt
main.py
app.py
README.md
```

---

## 👩‍💼 For Recruiters

✅ **Real-World Ready**: Modular, YAML-configured, CI/CD-ready  
✅ **Explainable**: Every step has `research.ipynb` for experiments  
✅ **Extensible**: Easily plug and play with other models or APIs  
✅ **Frontend + Backend**: Comes with Flask + HTML templates  
✅ **Proven Stack**: Uses MLFlow, DagsHub, YAML, and component abstraction

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/Aparna-k246/datascienceproject.git

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install requirements
pip install -r requirements.txt

# 4. Run the main pipeline
python main.py

# 5. Launch the app
python app.py
```


## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

🌟 **Give this repo a star if you found it helpful!**  
