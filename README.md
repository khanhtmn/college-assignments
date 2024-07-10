# ML-assignments
Machine learning assignments from college courses

**LBA**: LBA is location-based assignment. I picked a symbol in San Francisco, collected the data (photos of the symbol)  and tried to reconstruct the symbol with PCA (principal component analysis).

**CS156 final**: This is the final project for CS156, machine learning course. In this project, I used natural language to classify comic transcript.
- I scraped the data from https://scrapsfromtheloft.com/, did some text processing and data exploration.
- Then I tokenized the scripts into bag of words that denotes the vocabulary used by the comics. This was done by either Count Vectorizer or TF-IDF Vectorizer.
- I used Neural Network (for only Count Vectorizer) and Logistic Regression (for both Count Vectorizer and TF-IDF Vectorizer) to classify the data.
