# Department of Computer Science

## COS781 Project Proposal

### Clustering Analysis on Sentiment Tagged Parallel Corpus for Luganda and Swahili

**Author**: Arno Jooste (u21457451)  
**Supervisors**: Prof. Vukosi Marivate, Ms. Seani Rananga, Dr. Abiodun Modupe  
**Date**: October 2024  

---

### Introduction

In recent years, research on sentiment analysis has largely neglected African languages. This project addresses this gap by exploring how clustering techniques can be applied to sentiment-tagged corpora in low-resource languages, specifically Luganda and Swahili.

This study investigates:
1. The effectiveness of clustering algorithms specifically KMeans.
2. The impact of feature extraction methods (BoW, or TF-IDF) and topic modeling (LDA).
3. The insights clustering and topic modelling provides into sentiment patterns in Luganda and Swahili texts.

The dataset used is the [Sentiment Tagged Parallel Corpus for Luganda and Swahili](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/XSGIKR), containing thousands of sentences tagged with sentiment labels.

The overall aim is to uncover meaningful relationships between sentiment labels and topics while contributing to the broader field of sentiment analysis for African languages.

---

### Use the code

This project was completed using the GPU T4 environment provided by [Kaggle](kaggle.com). To use the Python notebook, follow the folloing instructions:

1. Log in/Sign up for a Kaggle account.
2. Create a new notebook.
3. Download this project's notebook located in the `src` folder.
4. Import the downloaded notebook into your newly created notebook.
5. Download this project's data files located in the `data` folder.
6. In Kaggle, use the open (if not already opened) the panel on the right to upload a new dataset (`Input` -> `Upload` -> `New Dataset`).
7. Upload the downloaded data files separately:

   7.1 Uploading `swahili-stopwords`: open the downloaded folder and drag and drop all the files into Kaggle and name the new dataset `swahili-stopwords`. It is important to not drag and drop the folder but all the files, since this will cause problems with the file paths used in the notebook.
   
   7.2 Uploading `Makerere_Sentiment_corpus_Luganda_and_Kiswahil_translations`: Repeat step 6 to create a new dataset. Drag and drop the downloaded CSV file into Kaggle and name the dataset `Makerere_Sentiment_corpus_Luganda_and_Kiswahil_translations`. It is important to name these datasets as instructed since it will cause issues when using the file paths.
9. Turn on the GPU T4 x2 accelerator from the panel on the right.
10. Have fun!

---

Detailed documentation for each function can be found in the notebook file.
