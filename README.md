# Ovarian-Cancer-Risk

# Ovarian Cancer Risk and Progression Data

**Institute of Medical Data Processing, Biometrics, and Epidemiology (IBE)**

## About Dataset

This dataset, titled **"Ovarian Cancer Risk and Progression Data"**, contains **200,100 hourly patient records** collected between **January 2019 and December 2024**. The data originates from a healthcare repository hosted by a leading research institute in Munich, Germany. It includes an extensive array of features spanning clinical, genetic, imaging, and demographic dimensions. The dataset represents a diverse population from Munich's urban and suburban regions, ensuring broad demographic and socioeconomic variety.

Ethical protocols were strictly followed, and all personal identifiers were removed to protect patient privacy. This dataset provides invaluable resources for ovarian cancer risk prediction, cancer progression modeling, and advanced machine learning research.

---

## Dataset Composition

The dataset encompasses the following categories of features:

### Clinical Features

- **Age**: Patient's age at diagnosis, ranging from 18 to 90 years.
- **BMI**: Body Mass Index values (15–50), indicating health and weight status.
- **Comorbidities**: Presence of additional diseases, with 30% of patients reporting comorbid conditions.
- **Symptoms**: Binary feature indicating the presence of symptoms like abdominal pain or bloating.
- **CA-125 Levels**: A critical biomarker for ovarian cancer, ranging from 0 to 200.
- **Cancer Stage**: Classification into Stages 0 to IV, reflecting disease progression.
- **Histopathology**: Cancer subtypes (serous, mucinous, clear cell) based on tissue analysis.
- **Previous Treatments**: History of chemotherapy, surgery, or radiation.
- **Menstrual History**: Regular or irregular menstrual patterns.

### Demographic Features

- **Ethnicity**: Patient's ethnic background (Caucasian, Asian, African, Hispanic).
- **Smoking & Alcohol**: Lifestyle habits, with binary indicators.
- **Residence**: Urban or rural living environments.
- **Socioeconomic Status**: Economic categories (Low, Middle, High).

### Genetic Features

- **BRCA Mutation**: Binary indicator for BRCA1/BRCA2 mutations.
- **Gene Expression**: Normalized gene activity values.
- **SNP Status**: Presence of significant single nucleotide polymorphisms.
- **DNA Methylation & miRNA Levels**: Continuous variables capturing molecular markers.

### Imaging-Derived Features

- **Tumor Size & Location**: Dimensions and anatomical origin (Ovary, Fallopian Tube, Peritoneum).
- **Radiomic Features**: Texture, intensity, and shape metrics derived from imaging.
- **Enhancement Patterns**: Contrast enhancement in imaging.
- **Doppler Velocity**: Blood flow velocity within tumors.

### Reproductive and Hormonal Features

- **Parity**: Number of pregnancies (0–3).
- **Oral Contraceptives & Hormone Therapy**: Binary indicators for usage history.
- **Menarche & Menopause Age**: Age at the onset of menstruation and menopause.

---

## Target Variables

- **Risk Label**: Multi-class classification:
  - `0`: No Risk
  - `1`: Low Risk
  - `2`: Medium Risk
  - `3`: High Risk
- **Progression Probability**: Continuous variable (0–1) representing the likelihood of disease progression.

---

## Dataset Utility

This dataset is curated for advancing research in ovarian cancer risk assessment and progression modeling. It is designed to support studies leveraging **machine learning** and **deep learning techniques**, providing a real-world, comprehensive feature set.

Applications include:

- Multi-modal classification.
- Risk stratification.
- Personalized medicine development.

The high-dimensional and balanced representation ensures robust training and evaluation for predictive models. This dataset can be instrumental for researchers aiming to improve ovarian cancer diagnosis and intervention strategies.
