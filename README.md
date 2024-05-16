# BahasaRojakSentimentAnalysis 😸😑😾

Handling Bahasa Rojak (Malaysian Code Mixing Language) OOV and performing Sentiment Analysis using downstreamed Cross Lingual Model XLM-RoBERTa (XLM-T) 

Jupyter Notebooks includes detailing of: 
1. Text Preprocessing
2. Model Fine Tuning
3. New Data Inference Pipeline 

For further resources regarding the project, please access link below.

Access the project here: https://drive.google.com/drive/folders/12Uir9KE4B1VL6oQWdj2BWvCUZOC0vWa2

## Ablation Settings:<br> 
| Preprocessing Method      | Model 1 (V1) | Model 2 (V2) | Model 3 (V3) | Model 4 (V4) |
|---------------------------|--------------|--------------|--------------|--------------|
| Remove URLs               | ✔            | ✔            | ✔            | ✔            |
| Convert Lowercase         | ✔            | ✔            | ✔            | -            |
| Remove Punctuations       | ✔            | ✔            | ✔            | -            |
| Remove Irregular Spaces   | ✔            | ✔            | ✔            | ✔            |
| Handle OOV                | ✔            | ✔            | ✔            | ✔            |
| Remove Stopwords          | ✔            | ✔            | -            | -            |
| Chinese Character Segmentation | -      | ✔            | ✔            | -            |
| Remove Rare Words         | -            | -            | ✔            | -            |

![image](https://github.com/Bernardbyy/BahasaRojakSentimentAnalysis/assets/75737130/58bd9cd0-1aa5-448e-a97f-a584aa348bdc)

## Model Results:<br>
|           | Precision |      | Recall |      | F1-Score |      | Accuracy |
|-----------|-----------|------|--------|------|----------|------|----------|
|           | 0         | 1    | 0      | 1    | 0        | 1    |          |
| Model V1  | 0.716     | 0.830| 0.840  | 0.702| 0.773    | 0.760| 0.767    |
| Model V2  | 0.768     | 0.771| 0.735  | 0.801| 0.751    | 0.786| 0.770    |
| Model V3  | 0.794     | 0.703| 0.691  | 0.802| 0.739    | 0.749| 0.744    |
| Model V4  | 0.861     | 0.833| 0.802  | 0.884| 0.831    | 0.858| 0.845    |

## Web Application to Test out the Sentiment Analysis Model (w/ Twitter Web Scraping):<br>
### Scrap tweets related to "britneyspears":<br>
![image](https://github.com/Bernardbyy/BahasaRojakSentimentAnalysis/assets/75737130/aaf773ea-a43f-428c-a3b3-c86804748508)

### Inference Results:<br>
![image](https://github.com/Bernardbyy/BahasaRojakSentimentAnalysis/assets/75737130/7a4712e1-0891-4fa4-ba13-41b9f434069c)


