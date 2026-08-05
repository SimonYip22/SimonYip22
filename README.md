# Simon Yip

MBBS and machine learning engineer building end-to-end clinical systems across time-series modelling and clinical NLP

Currently contributing to ML research workflows at RadNomics involving large-scale radiology report generation, data augmentation, and proprietary LLM evaluation

## Featured Work

### Clinical Entity Extraction-Validation System

_Python · PyTorch · Hugging Face Transformers · Scikit-learn · Pandas · FastAPI · Docker · Google Cloud Run · GitHub Actions_

- Hybrid clinical NLP system generating structured entity outputs from adult ICU progress notes
- Implemented rule-based regex extraction schemas for recall-focused extraction of **3 clinical entity types**
- **Fine-tuned a BioClinicalBERT classifier on 1000+ manually annotated entities,** and integrated precision-oriented threshold tuning for final entity validation
- **Extracted 780,000+ structured entities** from a preprocessed ICU corpus of **160,000+ notes (30,000+ stays)**
- Transformer validation achieved **+45.9% in precision** and **−83.3% in false positives** relative to rule-only baseline
- Deployed inference pipeline as **stateless, containerised API on Google Cloud Run** with GitHub Actions versioning

[Live API](https://clinical-nlp-api-1064509144938.europe-west1.run.app/docs) · [Repository](https://github.com/SimonYip22/Clinical-Entity-Extraction-Validation-System) · [Zenodo DOI](https://doi.org/10.5281/zenodo.20018309)

<p align="center">
  <img src="system_architecture.png" width="650" alt="Clinical entity extraction and validation system architecture"/>
</p>


### Time-Series ICU Patient Deterioration Predictor  

_Python · PyTorch · LightGBM · Scikit-learn · Pandas · NumPy · SHAP_

- Dual-architecture ICU early warning system combining a Temporal CNN (TCN) and LightGBM to predict NEWS2-derived deterioration outcomes across **3 clinical risk dimensions**
- Transformed clinical data across **140 ICU stays** using CO2 retainer logic, GCS mapping, and oxygen protocols
- **Engineered 171 timestamp-level features (8 vital parameters; 96-hour windows)** and **40 aggregated patient-level features** from **70,000+ extracted time-series observations**
- TCN achieved **+9.3% AUC improvement** for acute-event detection; LightGBM achieved **−68% Brier score and −48% RMSE** for prolonged risk exposure
- Implemented clinician-interpretable SHAP and saliency mapping for feature contribution insights

[Repository](https://github.com/SimonYip22/Time-Series-ICU-Patient-Deterioration-Predictor) · [Zenodo DOI](https://doi.org/10.5281/zenodo.18487174)

<p align="center">
  <img src="tcn_architecture_detailed.png" width="650" alt="Temporal convolutional network architecture"/>
</p>


## Professional Experience

**Applied Machine Learning Engineer @ RadNomics Ltd** 

- **Processed 2.3M+ radiology reports** and developed a data augmentation pipeline generating **17M+ report pairs** across **7 clinically relevant reconstruction tasks**
- Ran large-scale ML research workflows in containerised remote environments on **GKE-based cloud infrastructure,** with Git-based collaboration
- Built an LLM benchmarking framework across **6 candidate language models,** generating **42,000 reconstructed reports** and evaluating using text and semantic similarity metrics, clincal scoring, and operational performance metrics

## Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,scikitlearn,git,github,githubactions,postgres,mysql,regex,vscode,fastapi,docker,kubernetes,gcp,bash" />
</p>

- **Machine Learning:** PyTorch, TensorFlow/Keras, Scikit-learn, LightGBM, Hugging Face Transformers, Clinical NLP, LLM Evaluation
- **DevOps:** Google Cloud Platform (GKE, Cloud Run), Kubernetes, Docker, FastAPI, GitHub Actions (CI/CD)
- **Data & Engineering:** Python, Pandas, NumPy, SQL (PostgreSQL/MySQL), Seaborn, Bash

## Education

- ***MSc, Computer Science with Artificial Intelligence*** @ City St George’s, University of London
- ***MBBS, Medicine*** @ Norwich Medical School, University of East Anglia

## Clinical Experience

#### _Clinical Research_
- Lacertus syndrome and its surgical management using WALANT - our first 12 cases (Research Poster)
- Giant trichoblastic carcinoma initially misdiagnosed as basal cell carcinoma (Case Report)

#### _Audit Cycles_
- Head and Neck Surgery, Integrated Care Pathway Surgical Proforma Audit
- Plastic Surgery, Free Flap Surgical Outcomes Audit

#### _Healthcare Data Skills_
- **Clinical Informatics:** EHR Systems (ICE, SystmOne, MediViewer, EPMA), NEWS2, GDPR
- **Clinical Research:** Audit Methodology, Literature Review, Critical Appraisal, Manuscript Preparation


## Archives

- _Yip, S. (2026). Clinical Entity Extraction-Validation System (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.20018309_
- _Yip, S. (2026). Time-Series ICU Patient Deterioration Predictor (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.18487174_

##

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SimonYip22&theme=radical" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SimonYip22&layout=compact&theme=radical" />
</p>

##
