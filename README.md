# Simon Yip

Machine learning engineer and MBBS with an application within healthcare, focusing on clinical NLP and time-series modelling

Currently building out the ML research pipeline at [RadNomics](radnomics.co.uk), involving clinical dataset augmentation, radiology report generation, LLM benchmarking, and LoRA fine-tuning

## Featured Work

<table width="100%">
  <thead>
    <tr>
      <th width="50%" align="left">
        <a href="https://github.com/SimonYip22/Clinical-Entity-Extraction-Validation-System">Clinical Entity Extraction-Validation System</a>
      </th>
      <th width="50%" align="left">
        <a href="https://github.com/SimonYip22/Time-Series-ICU-Patient-Deterioration-Predictor">Time-Series ICU Patient Deterioration Predictor</a>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="50%" valign="top">
        <em>Python · PyTorch · Hugging Face Transformers · FastAPI · Docker · Google Cloud Run · GitHub Actions</em>
      </td>
      <td width="50%" valign="top">
        <em>Python · PyTorch · Scikit-learn · LightGBM · SHAP</em>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <ul>
          <li>Hybrid clinical NLP pipeline generating structured entity outputs from ICU progress reports</li>
          <li>Combines regex-based extraction across <strong>3</strong> clinical entity types, with validation from a BioClinicalBERT classifier fine-tuned on <strong>1000+</strong> manually annotated examples</li>
          <li>Processed <strong>160,000+</strong> ICU notes across <strong>30,000+</strong> stays, generating <strong>780,000+</strong> candidate entities</li>
          <li>Improved validation precision by <strong>45.9%</strong> and reduced false positives by <strong>83.3%</strong> relative to the rule-only baseline</li>
          <li>Containerised FastAPI inference service with Docker, <a href="https://clinical-nlp-api-1064509144938.europe-west1.run.app/docs">deployed on Google Cloud Run</a> with GitHub Actions CI/CD</li>
        </ul>
      </td>
      <td width="50%" valign="top">
        <ul>
          <li>Dual-architecture ICU deterioration prediction system using a Temporal CNN (TCN) and LightGBM across <strong>3</strong> NEWS2-derived clinical risk outcomes</li>
          <li>Engineered <strong>171</strong> timestamp-level and <strong>40</strong> aggregated patient-level features across <strong>8</strong> vital parameters, from <strong>70,000+</strong> extracted physiological observations across <strong>140</strong> ICU stays</li>
          <li>TCN improved acute-event AUC by <strong>9%</strong> over baseline; LightGBM reduced Brier score by <strong>68%</strong> and RMSE by <strong>48%</strong> for prolonged-risk prediction</li>
          <li>Implemented SHAP and temporal saliency analysis for clinician-interpretability</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        Zenodo DOI: <a href="https://doi.org/10.5281/zenodo.20018309">10.5281/zenodo.20018309</a>
      </td>
      <td width="50%" valign="top">
        Zenodo DOI: <a href="https://doi.org/10.5281/zenodo.18487174">10.5281/zenodo.18487174</a>
      </td>
    </tr>
  </tbody>
</table>

## Professional Experience

***Applied Machine Learning Engineer @ [RadNomics Ltd](radnomics.co.uk)***

- Built core radiology report data pipeline from **2.3M MIMIC-IV reports**, producing **15.6M augmented reconstruction pairs** and a **7,000-task evaluation benchmark** across **7 controlled transformations**
- Created scalable LLM evaluation framework across **9 proprietary and open models**, analysing **63,000 validated generations** using textual, semantic, radiology-aware, and operational metrics
- Ran core ML experimentation within **private GCP/GKE infrastructure**, presenting research findings to founders and directly informing model-selection and product-implementation decisions

## Education

- ***Master of Science (MSc), Computer Science with Artificial Intelligence*** @ City St George’s, University of London
- ***Bachelor of Medicine, Bachelor of Surgery (MBBS), Medicine*** @ Norwich Medical School, University of East Anglia

## Technical Skills

- **Machine Learning:** PyTorch, TensorFlow/Keras, Scikit-learn, LightGBM, Hugging Face Transformers
- **DevOps:** Google Cloud Platform (GKE, Cloud Run), Kubernetes, Docker, FastAPI, GitHub Actions (CI/CD)
- **Data & Engineering:** Python, Pandas, NumPy, SQL (PostgreSQL/MySQL), Git/GitHub

##


