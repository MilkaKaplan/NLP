# Portfolio NLP
A collection of tools, models, and notebooks for solving NLP tasks such as text classification, sentiment analysis, metaphors, translation and multilingualism, multimodality, and style transformation

## Here are completed NLP / NLI projects 
___
| #| name of project| description| stack| language|
|---|---------------|------------|------|---------|
| 1.| [Researching of data from the **Yandex.Musik**  service - a comparison of users of two cities](https://github.com/MilkaKaplan/Portfolio/blob/research-data-analysis/Yandex.Musik/Music.ipynb)| This notebook contains a component of a larger project focused on zero-shot text classification. It uses the `facebook/bart-large-mnli` model from the `transformers` library to read structured JSON files, extract sentences from specific fields (like `"petitioner advocate transcript"`), and classify each sentence against a predefined set of labels indicating tone or stance (e.g., 'Confidence', 'Hesitation', 'Anger', 'Neutrality', 'Defensiveness', 'Frustration'). The code processes multiple input files from a specified directory and saves the classification results, including confidence scores for each label per sentence, into new JSON output files.| python, pandas| English|
