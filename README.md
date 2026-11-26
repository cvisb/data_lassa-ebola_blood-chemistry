# Lassa/Ebola Blood Chemistry Dataset

Blood chemistry data of Ebola or Lassa survivors and non-survivors during the acute phase of infection. Data were collected with a Piccolo Xpress Chemistry Analyzer.

| | |
|---|---|
| Records | 1,435 |
| Samples | 1,435 |
| With a patient identifier | 1,435 |
| Cohort | Lassa (1,161), Ebola (273), Unknown (1) |
| Outcome | Unknown (895), Survivor (296), Dead (244) |
| Country | Sierra Leone (1,434), Liberia (1) |
| Years | 2007–2020 |
| Technique | Blood Chemistry Measurement |
| Version | 0.4 |

## Files

| File | Rows | Description |
|---|---|---|
| `metadata.csv` | 1,435 | Sample and patient metadata |
| `blood_chemistry.csv` | 1,435 | Blood chemistry panel |
| `dataset.json` | – | Dataset description in schema.org format |

## Columns in `metadata.csv`

| Column | Description |
|---|---|
| `experimentID` | Experiment identifier |
| `sample_id` | Sample identifier, shared across CViSB datasets |
| `timepoint` | Point in care the reading was taken at |
| `patientID` | Patient identifier, where known |
| `cohort` | Ebola, Lassa, Unknown |
| `outcome` | Dead, Survivor, Unknown |
| `country` | Country of infection |
| `year` | Year of infection |

## Columns in `blood_chemistry.csv`

| Column | Description |
|---|---|
| `sodium` | Sodium (mmol/L), or `Above range` |
| `potassium` | Potassium (mmol/L), or `Below range` / `Above range` |
| `chloride` | Chloride (mmol/L), or `Below range` |
| `totalCarbonDioxide` | Total carbon dioxide (mmol/L), or `Below range` |
| `calcium` | Calcium (mmol/L), or `Below range` |
| `glucose` | Glucose (mmol/L), or `Below range` / `Above range` |
| `bloodUreaNitrogen` | Blood urea nitrogen (mmol/L), or `Below range` / `Above range` |
| `creatinine` | Creatinine (µmol/L), or `Below range` |
| `totalProtein` | Total protein (g/L), or `Below range` |
| `albumin` | Albumin (g/L), or `Below range` |
| `totalBilirubin` | Total bilirubin (µmol/L) |
| `alkalinePhosphatase` | Alkaline phosphatase (U/L), or `Below range` |
| `alanineAminotransferase` | Alanine aminotransferase (U/L), or `Below range` / `Above range` |
| `aspartateAminotransferase` | Aspartate aminotransferase (U/L), or `Below range` / `Above range` |

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite the Center for Viral Systems Biology (CViSB).

Funded by NIAID award U19AI135995.
