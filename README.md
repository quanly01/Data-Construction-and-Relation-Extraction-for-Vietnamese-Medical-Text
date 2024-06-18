## Vietnamese Medical Relation Extraction using PhoBERT

This repository contains the implementation and analysis of a PhoBERT-based model for Vietnamese medical relation extraction. The project aims to bridge the gap between Vietnamese and English medical entity relationship extraction resources, promoting the use of information technology in Vietnamese healthcare and ultimately benefitting the community.

**Motivation:**

-  The lack of Vietnamese medical entity relationship extraction resources hinders the development of healthcare applications in Vietnam.
-  This project focuses on constructing a Vietnamese medical entity relationship extraction dataset and applying the PhoBERT model to classify defined relationships within the dataset.

**Methodology:**

-  The project presents an overview of the Unified Medical Language System (UMLS) and fundamental concepts in entity recognition and relationship extraction.
-  A comprehensive analysis of the PhoBERT model is provided, comparing its performance with the XLM-R model.
-  The PhoBERT model is applied to the VLSP 2020 Relation Extraction dataset.
-  The project outlines the process of constructing a Vietnamese medical entity and relationship label set based on international standards, data collection from Wikipedia, and annotation using the INCEpTION tool.

**Results:**

-  Experimental results demonstrate the high performance of the PhoBERT model on the sample dataset.
-  The model achieved a Macro-Average F-score of 0.67 and a Micro-Average F-score of 0.85 on the training set.
-  On the development set, the Macro-Average F-score reached 0.65 and the Micro-Average F-score reached 0.78.

**Availability:**

-  The research documentation is available in the Excel file or the thesis report file named "Nguyen_Chi_Dung_KLTN."
-  The dataset is currently under development and is not publicly available. However, a sample is included in the "VLSP2020_RE.zip" file.

**Contact:**

For further inquiries, please contact chidung05102002@gmail.com.


**Acknowledgments:**

We thank the VLSP 2020 organizers for providing the dataset and the developers of PhoBERT and XLM-R for their open-source contributions.

**Future Work:**

-  Further expand the Vietnamese medical entity and relationship dataset.
-  Explore other language models for Vietnamese medical relation extraction.
-  Develop real-world applications leveraging the constructed dataset and trained models.
