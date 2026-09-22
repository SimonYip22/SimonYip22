# Simon Yip

MBBS and machine learning engineer building end-to-end clinical systems across time-series modelling and clinical NLP

Currently contributing to ML research workflows at RadNomics ltd involving large-scale data augmentation, unsupervised radiology report generation, and LLM fine-tuning and evaluation

## Featured Projects

### Clinical Entity Extraction-Validation System

_Python · PyTorch · Hugging Face · FastAPI · Docker · Google Cloud Run · GitHub Actions_

- Hybrid clinical NLP pipeline generating structured entity outputs from adult ICU progress notes
- Implemented regex-based extraction schemas for recall-focused extraction of **3** clinical entity types
- Fine-tuned and threshold-tuned a BioClinicalBERT classifier on **1000+** manually annotated entities for validation
- Processed **160,000+** ICU notes across **30,000+** stays, extracting **780,000+** structured clinical entities
- Improved validation precision by **45.9%** and reduced false positives by **83.3% relative** to the rule-only baseline
- Containerised inference service with FastAPI/Docker, deployed on Google Cloud Run with GitHub Actions CI/CD

[Live API](https://clinical-nlp-api-1064509144938.europe-west1.run.app/docs) · [Repository](https://github.com/SimonYip22/Clinical-Entity-Extraction-Validation-System) · [Zenodo DOI](https://doi.org/10.5281/zenodo.20018309)

<p align="center">
  <img src="system_architecture.png" width="650" alt="Clinical entity extraction and validation system architecture"/>
</p>


### Time-Series ICU Patient Deterioration Predictor  

_Python · PyTorch · LightGBM · Scikit-learn · SHAP_

- Dual-architecture ICU early warning system combining a Temporal CNN (TCN) and LightGBM for NEWS2-derived deterioration prediction across **3** clinical risk dimensions
- Engineered **171** timestamp-level features and **40** aggregated patient-level features across **8** vital parameters, from **70,000+** extracted time-series observations over **140** ICU stays
- TCN improved acute-event AUC by **9%** over baseline; LightGBM reduced Brier score by **68%** and RMSE by **48%** for prolonged-risk prediction
- Implemented clinician-interpretable SHAP and temporal saliency analysis for feature contribution insights

[Repository](https://github.com/SimonYip22/Time-Series-ICU-Patient-Deterioration-Predictor) · [Zenodo DOI](https://doi.org/10.5281/zenodo.18487174)

<p align="center">
  <img src="tcn_architecture_detailed.png" width="650" alt="Temporal convolutional network architecture"/>
</p>


## Professional Experience

***Applied Machine Learning Engineer @ RadNomics Ltd***

- Built a radiology report data augmentation pipeline from **2.3 million** MIMIC-IV reports, producing **15.6 million** supervised reconstruction pairs and a **7,000**-task evaluation benchmark across seven controlled transformations
- Implemented scalable LLM evaluation framework across **9** proprietary and open models, analysing **63,000** validated generations using textual, semantic, radiology-aware, and operational metrics
- Developed reproducible research within private GCP/GKE infrastructure environment, with Git-based code review

## Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,scikitlearn,git,github,githubactions,postgres,mysql,regex,vscode,fastapi,docker,kubernetes,gcp,bash" />
</p>

- **Machine Learning:** PyTorch, TensorFlow/Keras, Scikit-learn, LightGBM, Hugging Face Transformers, PEFT/LoRA, vLLM
- **DevOps:** Google Cloud Platform (GKE, Cloud Run), Kubernetes, Docker, FastAPI, GitHub Actions (CI/CD)
- **Data & Engineering:** Python, Pandas, NumPy, SQL (PostgreSQL/MySQL), Git/GitHub

## Education

- ***MSc, Computer Science with Artificial Intelligence*** @ City St George’s, University of London
- ***MBBS, Medicine*** @ Norwich Medical School, University of East Anglia

##

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SimonYip22&theme=radical" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SimonYip22&layout=compact&theme=radical" />
</p>

##
