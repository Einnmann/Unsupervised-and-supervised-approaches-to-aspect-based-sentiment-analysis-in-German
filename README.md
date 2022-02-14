# Unsupervised-and-supervised-approaches-to-aspect-based-sentiment-analysis-in-German

### Project Content:
 * BERT.ipynb - the Jupyter notebook, which contains the code that allows to train and test BERT and compute BERT's sentence embeddings;
 * sentiart_bert.ipynb - the Jupyter notebook, which contains the code allowing to combine SentiArt (1) and BERT (2);
 * data - a folder, which contains BERT's sentence embeddings and the indexes of the test samples.

### Description:
  In this work, the unsupervised vector space model (VSM)-based algorithm called SentiArt and the CatBoost regressor were used to predict the continuous valence values of literary texts evaluated by human raters. The predictive accuracy of the valence values was improved by incorporating new features into the dataset and adjusting the data based on the list with valence shifters and subject-verb-object (SVO) triplets, which yielded an 𝑅2 value of 0.338. The BERT model was also utilized for predicting continuous valence values and obtained an 𝑅2 value of 0.443. In a final approach, BERT’s sentence embeddings were added to those of SentiArt, and this hybrid model outperformed the other two models with an 𝑅2 value of 0.458.
  
  The results suggest that incorporating new features and considering the valence shifter and SVO triplets benefit the predictive accuracy of SentiArt. In addition, SentiArt and BERT showed complementary strengths, and therefore their combination produced the most promising result. 

### Important papers:

(1) Jacobs, A. M., & Kinder, A. (2019). Computing the Affective-Aesthetic Potential of Literary Texts. AI, 1(1), 11–27. doi:10.3390/ai1010002

(2) Alghanmi, I., Espinosa Anke, L., & Schockaert, S. (2020). Combining BERT with Static Word Embeddings for Categorizing Social Media. In Proceedings of the Sixth Workshop on Noisy User-generated Text (W-NUT 2020) (pp. 28–33). doi:10.18653/v1/2020.wnut-1.5
