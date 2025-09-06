# Movie Recommendation System

This project is a movie recommendation system that provides personalized and relevant movie suggestions. The core of the system is a **content-based filtering** model.

### How It Works

The system operates in two main phases:

1.  **Data Processing**: A dataset of over 5,000 movie records is cleaned and preprocessed using various **Natural Language Processing (NLP) techniques**. Key features like genres, cast, and keywords are transformed into a usable format.

2.  **Recommendation Engine**: The processed data is vectorized to represent movie features as numerical vectors. **Cosine similarity** is then used to measure the similarity between movies. When a user selects a movie, the system finds and recommends other movies that are most similar.

### Key Features

* **Content-Based Filtering**: Recommends movies based on the similarity of their attributes rather than user-user interactions.
* **NLP Techniques**: Uses NLP to clean and prepare textual data, improving the quality of recommendations.
* **Scalable Design**: The system is designed to provide highly relevant and personalized recommendations efficiently.

### Technologies Used

* **Python**: The primary programming language.
* **Scikit-learn**: For implementing cosine similarity.
* **NumPy & Pandas**: For data manipulation and analysis.

### Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ayushrajpoot2308/Movie-Recommendation-System.git](https://github.com/ayushrajpoot2308/Movie-Recommendation-System.git)
    cd Movie-Recommendation-System
    ```
2.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
