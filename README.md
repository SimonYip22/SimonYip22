# Simon Yip 葉詠倫

Applied Machine Learning Engineer building end-to-end clinical ML systems across time-series modelling and NLP. Experience with production-oriented cloud ML workflows (GKE, Kubernetes) at RadNomics  

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,git,github,fastapi,vscode,docker,kubernetes,gcp,linux,bash" />
</p>

## Featured Projects

#### Time-Series ICU Patient Deterioration Predictor  

_Python | PyTorch | LightGBM | scikit-learn | pandas | NumPy_

- Dual-architecture ICU early warning system combining Temporal CNN (TCN) and LightGBM to predict NEWS2-derived deterioration outcomes across 3 clinical risk dimensions

- Clincally validated data preprocessing included CO2 retainer logic, GCS mapping, and supplemental O2 protocols

- Engineered 171 timestamp-level features (8 vital parameters; 96-hour windows) and 40 aggregated patient-level features from 70,000+ time-series observations across 140 ICU stays

- TCN achieved +9.3% AUC improvement for acute-event detection; LightGBM achieved −68% Brier score and −48% RMSE for prolonged risk exposure

- Implemented SHAP and saliency mapping for clinican-interpretable feature insights

[View Repository](https://github.com/SimonYip22/Time-Series-ICU-Patient-Deterioration-Predictor)

https://doi.org/10.5281/zenodo.18487174

<p align="center">
  <img src="tcn_architecture_detailed.png" width="600"/>
</p>


#### Clinical Entity Extraction-Validation System

_Python | PyTorch | Hugging Face Transformers | scikit-learn | pandas | FastAPI | Docker | Google Cloud Run | GitHub Actions_

- Cloud-deployed hybrid clinical NLP system combining rule-based extraction and transformer validation to generate structured entity outputs from ICU progress notes for downstream analysis and ML workflows

- Implemented regex-based extraction schemas for recall-focused extraction of 3 clinical entity types; fine-tuned BioClinicalBERT classifier on 1000+ manually annotated entities for precision-oriented validation layer

- Extracted 780,000+ structured entities from filtered adult ICU corpus of 160,000+ notes (30,000+ stays)

- Transformer validation achieved +45.9% in precision and −83.3% in false positives relative to rule-only baseline

- Deployed inference pipeline as stateless, containerised API on Google Cloud Run; versioned via GitHub Actions

[View Repository](https://github.com/SimonYip22/Clinical-Entity-Extraction-Validation-System)

https://doi.org/10.5281/zenodo.20018309

<p align="center">
  <img src="system_architecture.png" width="600"/>
</p>


## Experience

**Applied Machine Learning Engineer @ RadNomics Ltd** 

- Worked on production-oriented clinical ML/NLP workflows within Kubernetes-based cloud infrastructure on GKE
- Supported large-scale clinical NLP pipeline development involving medical data cleaning, preprocessing, and feature engineering


## Technical Stack


- **Machine Learning:** PyTorch, Scikit-learn, LightGBM, Hugging Face Transformers, NLTK
- **Cloud / Infra:** Google Cloud Platform (GKE, Cloud Run), Kubernetes, Docker
- **Software Engineering:** Python, FastAPI, Git/GitHub, CI/CD (GitHub Actions)
- **Data:** Pandas, NumPy, SQL


## Education

- MSc Computer Science with Artificial Intelligence @ City St George’s, University of London  
- MBBS Medicine @ Norwich Medical School 


## Archives

- Yip, S. (2026). Time-Series ICU Patient Deterioration Predictor (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.18487174
- Yip, S. (2026). Hybrid Clinical Notes Extraction Pipeline (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.20018309


## Clinical Background


**Audit & Research Assistant @ Norfolk and Norwich University Hospital**

#### _Research_
- Lacertus syndrome and its surgical management using WALANT - our first 12 cases (Research Poster)
- Giant trichoblastic carcinoma initially misdiagnosed as basal cell carcinoma (Case Report)

#### _Audits_
- Head and Neck Surgery, Integrated Care Pathway Surgical Proforma Audit

#### _Healthcare Data Skills_
- **Clinical Informatics:** EHR Systems (ICE, SystmOne, MediViewer, EPMA), HL7-FHIR, NEWS2, GDPR
- **Clinical Research:** Audit Methodology, Literature Review, Critical Appraisal, Manuscript Preparation

##

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SimonYip22&theme=radical" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SimonYip22&layout=compact&theme=radical" />
</p>

##
