#  Task 1 - Movie Genre Classification (CodSoft Internship)

This project aims to classify the genre of a movie based on its plot summary using a Naive Bayes classifier and TF-IDF vectorization.





## Data
The dataset contains movie details: `index`, `movie_name`, `genre`, and `plot`.
- Format: .txt files inside ZIP archives
- Preprocessing includes handling null values, converting text to lowercase, and TF-IDF vectorization.
## Tools

- Python
- pandas
- scikit-learn
- TfidfVectorizer (text vectorization)
- Multinomial Naive Bayes
- matplotlib (for visualization)

## Steps performed

1. Loaded and extracted training and testing datasets
2. Cleaned and preprocessed plot data
3. Vectorized plots using **TF-IDF** with 2000 features
4. Trained a **Multinomial Naive Bayes** classifier
5. Evaluated performance using:
   - Accuracy Score
   - Classification Report (Precision, Recall, F1-score)
##  Visualization

- Bar plot showing number of predicted genres
- Confusion matrix to understand correct vs incorrect classifications
## Results

- **Accuracy**: ~50.8%
- Best performance on frequent genres like `drama` and `documentary`
- Lower scores for underrepresented genres (due to class imbalance)
